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

    In geothermal exploration, our targets are usually located kilometres underground. Thus, direct exploration, as drilling exploratory wells, come with a high cost and only give good information in the vicinity of the borehole. This makes techniques that are able to image the underground from the surface highly attractive. Techniques similar to the ones used in geothermal exploration have been used for a long time, for example in medical imaging. For getting an image of the internal structure of the body without cutting it open, we use physical phenomena, like electro-magnetic waves, acoustical waves, or magnetic fields, to study the reaction of the body to these processes. The physical response of the body itself then gives us information about the internal structure.

    When getting an x-ray to check for broken bones, we send highly energetic radiation in form of electro-magnetic waves through the body part, which we want to examine. On the other side of the x-ray emitter, an receptor catches the amount of radiation, that has not been absorbed by the body. Since bones absorb a high amount of the radiation, whereas tissues does not, we can locate bones inside the body. Another technique, that is close to the seismic technique used in geothermal exploration and explained in the next paragraph, is ultrasound. In ultrasound, we use very small compressions of air, to create an acoustic wave that travels through the body. When the wave hits an obstacle in the tissue, parts of the wave are reflected and are picked up by a receiver. Measuring the time, the wave needs to travel to the obstacle and back and knowing the velocity of the wave in the tissue, we can again locate the obstacle in the body.

    Medical applications nowadays allow us to get a very detailed picture of the body from the outside. This is also due to the fact, that we can place sources and receivers for our medical imager in all positions around the body. A prime example for this, are CT and MRT scanners. When imaging the underground, we don’t have this luxurious setting. Therefore, we have to work with limited information, that we get from reflections or have to apply involved processing techniques, to get an adequate image out of the little data.


 #### Seismic (@Hagen)
    PICTURES: Vibrotruck? / Geophones /  GIF with wavefield data
    - Explain the method and make a gif with wave propagation 

    One of the most important methods used for imaging the earth, is by seismic waves. Seismic waves are basically waves of ground motion, that travel through the earth. Just like in ultrasound, these waves get reflected and refracted at obstacles and boundaries and give us a lot of information about the underground structure. The field, that studies seismic waves, is called seismology and has traditionally investigated earthquakes. To study earthquakes is not only important, to understand the processes of earthquakes, as well as warn and protect people living in exposed regions, but give us also the possibility to study the interior of the earth, as the earthquake are sending waves through the earth. Just like in ultrasound imaging, these waves get picked up at seismometers all around the world, allowing us to image the interior of the earth.

    When wanting to deliberately image the underground at a potential geothermal site, we must generate seismic waves ourselves. Seismic waves for exploration can use a variety of sources. For shallow experiments, you can use a hammer with a metal plate to generate a wave. If you need the waves to travel deeper into the earth more energy is needed, and we need to use explosive of vibration trucks to create strong waves. To record the seismic waves, so called geophones are used. These consist of a metal pin, that gets firmly put into the ground, and an accelerometer, that picks up the ground movement. After installing all the geophones, the sources get placed at different positions at the geothermal site, and at each site, an experiment is conducted. After all experiments at the source locations have been conducted, all the recorded data is collected and passed to a geophysicist for analysis. By analysing all the reflections picked up at the geophones, a detailed image of the underground can be produced.

 #### Multi-physics (EM, gravity, magnetics) (@Andrea)
 - Explain the method and make a gif with wave propagation 
 - Add gravity circle interactive thingy
 
## Modelling
 ### Geologic model (@Andrea)
 - Look for gempy model of utah forge existing site (granite wih some sedimentary layers on top)
 ### Inversion (@Hagen and Mahmoud)
- Forward and backward simulation (seismogram and gempy model connected with loopy thingy), desmos app for gradient descent
- Resulting model that is given to reservoir modelers (production link)

    When imaging a geothermal site, we usually start with a rough guess from a geological model, and try to find a model of the underground, such that it matches our recorded data. To verify, that our model is a good fit, we need to be able to simulate our geophysical technique using a computer. This is commonly referred to as forward modelling. To minimise the misfit between our recorded data and the predicted set of data, we then have to calculate the derivative of the function calculating the misfit. When having an analytic function, we would usually try to find the roots of the derivative, which would gives us the places, where the error between recorded and predicted data is minimal. Since this calculation is way to complex, we have to use a computer the calculate the derivative and we dont get a function for the derivative, to find the roots of. Nevertheless, the derivative tells us, how to update the model, such that we reduce the error, by following along into the direction of descent. This procedure is commonly called inverse modelling. By repeating the process of calculating the derivative and following along into the direction of descent, one approaches the minimum, giving us the model, that explains our underground structure best. Once we are done, we hand over our best underground model to the reservoir engineers, to plan the layout of the geothermal power plant.

```{code-cell}
print(2 + 2)
```