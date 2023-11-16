---
layout: default
title: Dogecoin Energy and Emissions
nav_order: 1
has_children: true
parent: Dogecoin
grand_parent: Crypto Assets - Energy and Emissions Data
---

# Dogecoin Energy and Emissions
---

**Interface Name:** Dogecoin Energy and Emissions Metrics

**Description:** This API provides data on the energy consumption and carbon footprint of the Dogecoin network, broken down per transaction output.

**Output Parameters:**

| Field Name | Type | Description |
| --- | --- | --- |
| date | String | Date of data in YYYYMMDD format |
| 24hr_kWh | Float | Total energy used by Dogecoin network over 24 hours (kWh) |
| 24hr_kgCO2 | Float | Total carbon footprint of Dogecoin over 24 hours (kg CO2) |
| Output_kWh | Float | Average energy consumed per transaction output (kWh) |
| Output_kgCO2 | Float | Average carbon footprint per transaction output (kg CO2) |

**Sample Data:**

| Date     |   24hr_kWh |   24hr_kgCO2 |   Output_kWh |   Output_kgCO2 |
|:---------|-----------:|-------------:|-------------:|---------------:|
| 20231110 |    6072243 |      3386854 |      12.3381 |        6.88169 |
| 20231109 |    6076411 |      3389179 |      14.5869 |        8.13601 |
| 20231108 |    6085301 |      3394138 |      22.5059 |       12.5529  |
| 20231107 |    6095412 |      3399777 |      38.9266 |       21.7117  |
| 20231106 |    6107150 |      3406324 |      57.0889 |       31.8419  |
| 20231105 |    6118094 |      3412428 |      70.695  |       39.4309  |
| 20231104 |    6130353 |      3419266 |      75.0921 |       41.8834  |
| 20231103 |    6144703 |      3427270 |      78.1234 |       43.5741  |
| 20231102 |    6161353 |      3436556 |      70.747  |       39.4598  |
| 20231101 |    6173271 |      3443204 |      61.4953 |       34.2996  |

