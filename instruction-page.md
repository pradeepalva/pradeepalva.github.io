---
layout: default
---
[back](./)

[Research Project](./another-page.html)
[UDT GHG](./app-page.html)
[User feedback](./feedback-page.html)

## Instructions on how to use UDT-GHG Dashboard

* * *

### Instruction Video

<iframe width="1000" height="500" src="https://www.youtube.com/embed/EkGt_DRY8v0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### UDT-GHG Dashboard

![Dashboard](assets\images\dashboard.jpg)

* * *

## Methodology for building operational Greenhouse gas (GHG) emissions

* * *

### The operational GHG emissions (Og) of buildings (CO2e/kWh-carbon dioxide equivalent per kilowatt hour) are calculated using a linear equation:

![The operational GHG emissions (Og) of buildings (CO2e/kwh—carbon dioxide equivalent per kilowatt hour) are calculated using a linear equation](/assets/images/linear_equation.jpg)

Electricity demand (Del) in kWh (kilowatt-hours) by average values indicated in the national benchmarking reports or results from simulated energy demand model (CEA) or actual meter reading.

The electricity grid emission factor is the average amount of CO2 that each grid-connected power unit emits per unit of net electricity produced in the system (Energy Market Authority-EMA yearly Singapore energy statistics report provides emission factor for Singapore).

The Global Warming Potential (GWP) for each of seven major GHGs [carbon dioxide (CO2), methane (CH4), perfluorocarbons (PFCs), hydrofluorocarbons (HFCs), sulfur hexafluoride (SF6), nitrous oxide (N2O), and nitrogen trifluoride (NF3)], compares the contribution of a given mass of a GHG to that of CO2 in terms of global warming over a definite time frame (for instance, 100 years). The GWP values for the most common GHGs (CO2, CH4, N2O) can be found in the Intergovernmental Panel on Climate Change (IPCC) reports.

* * *

## Potential of Intervention Map - Public housing (HDB) priority of low carbon rejevenation of building systems

* * *

The Potential of Intervention (POI) map is created using Multiple-Criteria Decision Analysis ![(MCDA)](https://en.wikipedia.org/wiki/Multiple-criteria_decision_analysis). The POI map helps decision makers to prioritise low carbon rejuvenation of building systems in the public housing. A heat map is generated showing the buildings that need urgent rejuvenation based on parameters assigned. Parameters assigned for analysis are: 1. Building Age, 2. Greenhouse gas (GHG) emissions, 3. Replacement cycles of Lifts and 4. Lighting equipments and 5. Building wall painting cycle. These parameters have varied scales and hence normalisation (to a notionally common scale) using sigmoid function is applied in order to aggregate them. Before aggregating, each of parameter is converted to 0 to 1 value using ![(Sigmoid function)](https://en.wikipedia.org/wiki/Sigmoid_function), mid point (0.5) for each parameter is defined as per threshold beyond which needs an intervention from decision maker (see Figure below with Normalisation step).

### Normalisation of parameters of varied scale using sigmoid function:

![Normalisation of parameters of varied scale using sigmoid function](/assets/images/POI_1.jpg)

The result of aggregate potential of intervention with each parameter of same weightage assigned (1) (see Figure below with POI map). The dashboard gives users an option to change weightage of parameters based on thier priority and dashboard intuitively generates a POI map.

### Aggregate Potential of Intervention after normalisation:

![Aggregate Potential of Intervention after normalisation](/assets/images/POI_2.jpg)

[back](./)