---
layout: default
title: Verra
nav_order: 1
parent: Carbon Project
grand_parent: Carbon Credit Market Insights
---

# Carbon Project (Verra)
---

**Interface Name:** getVerraRegisteredProject

**Description:** :Get the detailed information of carbon projects registered in Verra registry.

**Output Parameters**

| Field                               | Type   | Description                                                       |
|:-------------------------------------|:--------|:-------------------------------------------------------------------|
| Project ID                          | String | Unique identification code for the carbon project registration    |
| Project Name                        | String | Name of the registered carbon project                             |
| Project Type                        | String | Category of the carbon project based on sector                     |
| Country                             | String | Country where the carbon project is located                       |
| Region                              | String | Geographic region where the carbon project is located             |
| Project Status                      | String | Current status of the carbon project e.g. registered etc.         |
| Current Registry                    | String | Carbon registry where the project is currently registered         |
| Registration Date                   | Date   | Date when the project got registered                              |
| Methodology                         | String | Carbon accounting methodology used for the project                |
| Developer                           | String | Organization developing the carbon project                        |
| Credits Issued to Project           | Number | Total carbon credits issued to the project till date              |
| Total Retired                       | Number | Total carbon credits retired from the project                     |
| Total Cancelled                     | Number | Total carbon credits cancelled from the project                   |
| Estimated Annual Emission Reductions| Number | Estimated GHG emission reductions from the project annually       |
| BeZero Carbon Rating                | String | Carbon rating for the project from BeZero based on assessment     |


**Sample Data**

| Project ID | Project Name | Project Type | Country | Region | Project Status | Current Registry | Registration Date | Methodology | Developer | Credits Issued to Project | Total Retired | Total Cancelled | Estimated Annual Emission Reductions | BeZero Carbon Rating |
|:------------|:--------------|:--------------|:---------|:--------|:----------------|:------------------|:-------------------|:-------------|-----------|:----------------------------|:---------------|:-----------------|:------------------------------------|:----------------------|
| VCS487     | 210 MW Musi Hydro Power Plant, Bengkulu | Energy industries (renewable/non-renewable sources) | Indonesia | Asia | Registered | Verra | 2020-04-06 | ACM0002 | PT. PLN (Persero) | 6,432,548 | 3,182,476 | 302,069 | 953,128 | BB |
| VCS2402    | Linshu Biogas Recovery and Power Generation Project | Energy industries (renewable/non-renewable sources); Waste handling and disposal | China | Asia | Registered | Verra | 2021-08-04 | ACM0014 | VPOWER New Energy Technology (LinYi) LTD | 828,251 | 360,846 | 12,483 | 359,691 | B |
| VCS1529    | Inner Mongolia Chao’er Improved Forest Management Project | Agriculture Forestry and Other Land Use | China | Asia | Registered | Verra | 2020-04-06 | VM0010 | Chao’er Forest Bureau of Inner Mongolia Autonomous Region | 445,305 | 197,634 | 0 | 90,035 | B |
| VCS1899 | Sumatra Merang Peatland Project (SMPP) | Agriculture Forestry and Other Land Use | Indonesia | Asia | Registered | Verra | 2020-04-06 | VM0007 | Multiple Proponents | 2,663,148 | 2,250,456 | 6,600 | 1,338,569 | A |
| VCS1406 | Jingyuan County 100MW Solar Power Generation Project | Energy industries (renewable/non-renewable sources) | China | Asia | Registered | Verra | 2020-04-06 | ACM0002 | Gansu Deyou Energy Technology Co., Ltd | 859,993 | 508,148 | 31,237 | 128,589 | B |
| VCS2581 | Grouped projects for Mekong River Delta Water Purifier | Energy demand | Vietnam | Asia | Registered | Verra | 2022-07-25 | AMS-III.AV. | Sustainability Investment Promotion and Development Joint Stock Company | 645,596 | 11,871 | 0 | 1,202,693 | BB |
| VCS2099 | Ningbo Yinzhou Landfill Gas Recovery and Utilization Project | Energy industries (renewable/non-renewable sources); Waste handling and disposal | China | Asia | Registered | Verra | 2020-06-16 | ACM0001 | Ningbo Micropowers New Energy Co., Ltd. | 360,066 | 360,066 | 0 | 88,139 | BBB |
| VCS756 | Crow Lake Wind Emissions Reduction Project | Construction; Energy industries (renewable/non-renewable sources) | United States of America | North America | Registered | Verra | 2020-04-06 | ACM0002 | Multiple Proponents | 3,387,900 | 2,770,459 | 37,807 | 432,128 | B |
| VCS403 | Siam Cement Biomass Project | Manufacturing industries | Thailand | Asia | Registered | Verra | 2020-04-06 | ACM0003 | SCG Cement Co., Ltd. | 3,994,627 | 3,873,760 | 358 | 107,356 | BB |
| VCS2072 | UK CowCredit project: A UK dairy initiative to reduce methane from enteric fermentation | Livestock, enteric fermentation, and manure management | United Kingdom | Europe | Registered | Verra | 2020-11-05 | VM0041 | MOOTRAL SA | 3,303 | 109 | 0 | 187,563 | A |