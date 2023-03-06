# Exploration of Geothermal Resources

This chapter is about the exploration and evaluation of geothermal resources

 ## Explain what is exploration (@Andrea)
 - Targets 
 - What do we use to explore (prior geologic knowledge) 
 which then ties in to "how"
 
 ## How we explore
 ### Exploratory well drilling (@Mahmoud)
- Image of core logs (Bedretto core logs)
- Paragraph of different type of well data 
 ### Geophysics (@Hagen)
- Make analog to medical x-rays
- Talk about acquisition (include pictures)
PICTURES: MRT/CT scanner / Acquisition picture?

In geothermal exploration, our targets are usually located kilometres underground. Thus, direct exploration, as drilling exploratory wells, come with a high cost and only give good information in the vicinity of the borehole. This makes techniques that can image the underground from the surface highly attractive.

Techniques for this application have been used for a long time, for example in medical imaging. For getting an image of the internal structure of the body without cutting it open, we use physical phenomena, like electro-magnetic waves, acoustical waves, or magnetic fields, to study the reaction of the body to these processes. The physical response of the body itself then gives us information about the internal structure. When getting an x-ray to check for broken bones, we send highly energetic radiation in form of electro-magnetic waves through the body part, which we want to examine. On the other side of the x-ray emitter, a receptor catches the amount of radiation, that has not been absorbed by the body. Since bones absorb a high amount of the radiation, whereas tissue does not, we can locate bones inside the body. Another technique from medical imaging, that is close to the seismic technique used in geothermal exploration, is ultrasound imaging. In ultrasound, we use very small compressions of air, to create an acoustic wave that travels through the body. When the wave hits an obstacle in the tissue, parts of the wave are reflected and are picked up by a receiver. Measuring the time, the wave needs to travel to the obstacle and back and knowing the velocity of the wave in the tissue, we can again locate the obstacle in the body.

Medical applications nowadays allow us to get a very detailed picture of the body from the outside. This is also due to the fact, that we can place sources and receivers for our medical imager in all positions around the body. A prime example for this, are CT and MRT scanners. When imaging the underground, we don’t have this luxurious setting. In geothermal exploration, we usually have way to scarce data, to reconstruct every detail of the underground from measurements. By using very involved processing techniques, we can nevertheless get a very good image of the key features, like big faults in the reservoir. Imaging these faults from the surface allows us to locate fruitful targets to drill into.

 #### Seismic (@Hagen)
PICTURES: Vibrotruck? / Geophones /  GIF with wavefield data
- Explain the method and make a gif with wave propagation 

One of the most important methods of imaging the earth are seismic waves. Seismic waves are waves of ground motion, that travel through the earth. Just like in ultrasound, these waves get reflected and refracted at obstacles and boundaries and carry lots of information about the underground structure. The field, that studies seismic waves, is called seismology and has traditionally investigated earthquakes, to understand the science behind earthquakes, learn about the structure of the earth and subsequently protect humankind from natural disasters.

In exploration geophysics, we use the very same phenomena, to image a small, chosen part of the underground, to understand its structure. Since we cannot have earthquakes as a source of seismic waves at the spot, where we want to examine a geothermal site, we must generate seismic waves ourselves. For this, geophysicists use a variety of sources. For shallow experiments, a hammer with a metal plate is enough to generate a wave, that travels tens of meters. If you need the waves to travel deeper into the earth more energy is needed. Therefore, we either use explosives of vibration trucks to create stronger waves. To record the seismic waves, one uses so called geophones instead of seismometers. These consist of a metal pin, that gets firmly inserted into the ground. Attached to the metal pin is an accelerometer, that picks up the ground movement. For a seismic survey, a handful of geophones is laid out on the surface about the reservoir, that we want to image. After installing all the geophones, the sources get placed at different positions at the geothermal site, and at each site, an experiment is conducted. After all experiments at the source locations have been conducted, all the recorded data is collected and passed to a geophysicist for analysis. By analysing all the reflections picked up at the geophones, a detailed image of the underground can be produced.


 #### Multi-physics (EM, gravity, magnetics) (@Andrea)
 - Explain the method and make a gif with wave propagation 
 - Add gravity circle interactive thingy
 
## Modelling
 ### Geologic model (@Andrea)
 - Look for gempy model of utah forge existing site (granite wih some sedimentary layers on top)
 ### Inversion (@Hagen and Mahmoud)
- Forward and backward simulation (seismogram and gempy model connected with loopy thingy), desmos app for gradient descent
- Resulting model that is given to reservoir modelers (production link)

When investigating a geothermal site, we usually already have a rough idea about the subsurface from a geological model. However, there is often major differences, between our first geological model and reality. By the means of our geophysical survey, we aim to find a model of the underground, such that it matches our recorded data. To verify, that our model is a good fit, we need to be able to simulate our geophysical technique using a computer. This is commonly referred to as forward modelling and would mean to calculate the propagation of seismic waves in the case of a seismic survey. By simulating the wave propagation with respect to our first geological model, we can see, if our recorded data is already close to the one predicted by the simulation. We then try to find model variables, such that the misfit between simulated and recorded data is close to zero.

When trying to minimise an analytic function, we would usually try to find the roots of the derivative. This gives us the model parameters, where the error between recorded and simulated data is minimal. Since this calculation is way too complex for geophysical techniques, we must use a computer the calculate the derivative. This also means, we don’t get an analytic function for the derivative to find the roots of. Nevertheless, the derivative tells us, how to update the model, such that we reduce the error, by following along into the direction of descent. A little animation for this procedure can be found below. This procedure is commonly called inverse modelling. By repeating the process of calculating the derivative and following along into the direction of descent, one approaches the minimum. This yields a model, that explains our underground structure as good as possible. Once we are done, we hand over our best underground model to the reservoir engineers, to plan the layout of the geothermal power plant.


```{code-cell}
import jp_proxy_widget
src = "https://www.desmos.com/api/v1.7/calculator.js?apiKey=dcb31709b452b1cf9dc26972add0fda6"
graphUrl = "https://www.desmos.com/calculator/qn5qqc4wtc?lang=de"

widget = jp_proxy_widget.JSProxyWidget()
widget.load_js_files([src])
widget.js_init(
    """
    element.width(950).height(1000);
    element.calculator = Desmos.Calculator(element[0]);
    $.getJSON("https://www.desmos.com/calculator/qn5qqc4wtc").done(data => element.calculator.setState(data.state));
    """
)
widget
```