
# Discover and Manage Farms

## Motivating scenario

A farm is separated to 4 land sections: The first two land sections grow crops of type wheat, and they are of square shape of length 1, characterised by their opposite corners at point coordinates [0,0],[1,1] and [1,0],[2,1] respectively. The other two land sections grow crops of type corn, and they are of square shape of length 1, characterised by their opposite corners at point coordinates [0,1],[1,2] and [1,1],[2,2] respectively.  

Each crop type has a required moisture level: Once the moisture level of crops falls under the required one, the crops should be irrigated.  The required moisture levels of wheat and corn are 120 and 80, respectively. 

The farm contains two tractors that can be controlled within the coordinates of the farm’s land sections: One tractor offers an action affordance for reading the current moisture level of the farms’ land sections, and one tractor offers an action affordance for irrigating the farm’s land sections.  

The tractors are operated by two autonomous agents: An agent that monitors the current moisture levels of land sections, and an agent that irrigates land sections.

<img src="docs/farm-matrix.PNG" width="400">

## Informal competency questions

| ID | Question in Natural Language                                                                      | Example                                                                                                                      |
|----|---------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| q1 | What are the tractors in farm X? | Tractors contained in farm `ex:farm`: `ex:tractor1`, `ex:tractor2`.
| q2 | What is the W3C WoT Thing Description of a tractor in farm X that offers an affordance for reading the moisture level of soil?| Thing Description of a tractor contained in farm `ex:farm`: [<https://raw.githubusercontent.com/Interactions-HSG/example-tds/was/tds/tractor1.ttl>](https://raw.githubusercontent.com/Interactions-HSG/example-tds/was/tds/tractor1.ttl).|
| q3 | What is the W3C WoT Thing Description of a tractor in farm X that offers an affordance for irrigating the soil? | Thing Description of a tractor contained in farm `ex:farm`: [<https://raw.githubusercontent.com/Interactions-HSG/example-tds/was/tds/tractor1.tt2>](https://raw.githubusercontent.com/Interactions-HSG/example-tds/was/tds/tractor2.ttl).|
| q4 | What are the land sections in farm X? |  Land sections of farm `ex:farm`: `ex:section1`, `ex:section2`, `ex:section3`, `ex:section4`|
| q5 | What are the coordinates X1, Y1, X2, Y2 that define land section X? | Coordinates of land section `ex:section1`: `0`, `0`, `1`, `1`, respectively.|
| q6 | What is the crop growing in land section X? |  Crop growing in land section `ex:section1`: `ex:crop1`.|
| q7 | What is the required moisture level of crop X based on its crop type? | Required moisture level of `ex:crop1`: 120.|

## Glossary of terms
- **Farm**: A plot of land devoted to the growing of crops.
- **Tractor**: An automotive vehicle that offers affordances to agents for managing a farm.
- **ReadSoilMoistureAffordance**: An affordance offerred by the environment to agents for reading the moisture level of soil.
- **IrrigateAffordance**: An affordance offerred by the environment to agents for irrigating the soil.
- **Coordinates**: A set of 4 coordinates [X1,Y1,X2,Y2] that define the opposite corners of a square section at points [X1,Y1] and [X2,Y2].
- **SoilMoisture**: Level of moisture in soil.
- **MoistureLevelRequirement**: Specific moisture level needed for a crop type to grow optimally.
- **LandSection** A specific area of a farm designated for growing a particular type of crop. Characterized by its shape, size, and the type of crop grown.
- **CropType** A classification for crops indicating the variety, such as wheat or corn. Each type has specific requirements, including moisture levels.
- **Crop**: A plant or plant product that is grown and harvested extensively for-profit or subsistence.
- **Wheat**: A type of crop known for its grain, used to make products like flour.
- **Corn**: A type of crop known for its edible kernels.
- **SquareShape**: A geometric shape characterized by four equal sides and four right angles. Defined by two opposite corner coordinates.
- **Agent**: An autonomous entity that performs actions on the farm, such as monitoring moisture levels or irrigating land sections.
- 
- *Complete the glossary for definiting terms required to model the motivating scenario of the domain. These terms will then be formally defined in your TBox.*
