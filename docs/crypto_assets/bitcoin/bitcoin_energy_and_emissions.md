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

|    | Date                |   24hr_kWh |   24hr_kgCO2 |   Output_kWh |   Output_kgCO2 |
|---:|:--------------------|-----------:|-------------:|-------------:|---------------:|
|  9 | 2023-11-10 00:00:00 |  377214438 |    210395125 |      260.5   |        145.296 |
|  8 | 2023-11-09 00:00:00 |  377214438 |    210395125 |      274.026 |        152.841 |
|  7 | 2023-11-08 00:00:00 |   37721443 |    210395125 |      262.698 |        146.523 |
|  6 | 2023-11-07 00:00:00 |  376317836 |    209895036 |      246.21  |        137.326 |
|  5 | 2023-11-06 00:00:00 |  375192259 |    209267234 |      240.749 |        134.28  |
|  4 | 2023-11-05 00:00:00 |  374116674 |    208667316 |      259.038 |        144.481 |
|  3 | 2023-11-04 00:00:00 |  372997680 |    208043186 |      285.226 |        159.087 |
|  2 | 2023-11-03 00:00:00 |  371882034 |    207420923 |      296.997 |        165.653 |
|  1 | 2023-11-02 00:00:00 |  370769725 |    206800522 |      303.889 |        169.497 |
|  0 | 2023-11-01 00:00:00 |  369660743 |    206181976 |      301.985 |        168.435 |

