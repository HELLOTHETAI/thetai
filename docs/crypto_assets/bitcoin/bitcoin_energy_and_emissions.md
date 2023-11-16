---
layout: default
title: Bitcoin Energy and Emissions
nav_order: 1
has_children: true
parent: Bitcoin
grand_parent: Crypto Assets - Energy and Emissions Data
---

# Bitcoin Energy and Emissions
---

**Interface Name:** Bitcoin Energy and Emissions Metrics

**Description:** This API provides data on the energy consumption and carbon footprint of the Bitcoin network, broken down per transaction.

**Output Parameters:**

| Field Name | Type | Description |
| --- | --- | --- |
| date | String | Date of data in YYYYMMDD format |
| 24hr_kWh | Float | Total energy used by Bitcoin network over 24 hours (kWh) |
| 24hr_kgCO2 | Float | Total carbon footprint of Bitcoin over 24 hours (kg CO2) |
| Transaction_kWh | Float | Average energy consumed per transaction (kWh) |
| Transaction_kgCO2 | Float | Average carbon footprint per transaction (kg CO2) |

**Sample Data:**

| Date     |   24hr_kWh |   24hr_kgCO2 |   Output_kWh |   Output_kgCO2 |
|:---------|-----------:|-------------:|-------------:|---------------:|
| 20231110 |  377214438 |    210395125 |      260.5   |        145.296 |
| 20231109 |  377214438 |    210395125 |      274.026 |        152.841 |
| 20231108 |   37721443 |    210395125 |      262.698 |        146.523 |
| 20231107 |  376317836 |    209895036 |      246.21  |        137.326 |
| 20231106 |  375192259 |    209267234 |      240.749 |        134.28  |
| 20231105 |  374116674 |    208667316 |      259.038 |        144.481 |
| 20231104 |  372997680 |    208043186 |      285.226 |        159.087 |
| 20231103 |  371882034 |    207420923 |      296.997 |        165.653 |
| 20231102 |  370769725 |    206800522 |      303.889 |        169.497 |
| 20231101 |  369660743 |    206181976 |      301.985 |        168.435 |

