# Issues and Safety of Geothermal Operations

<span style="font-size:0.6em;">Last edited: 01 Sep 2023</span> \
<span style="font-size:0.6em;">Author(s): </span>&ensp; <span style="font-size:0.6em;">Anna Kottsova (ETH Zurich, Switzerland - TU Delft, Netherlands)</span> \
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;<span style="font-size:0.6em;">David Naranjo (TU Delft, Netherlands - RWTH Aachen, Germany)</span> \
&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;<span style="font-size:0.6em;">Wen Luo (Josselin Ouf, RWTH Aachen - TU Delft, Netherlands)</span>

While geothermal energy offers many benefits as a renewable and sustainable energy source, there are some potential risks and drawbacks associated with its use. During the production of geothermal fluids, the change in pressure and temperature is unavoidable. It, in turn, results in a change in fluid composition and properties. Depending on the initial properties of the fluid, these changes can significantly affect the operation of the geothermal system and should, therefore, be carefully monitored. In the following section, we explain the environmental and operational risks/issues happening at different stages of production and the consequent injection of geothermal fluids.

`````{admonition} Recap on how geothermal energy works
:class: tip
Geothermal power plants harness the heat stored beneath the Earth's surface to generate electricity. This heat comes from hot water or steam found in underground reservoirs. To access this heat, operators drill (deep) wells into the Earth to extract the hot fluids. After the heat is extracted and used to generate electricity, the cooled fluids are often reinjected into the reservoir to maintain pressure and sustain the resource.
![Example image](../GeothermalEnergy/issues_pictures/dapwell.jpg)
Figure 1: Schematic representation of the DAP-well [click here for more details](https://www.tudelft.nl/en/delft-outlook/articles/campus-switching-to-geothermal-energy).

`````

## Environmental Impacts of Geothermal Operations

Geothermal energy is often considered an environmentally friendly energy source due to its low greenhouse gas emissions and renewability. However, it is essential to consider the potential environmental impacts associated with geothermal operations to ensure sustainable development and minimize adverse effects on the surrounding ecosystem. This section discusses some critical environmental concerns related to geothermal energy production, including greenhouse gas emissions, water pollution, and induced seismicity.

### Greenhouse Gas Emissions
Let's begin by examining a recognized environmental concern related to geothermal energy production: greenhouse gas emissions. Geothermal power plants generally emit fewer greenhouse gases than conventional fossil fuel-based power plants. However, they do release greenhouse gases, such as carbon dioxide (CO<sub>2</sub>) and methane (CH<sub>4</sub>), during the extraction of geothermal fluids. Geothermal plants emit about 5% of the carbon dioxide, 1% of the sulfur dioxide, and less than 1% of the nitrous oxide emitted by a coal-fired plant of equal size, and certain types of geothermal plants produce near-zero emissions [(Holm et al., 2012)](https://geothermal.org/sites/default/files/2021-02/Geothermal_Greenhouse_Emissions_2012_0.pdf).
While the volume of these emissions is relatively low compared to fossil fuel-based plants, they still pose a considerable concern. For this reason, it is important to monitor and minimize these emissions through the implementation of advanced technologies and best practices (see section [Processes during reinjection](section:reinjection)).

`````{admonition} Are CO<sub>2</sub> emissions from solar energy lower than the ones from geothermal?
:class: tip

According to a study by [Chandrasekharam et al., (2020)](https://link.springer.com/article/10.1007/s40948-019-00135-y), geothermal energy exhibits lower greenhouse gas emissions when compared to solar PV (photovoltaic). This is because solar PV energy, which converts sunlight into electricity, involves a substantial amount of energy and materials during the manufacturing process of solar cells, resulting in higher emissions throughout the cells' lifecycle. As a result, geothermal energy stands out as a more environmentally friendly option with lower CO<sub>2</sub> emissions. 

Although this might be the case for most geothermal operations, it is important to note that some regions may have higher emissions. For example, Turkish geothermal plants have shown CO<sub>2</sub> emission factors significantly higher than the reported global average [(see Aksoy et al., 2015)](https://link.springer.com/article/10.1134/S0040601516050098).
`````

### Water Pollution
Apart from the atmospheric considerations, geothermal operations may pose potential challenges to underground water resources. To prevent water pollution, it is essential to establish appropriate fluid management practices, such as treating and reinjecting geothermal fluids back into the reservoir or disposing of them in a safe and regulated manner. The challenge lies in the nature of the geothermal fluids themselves. Geothermal fluids can contain dissolved minerals and gases that may pose a risk to water quality if not properly managed. Some of these substances can be toxic and harmful to the environment. 

### Induced seismicity

While the impact on air and water quality are significant, another environmental concern of geothermal energy production is induced seismicity. This kind of seismicity is caused by stress changes resulting from anthropogenic activities. In geothermal systems, pressure changes can occur due to the production and (re)injection of geothermal fluid {cite}`buijze_van2019`. This can lead to the creation of new fractures or the reactivation of existing faults (if the fluids migrate towards these).

Induced seismicity associated with geothermal operations is generally minor in scale and often goes unnoticed by people living nearby. This shouldn't come as a surprise, as successively smaller earthquakes are more common, as shown by the [Gutenber-Richter frequency-magnitude distribution relation](https://doi.org/10.1016/B978-0-12-814580-7.00014-9). 

Despite this general trend of minor seismic activity, there are instances where geothermal operations have induced earthquakes strong enough to cause damaging ground motions. These potentially damaging earthquakes cannot be confidently predicted before the start of operations {cite}`Atkinson2020`. This was the case in the destructive 2017 Pohang Earthquake in South Korea.

In the context of geothermal operations, induced [light to moderate earthquakes](https://www.usgs.gov/media/images/eq-magnitude-energy-release-and-shaking-intensity-5) are uncommon. For a moderate earthquake to be triggered, it must involve i) a source of stress perturbation, such as the injection of fluids, ii) a critically stressed fault that has enough surface to accommodate an earthquake that can be felt, and iii) a direct or indirect connection between both {cite}`Atkinson2020`. Therefore, understanding the underground geological structures and monitoring the local seismicity is critical to ensure the safety of geothermal operations. Additionally, it is essential to analyze the vulnerability of infrastructure nearby.

`````{admonition} Seismic hazard vs risk
:class: tip

Analyzing the potential danger posed by earthquakes is not a trivial task. It is important to distinguish between hazard and risk. Hazard relates to the intrinsic natural occurrence of earthquakes and the resulting ground motion, whereas risk is the danger the hazard poses to life and property {cite}`stein2009introduction`. It is often said that "earthquakes do not kill people, but buildings do". For this reason, it is critical to quantify the potential for an earthquake to occur at particular geological sites due to fluid injection and study the risk it may pose. 

If you would like to learn about the destructive geothermal-induced 2017 Pohang Earthquake, you can check out the following articles by [Shapiro et al., (2021)(https://www.nature.com/articles/s41467-021-26679-w) or [Grigoli et al., (2018)](https://www.science.org/doi/10.1126/science.aat2010).
`````

# Operational risks and safety measures

## Processes during production 

### Scaling
As we already said, pressure and temperature decrease as we extract geothermal fluid from the surface. This may lead to one of the major issues of geothermal operations - scaling. As temperature drops and gases exsolve from the fluid, solubility of the minerals initially contained in the fluid also drops. It is mainly controlled by the saturation index (SI), which is defined as the ratio of ion activity product (IAP) to the solubility product or equilibrium constant (K<sub>sp</sub>): $SI = \frac{IAP}{K_{sp}}$ {cite}`Deng2021`. When SI > 0, solution is considered over-saturated and the mineral can precipitate. What this means to us, is that there is a risk of scaling in the production tubings, heat exchanger and other surface facilities. Scaling leads to decreased tube diameter and, consequently, lower productivity. It can also promote corrosion of metal surfaces and compromise the whole system.

```{figure} ../GeothermalEnergy/issues_pictures/scaling.jpeg
---
width: 350px
align: center
---
Example of scaling in a production pipe from the geothermal museum in Larderello.
```

### Corrosion

One of the major reasons for corrosion is contact of the geothermal fluid with oxygen at the different stages of operation, which leads to oxidation of ions, iron in particular. As a result of this process, metal tubing as well as other surface equipment can be damaged and will require a workover, resulting in the stop of all geothermal operations. Additionally, products of corrosion in the form of small particles can migrate further with the fluid flow. It has been observed that the concentration of oxidized ions increases as the fluid passes from the production to the injection site {cite}`Brehme2018`, showing that corrosion can occur at all stages of the system. Furthermore, if the particles are small enough to pass through the filters, they could migrate into the reservoir and cause pore blockage and decline of injectivity. 

### Control and prevention

Various methods to control scaling and corrosion exist and are constantly being developed. One of the most common is the usage of chemicals - scaling or corrosion inhibitors to prevent or, at least, slow down these processes. Additionally, to decrease scaling, increased pressure at the surface can be applied to keep gas in the dissolved state. Multiple filter systems are also installed at various stages of operation to prevent the products of scaling and corrosion from migrating further and clogging the reservoir.
Another big topic, receiving attention now is the development of chemical models of geothermal brine. This will allow the operating companies to accurately predict the system's behavior, select suitable operational parameters and choose treatment methods if needed.

(section:reinjection)=
## Processes during reinjection

Reinjection of the produced geothermal fluid back into the reservoir is a common practice, widely applied at fields around the world {cite}`Kaya2011, Stefansson1997`. There is a number of reasons for using this technology {cite}`Axelsson2012, Kaya2011`:

* Produced water disposal due to environmental reasons and regulations;
* Recharge of the reservoir/aquifer;
* Pressure compensation to account for fluid extraction and to prevent subsidence;
* Enhancement of thermal extraction from over- and underlying formations.

So, geothermal fluid reinjection has clear economic and technical advantages and is a key, and sometimes mandatory, process in a geothermal project. Therefore, its efficiency is very important and reinjection is constantly monitored to prevent possible issues. Various processes could influence the success of this process during operations. Disturbances in temperature, pressure, stresses and compositions in geothermal reservoirs as a result of cold brine reinjection could trigger complex coupled processes that influence injectivity. In the following sections we discuss these processes individually in more detail.

### Cooling of the reservoir

As we said before, the water injected into the geothermal reservoir has a lower temperature than that of the reservoir itself. As a result, heat flows from the rock towards the fluid, causing the temperature of the production well water to be higher than that of the injected water. However, in a closed geothermal reservoir, the extracted heat cannot be replenished, and the total amount of heat available for extraction is finite. This can be likened to the depletion of a water tank as water is pumped out; similarly, the extraction of heat leads to a reduction in the total amount of heat available, which in turn affects the reservoir's temperature.
The reduction in temperature caused by the pumping of water has a direct impact on the productivity of the reservoir. As the temperature decreases, the economic viability of further exploitation also declines. Additionally, the temperature changes can trigger faults located in the cooling regime of the reservoir.

### Injectivity decline

One key issue that determines the success of reinjection, and thus of the whole geothermal project, is to achieve and maintain injectivity at an acceptable level. In many geothermal fields where reinjection has been implemented, continuous decreases in injectivity have been recorded {cite}`Brehme2019, Birner2015`. In other words, over time we are able to inject less and less fluid because of some blockages. In some extreme cases, poor injectivity performance has led to the shutdown of the whole geothermal project, such as the Klaipeda geothermal plant in Lithuania.

Based on the primary mechanisms, the clogging processes can be divided into three groups: 
* physical processes, related to the migration of particles;
* chemical processes, caused by chemical reactions;
* biological processes as a result of bacterial activity. 

```{figure} ../GeothermalEnergy/issues_pictures/doublet_schematic.jpg
---
width: 500px
align: center
---
Clogging processes at different stages of geothermal operations {cite}`Luo2023`.
```

As you can see from the schematic, sources of clogging occur all the way along the fluid path. 
- From the start of production fluid can carry small particles, produced, for example, from poorly-consolidated sandstones. 
- As the fluid moves up, its pressure and temperature decreases, minerals saturation decreases and scaling can occur.
- After heat extraction, despite complex filtration systems, some fines are still left in the fluid volume and can migrate further into the reservoir. Corrosion also can occur at this stage if the system is not isolated.
- When the cold fluid is injected back into the reservoir, multiple processes can happen:
  - Not-filtered fines can block the pores;
  - Changes in the chemical composition can result in dissolution or precipitation of minerals in the pore space;
  - Changes in fluid salinity or pH can initiate migration of internal fines or swelling of clays;
  - Contamination of water as well as change of the temperature can promote bacterial activity, resulting in production of bio-polymers and pore space reduction.

So, you can see that at the end of this chain multiple processes can result in the reduction of rock porosity and permeability, which can seriously affect the whole process. There are various remediation methods for each of the described issues, however, prediction of these processes is crucial for successful prevention.

<div class="alert alert-block alert-info">
<b>By the way:</b> One of our researchers is working on this topic. Anna Kottsova is studying chemical precipitation in porous media and its effect on rock permeability using laboratory experiments. <a href="https://easygo-itn.eu/anna-kottsova/">Learn more about her work</a>
</div>


### Thermal fracturing at the well and hydro-shearing


The injection of fluids into a reservoir can cause significant changes in temperature, which may lead to the opening or reopening of fractures. This thermal crack initiation and propagation can alter the injectivity and permeability of the well, ultimately affecting the economic viability of the reservoir. Additionally, the energy released by these thermal cracks may result in induced seismicity. It is important to note that excessive permeability can cause the reservoir to cool too quickly, which can negatively impact its long-term profitability. On the other hand, insufficient permeability can result in poor fluid exchange, leading to suboptimal economic performance. In crystalline reservoirs, such as granite, fluid flow occurs primarily through fractures. To improve fracture permeability, a stimulation technique involving the injection of water at high pressure is employed. This process referred as hydro-shearing causes the fracture to slide and dilate, thereby creating a larger flow channel and improving the flow and heat exchange in the reservoir.


```{figure} ../GeothermalEnergy/issues_pictures/hydroshearing.jpg
---
width: 800px
align: center
---
Figure 4: Difference between hydraulic fracturing (a) and hydraulic shearing (b) {cite}`gischig`.
```
<div class="alert alert-block alert-info">
<b>By the way:</b> One of our researchers is working on this topic. Josselin Ouf is conducting numerical modeling  on fault instability due to reservoir contraction and hydro-shearing stimulation. Learn more about his work <a href="https://easygo-itn.eu/josselin-ouf/">Learn more about his work</a> 
</div>
