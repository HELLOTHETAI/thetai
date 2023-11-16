---
layout: default
title: Ethereum Energy and Emissions
nav_order: 1
has_children: true
parent: Ethereum
grand_parent: Crypto Assets - Energy and Emissions Data
---

# Ethereum Energy and Emissions
---

**Interface** Name: Ethereum Energy and Emissions Metrics

**Description:** This API provides data on the energy consumption and carbon footprint of the Ethereum network, broken down per unit of gas used for transactions.

**Output Parameters:**

| Field Name | Type | Description |
| --- | --- | --- |
| date | String | Date of data in YYYYMMDD format |
| 24hr_kWh | Float | Total energy used by Ethereum network over 24 hours (kWh) |
| 24hr_kgCO2 | Float | Total carbon footprint of Ethereum over 24 hours (kg CO2) |
| Gas_unit_Wh | Float | Average energy consumption per unit of gas (Wh) |
| Gas_unit_gCO2 | Float | Average carbon footprint per unit of gas (g CO2) |

**Sample Data:**

|    | Date                |   24hr_kWh |   24hr_kgCO2 |   Output_kWh |   Output_kgCO2 |
|---:|:--------------------|-----------:|-------------:|-------------:|---------------:|
|  9 | 2023-11-10 00:00:00 |      28415 |        15849 |  0.000263813 |    0.000147144 |
|  8 | 2023-11-09 00:00:00 |      25023 |        13957 |  0.000240933 |    0.000134383 |
|  7 | 2023-11-08 00:00:00 |      26944 |        15028 |  0.000249737 |    0.000139293 |
|  6 | 2023-11-07 00:00:00 |      27758 |        15482 |  0.000257471 |    0.000143607 |
|  5 | 2023-11-06 00:00:00 |      24490 |        13660 |  0.00024838  |    0.000138536 |
|  4 | 2023-11-05 00:00:00 |      24535 |        13685 |  0.000227113 |    0.000126674 |
|  3 | 2023-11-04 00:00:00 |      26646 |        14862 |  0.000247473 |    0.00013803  |
|  2 | 2023-11-03 00:00:00 |      26073 |        14543 |  0.000252857 |    0.000141034 |
|  1 | 2023-11-02 00:00:00 |      26474 |        14766 |  0.000245257 |    0.000136795 |
|  0 | 2023-11-01 00:00:00 |      22413 |        12501 |  0.000214327 |    0.000119543 |

