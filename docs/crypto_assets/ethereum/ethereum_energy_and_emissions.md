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

| Date     |   24hr_kWh |   24hr_kgCO2 |   Output_kWh |   Output_kgCO2 |
|:---------|-----------:|-------------:|-------------:|---------------:|
| 20231110 |      28415 |        15849 |  0.000263813 |    0.000147144 |
| 20231109 |      25023 |        13957 |  0.000240933 |    0.000134383 |
| 20231108 |      26944 |        15028 |  0.000249737 |    0.000139293 |
| 20231107 |      27758 |        15482 |  0.000257471 |    0.000143607 |
| 20231106 |      24490 |        13660 |  0.00024838  |    0.000138536 |
| 20231105 |      24535 |        13685 |  0.000227113 |    0.000126674 |
| 20231104 |      26646 |        14862 |  0.000247473 |    0.00013803  |
| 20231103 |      26073 |        14543 |  0.000252857 |    0.000141034 |
| 20231102 |      26474 |        14766 |  0.000245257 |    0.000136795 |
| 20231101 |      22413 |        12501 |  0.000214327 |    0.000119543 |

