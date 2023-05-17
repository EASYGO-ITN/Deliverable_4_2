# Geothermal Energy Utilisation

## Introduction @Tristan
From the geothermal reservoir we can produce hot fluids carrying plenty of thermal energy. This thermal energy can be
used to heat homes, offices and even greenhouses, which is particularly attractive in cold climates, where heating 
represents a large portion of the total energy consumption.

Where there is no demand for heating, for example in hot climates or during the summer months in cold climates, or
where there is no consumer in the vicintiy of the geothermal reservoir, the thermal energy can also be converted to
other forms of energy such as electricity. This can be transported more easily over long distances to the consumers.

## Role of Geothermal Energy @Lorenzo

* depends where you are
* Iceland is driven by geothermal but in a unique position
* multipurpose tool - Munich area 

## Direct Use @Wen
The versatile direct utilisations of geothermal fluids with a temperature between 10 &deg;C - 150 &deg;C {cite}`anderson1979direct` has been ducomented for over 2000 years {cite}`direct-2000`. By the end of 2019, the total annual energy consumption from direct geothermal use is 283,580 GW h worldwide, reported in 88 countries and/or regions {cite}`lund2021direct`.The figure [data from {cite}`lund2021direct`] below shows main categories of direct utilisations of geothermal energy, dominated by heat pumps, bathing & swimming, and space heating. 

![Direct Utilisation](../GeothermalEnergy/Utilisation_pictures/Direct_utilisation.png)

### Geothermal Heat Pumps

So far, geothermal heat pumps (GHPs), also called ground-source heat pumps, have been the most popular way to directly utilise geo-fluids since its first use in 1850s in Austria {cite}`heatflux1`.  GHPs take advantages of the fact that a few feet below Earth's surface, the temperatue of the ground remains relatively constant, ranging from 7 &deg;C - 25 &deg;C {cite}`DOE:2023`. In the winter, the ground is warmer than the air above it while, in the summer, colder. GHPs then acts like a refrigerator, transferring heat through geo-fluids for building heating, ventilation and air conditioning {cite}`heatflux1`.

### Space Heating
Space heating, including individual space heating and district heating, dates back from 14th century when inhabitants of French village, Chaudes-Aigues Cnatal, utilised geothermal heat via a district heating networks that is still in use today {cite}`stanford`. Wells or multiple wells, consisting of producer and injector, are used to circulate geo-fluids with a temperature ranging from 60 &deg;C - 90 &deg;C {cite}`spaceheating`. If high enough temperature can be reached at a depth of 20 m - 200 m,, downhole exchangers can also be used. The leading countries in space heating are China, Iceland and Turkey, with a worldwide installed capacity reaching 12768 MWt by the end of 2019 {cite}`lund2021direct`.

### Bathing & Swimming

### Greenhouse Heating

### Industrial Use

### Aquacultural Pond Heating

### Agricultural Drying

### Cooling/Snow Melting

### Other


[//]: # (## Energy Conversion @Tristan
Converting from one form of energy to another is always associated with losses. The most familiar type of such losses in our everyday life are frictional losses. For example an electric car converts electric potential energy into kinetic energy, but the friction between the wheels and the road surface eventually brings the vehicle to a stand still once the car's battery is empty. These kind of frictional losses are broadly described as mechanical losses.)

Besides the aforementioned mechanical losses, conversion of thermal energy into more useful forms of energy like  mechanical energy (in turn this can easily be converted into rotational and then electrical potential energy via use of a turbine and generator). This is because the conversion is an irreversible process.

A process is reversible if it takes but a small nudge to reverse the process, however when it take a significant effort to reverse a process it is considered irreversible. Cooking is a great example of irreversible processes; it is simple enough to fry some fish, but is it significantly more difficult to unfry the fish and return it to its original state.

There are a number of processes for converting thermal energy to mechanical energy, these are often referred to as heat engines or power cycles.

### Carnot Cycle

Definitions:
A thermal reservoir is a body at a constant temperature. No adding of thermal energy will change its temperature. For example, adding a pot of boiling water to a lake will not measurably change the lake's average temperature.

The Carnot Cycle converts the heat flow between two differently tempered thermal reservoirs into work (mechanical energy). The Carnot Cycle is the simplest, most efficient, but merely theoretical heat engine.

0. **The initial state**
    
    Piston chamber is placed between two thermal reservoirs, one hot and one cold, the walls of the piston chamber currently do not permit transfer of mass or heat but can one at a time opened to heat transfer to/from one of the reservoirs. Piston chamber is filled with a fluid, which is of the same temperature as the hot reservoir, T<sub>Hot</sub>. The pressure-volume and temperature-entropy diagrams show the initial state of the fluid.
    ![Stage 0](Utilisation_pictures/Stage0.svg)

1. **Isothermal Heat Addition** 

    The piston chamber wall in contact with the hot reservoir is opened to allow heat transfer between the hot reservoir and the piston chamber. The piston is then slowly raised, increasing the volume of chamber. Meanwhile, the temperature of the cell remains at T<sub>Hot</sub> as heat moves from the hot reservoir into the cell. The arrows in the pressure-volume and temperature-entropy diagrams illustrate the "journey" of the fluid from the initial to the current state.
    ![Stage 1](Utilisation_pictures/Stage1.svg)

    The heat added to the fluid is given by:
    $$ Q_{in} = T_{Hot} * (S_2 - S_1) $$

2. **Isentropic Expansion**

    The piston chamber is once again isolated from the two reservoirs. The piston is then moved upwards, increasing the volume of the chamber until the fluid cools to the temperature of the cold reservoir, T<sub>Cold</sub>.
    ![Stage 2](Utilisation_pictures/Stage2.svg)

3. **Isothermal Heat Removal**
    
    The previous processes are now reversed. The piston chamber wall in contact with the cold reservoir is opened to allow heat transfer between the cold and piston chamber. The piston is then slowly pushed down, reducing the volume of the chamber. The temperature in the cell remains at T<sub>Cold</sub>, as the heat moves from the chamber into the cold reservoir.
    ![Stage 3](Utilisation_pictures/Stage3.svg)

    The heat removed from the fluid is given by:
    $$Q_{out} = T_{Cold} * (S_2 - S_1)$$

4. **Isoentropic Compression**

    The piston chamber is once again isolated from the two reservoirs. The piston is then moved downwards, reducing the volume of the chamber until the fluid heats up to the temperature of the hot reservoir, T<sub>Hot</sub>. This returns the Carnot engine and the fluid in the piston chamber to their initial state.
    ![Stage 4](Utilisation_pictures/Stage4.svg)

5. Repeat from 1.

    ![GIF](Utilisation_pictures/CarnotAnimation.gif)

As the above is a cyclic process, the fluid returns to its initial state and no energy can have accumulated within the system. Therefore, the difference in heat added and removed has been converted into work, i.e. expanding or compressing the fluid in the piston chamber.

$$W_{Net} = Q_{in} - Q_{out}$$

The conversion efficiency is thus

$$\eta = \frac{W_{net}}{Q_{in}} = \frac{(Q_{in} - Q_{out})}{Q_{in}} = 1 - \frac{T_{Cold}}{T_{Hot}}$$

Unfortunately, it is difficult to translate such a cyclic process into the real world. A pure, single component
fluid like water could be used to realise Stage 1 and Stage 3 (i.e. isothermal heat addition and isothermal heat
removal), since pure fluids undergo constant temperature phase changes. For example, adding heat to a saturated liquid
will cause it to vapourise, but its temperature remains constant. Similarly, removing heat from a vapour will cause it
to condense at a constant temperature

However, Stage 2 and Stage 4,are more difficult to realise. This is because, while specific equipment exists for
compressing a liquid (i.e. a pump) or a vapour (i.e. a compressor), these struggle with two-phase fluids (i.e. liquid
and vapour). For example, excessive vapour in a pump can lead to cavitation, which damages the pump impeller; likewise
excessive in a compressor can damage the blades.
![Real Carnot Cycle](Utilisation_pictures/RealCarnotCycle.svg)

## Power Plants
Geothermal power plants convert the thermal energy extracted from the sub-surface into electricity. The working principle behind converting the thermal energy to mechanical work (i.e. rotational energy) is not too different from other power plants types like coal-fired or nuclear plants.

### Working Principle: The Rankine Cycle
The Rankine Cyle is a heat engine, that converts thermal energy into mechanical work, which in turn can be used for driving a turbine. It is based on the theoretical Carnot Cycle, with adaptations to make the expansion and compression stages easier to implement with existing turbomachinery (i.e. turbines, pumps and compressors, see below).

![Rankine Cycle](Utilisation_pictures/RankineCycle.svg)

* **Initial State**: The cycle working fluid (e.g. water) is at a low pressure and saturated liquid state
*  **Stage 1**: A pump is used to compress and pressurise the working fluid to a high pressure
* **Stage 2**: Heat is added to the fluid at constant pressure, raising its temperature until it reaches the boiling point. From hereon, heat addition results in subsequent vaporisation of the working fluid until it is fully vapourised.
* **Stage 3**: The high pressure vapour is expanded in a turbine, which converts the fluid's thermal energy into rotational energy, and in turn drives a generator to produce electricity.
* **Stage 4**: The expanded low pressure vapour is cooled at constant pressure until it reaches its condensation point. From hereon, removal of heat results of subsequent condensation of the working fluid vapour until it is fully liquefied. This returns the fluid to its initial state and closes the cycle. 
* Repeat from **Stage 1**

Depending on the temperature and physical state (i.e. vapour, liquid or a mixture of the two) of the geofluid arriving at surface, different types of geothermal power plants are:

### Dry Steam @Tristan
Dry Steam power plants operate on the hottest geothermal resources, where the geofluid arrives at the surface as steam
at temperatures as high as 250 &deg;C.

![Dry Steam](Utilisation_pictures/DrySteamPlant.svg)

* **Initial State**: High-pressure saturated steam arrives at the power plant
*  **Stage 1**: The hot vapour is expanded in a turbine
* **Stage 2**: The low-pressure vapour is condensed (e.g. using a cooling tower)
* **Stage 3**: The low-pressure liquid is re-pressurised using a pump and re-injected into the reservoir

There are some peculiarities compared to the Rankine Cycle we discussed earlier:
* The stages do not close the loop - this is because the heating and re-boiling actually takes place in the geothermal reservoir and this not usually included in the diagram
* The cooling tower "loses" a considerable amount of geofluid - the typical white clouds over a power station 

This is also the reason why they are typically referred as being ***open-loop*** 

### Flash @Tristan
Flash power plants operate on geothermal resources, where the geofluid arrives at surface as a steam-water mixture.

![Flash Plant](Utilisation_pictures/FlashPlant.svg)

* **Initial State**: Hot high-pressure two-phase geofluid arrives at the power plant 
*  **Stage 1**: The geofluid is "flashed" (i.e. reducing its pressure). This causes the fluid to partition into a liquid and vapour phase, see dashed lines.
*  **Stage 2**: The hot and high-pressure vapour is exanded in a turbine
*  **Stage 3**: The low-pressure vapour is condensed (e.g. using a Cooling Tower)
*  **Stage 4**: The low pressure liquid is re-pressurised using a pump and re-injected into the reservoir alongside the liquid obtained from Stage 1

`````{admonition} Hint
:class: tip
Flashing the geofluid more, can produce more steam (good) but comes at the cost of lower specific power generated by the turbine (bad) so there is a trade-off.
`````

There are some peculiarities compared to the Rankine Cycle we discussed earlier:
* The stages do not close the loop - this is because the heating and re-boiling actually takes place in the geothermal reservoir and this not usually included in the diagram
* The cooling tower "loses" a considerable amount of geofluid - the typical white clouds over a power station 

### Binary @Lorenzo

Historically speaking, the first geothermal resources that were exploited are those providing brine at high temperatures, perhaps even in vapor state, as it is the case of Larderello in Italy. On the contrary, extracting energy from brines at lower temperatures is more challenging and the classical dry steam or flash power plant might not be profitable. In this case, the usual approach to first use the geothermal brine to heat another more suitable fluid, and have this secondary fluid undergo a rankine cycle. The cooled down brine is subsequently reinjected into the ground. This is the concept of Binary Geothermal Power Plant. 

[//]: # (@Lorenzo maybe we can put in a mention about my research here, since I am actually trying to revert that trend somewhat and to use ORCs for two phase sources. Something like:)
<div class="alert alert-block alert-info">
<b>By the way:</b> One of our researchers is working on widening the application range of binary ORC power plants to two-phase sources like those commonly associated with Flash or Dry Steam plants. Find out more <a href="https://easygo-itn.eu/lorenzo-galieti/">here</a> or <a href="https://www.researchgate.net/profile/Tristan-Merbecks">here</a>!</div>

The standard rankine cycle for geothermal applications is called Organic Rankine Cycle (ORC): this is because the fluid flowing inside the machinery (pump, heat exchangers, turbine) is usually an hydrocarbon, whose properties are selected to maximize the efficiency of the power plant. In particular, the boiling point is much lower than that of compressed water, allowing the generation of the vapor that drives the turbine without any need of a flashing procedure. 

![Binary ORC](Utilisation_pictures/OrganicRankineCycle.svg)

* **Initial State**: Hot geofluid arrives at the power plant 
*  **Stage 1**: The cold low-pressure cycle working fluid is pressurised using a pump.
*  **Stage 2**: The hot geofluid heats and evaporates the cycle working fluid. The now cold geofluid is re-injected into the reservoir
*  **Stage 3**: The hot and high-pressure vapour is exanded in a turbine.
*  **Stage 4**: The low-pressure vapour is condensed
* Repeat from **Stage 1**

[//]: # (@Lorenzo maybe we should also talk about the following a bit more...)
* advantages of ORCs
  * choice of WF - here we could then mention that you are doing research into this...
  <div class="alert alert-block alert-info">
  <b>By the way:</b> One of our researchers is investigating whether mixtures of organic fluids could improve the performance of binary ORCs powe plants. Find out more <a href="https://easygo-itn.eu/tristan-merbecks/">here</a> or <a href="https://www.researchgate.net/profile/Lorenzo-Galieti">here</a>!</div>
  * turbine size, cost, eff, durability
  * closed loop - reduced contact with geofluid
* disadvantages

### Efficiency

* First Law 
* Second Law

## Power Plant Equipment @Lorenzo
All the geothermal power plants convert the thermal energy into electricity by using several different machinery. In particular, the most recurring component is the turbine: its scope is to extract the energy of the vapor and convert it into mechanical energy.

A typical axial turbine for binary geothermal power plants is shown below: at its simplest, it is composed of a shaft driven by a series of wing-like elements, called blades. The blades are radially disposed around the shaft. By blowing the hot vapor on the blades, each one of them will generate some lift, and their combination will induce the rotation of the turbine.

![Turboden Axial Turbine](../GeothermalEnergy/Utilisation_pictures/axialturbine.png)

The heat exchangers come in different models and are responsible for several different thermodynamic transformations. In the binary power plants, we can usually distinguish between two different types: the shell and tube heat exchangers and the fin and tube heat exchangers .

The first ones can be used when there is little fluid in gaseous phase contributing to the heat exchange process: their typical application is in the evaporator of the binary power plant, which is responsible of transferring heat from the geothermal brine to the working fluid undergoing the rankine cycle. here, usually two different shell and tube heat exchangers are used: one to preheat the fluid and bring it on the verge of evaporation, and the other to promote the evaporation and eventually provide vapor to the turbine. Despite being of the same typology, they work in quite a different way.

### Heat Exchanger

### Pump

### Turbine

### Generator

### Valve/Orifice
