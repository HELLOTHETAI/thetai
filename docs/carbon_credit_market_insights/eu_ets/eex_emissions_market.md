---
layout: default
title: EEX Emissions Market (EUA & EUAA)
nav_order: 1
parent: European Union Emissions Trading System (EU ETS)
grand_parent: Carbon Credit Market Insights
---

## Primary Market Auction
---

**Interface Name:** EEX Emissions Primary Market Auction

**Description:** This interface provides data on the primary market auctions for EU ETS emissions allowances on the European Energy Exchange (EEX). The auctions allocate allowances to compliant entities to cover their verified carbon emissions.

**Output Parameters**

| Field Name | Type | Description |
|:---------|:---|:--------------------|
| Date | Timestamp | Date of the auction |
| Time | Timestamp | Time of the auction |
| Auction Name | String | Name/code of the specific auction |
| Contract | String | Contract type (spot, futures etc) |
| Status | String | Auction status (open/closed) |
| Auction Price | Float | Clearing price of the auction (€/ton CO2) |
| Minimum Bid | Float | Minimum bid price (€/ton CO2) |
| Maximum Bid | Float | Maximum bid price (€/ton CO2) |
| Mean | Float | Mean bid price (€/ton CO2) |
| Median | Float | Median bid price (€/ton CO2) |
| Auction Volume | Integer | Total volume of allowances auctioned (ton CO2) |
| Total Amount of Bids | Integer | Total bid volume submitted |
| Number of bids submitted | Integer | Number of bids submitted |
| Number of successful bids | Integer | Number of bids awarded allowances |
| Average number of bids per bidder | Float | Average bids per bidder |
| Average bid size | Float | Average bid size |
| Average volume bid per bidder | Float | Average volume of bids per bidder |
| Standard deviation of bid volume per bidder | Float | Standard deviation of bid volumes per bidder |
| Average volume won per bidder | Float | Average volume won per successful bidder |
| Standard deviation of volume won per bidder | Float | Standard deviation of volumes won per successful bidder |
| Cover Ratio | Float | Ratio of volume bid to volume auctioned |
| Total Number of Bidders | Integer | Total number of entities submitting bids |
| Number of Successful Bidders | Integer | Number of entities winning bids |
| Total Revenue | Float | Total revenue from auction (€) |
| Country | String | Country conducting auction |


**Sample Data**

| Date | Time | Auction Name | Contract | Status | Auction Price €/tCO2 | Minimum Bid €/tCO2 | Maximum Bid €/tCO2 | Mean €/tCO2 | Median €/tCO2 | Auction Volume tCO2 | Total Amount of Bids | Number of bids submitted | Number of successful bids | Average number of bids per bidder | Average bid size | Average volume bid per bidder | Standard deviation of bid volume per bidder | Average volume won per bidder | Standard deviation of volume won per bidder | Cover Ratio | Total Number of Bidders | Number of Successful Bidders | Total Revenue € | Country | Austria (AT) | Belgium (BE) | Bulgaria (BG) | Cyprus (CY) | Czech Republic (CZ) | Germany (DE) | Denmark (DK) | Estonia (EE) | Greece (EL) | Spain (ES) | Finland (FI) | France (FR) | Croatia (HR) | Hungary (HU) | Ireland (IE) | Innovation Fund (IF) | Iceland (IS) | Italy (IT) | InnoFund RRF (IX) | Liechtenstein (LI) | Lithuania (LT) | Luxembourg (LU) | Latvia (LV) | Modernisation Fund (MF) | Malta (MT) | MS RRF (MX) | Netherlands (NL) | Norway (NO) | Poland (PL) | Portugal (PT) | Romania (RO) | Sweden (SE) | Slovenia (SI) | Slovakia (SK) | Northern Ireland (XI) |
|:------------|:--------------|:--------------|:---------|:--------|:----------------|:------------------|:-------------------|:-------------|:-----------|:----------------------------|:---------------|:-----------------|:------------------------------------|:----------------------|:--------------------------|:----------------------------------------|:--------------------------|:------------------------------------|:----------------------|:---------------|:-----------------|:----------------------|:----------------------|:---------------|:---------------|:---------------|:---------------|:----------------|:------------------|:---------------|:---------------|:---------------|:---------------|:----------------|:------------------|:---------------|:---------------|:---------------|:------------------|:---------------|:---------------|:------------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|:---------------|
| 13.11.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 77.01 | 74.62 | 120.00 | 77.29 | 76.66 | 3,035,500 | 4,521,500 | 83 | 26 | 4.37 | 54,476 | 237,974 | 290,273 | 202,367 | 265,079 | 1.49 | 19 | 15 | 233,763,855 | EU | 3,426,945 | 5,891,265 | 8,586,615 | 847,110 | 6,545,850 | | 3,234,420 | 2,656,845 | 10,935,420 | 26,799,480 | 4,505,085 | 16,095,090 | 1,193,655 | 3,388,440 | 1,347,675 | 0 | 0 | 27,569,580 | 22,640,940 | 0 | 847,110 | 0 | 654,585 | 38,042,940 | 308,040 | 19,175,490 | 9,857,280 | 1,963,755 | | 5,506,215 | 4,967,145 | 2,387,310 | 1,424,685 | 2,964,885 |
| 10.11.2023 | 11:00 | Auction 4. Period DE | T3PA | successful | 76.46 | 73.68 | 120.00 | 76.60 | 75.80 | 2,147,000 | 3,955,500 | 85 | 22 | 3.54 | 46,535 | 164,813 | 162,114 | 126,294 | 128,724 | 1.84 | 24 | 17 | 164,159,620 | DE | | | | | | 164,159,620 | | |
| 09.11.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 75.75 | 73.24 | 120.00 | 76.41 | 75.32 | 3,035,500 | 4,567,000 | 79 | 23 | 3.95 | 57,810 | 228,350 | 221,998 | 202,367 | 201,597 | 1.50 | 20 | 15 | 229,939,125 | EU | 3,370,875 | 5,794,875 | 8,446,125 | 833,250 | 6,438,750 | | 3,181,500 | 2,613,375 | 10,756,500 | 26,361,000 | 4,431,375 | 15,831,750 | 1,174,125 | 3,333,000 | 1,325,625 | 0 | 0 | 27,118,500 | 22,270,500 | 0 | 833,250 | 0 | 643,875 | 37,420,500 | 303,000 | 18,861,750 | 9,696,000 | 1,931,625 | | 5,416,125 | 4,885,875 | 2,348,250 | 1,401,375 | 2,916,375 |
| 08.11.2023 | 11:00 | Auction 4. Period CAP3 PL | T3PA | successful | 74.56 | 72.28 | 120.00 | 75.31 | 74.50 | 3,347,500 | 4,979,000 | 83 | 39 | 3.61 | 59,988 | 216,478 | 246,380 | 176,184 | 237,937 | 1.49 | 23 | 19 | 249,589,600 | PL | | |
| 07.11.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 75.58 | 73.49 | 120.00 | 76.54 | 75.59 | 3,035,500 | 4,095,500 | 73 | 38 | 3.84 | 56,103 | 215,553 | 202,240 | 178,559 | 196,905 | 1.35 | 19 | 17 | 229,423,090 | EU | 3,363,310 | 5,781,870 | 8,427,170 | 831,380 | 6,424,300 | | 3,174,360 | 2,607,510 | 10,732,360 | 26,301,840 | 4,421,430 | 15,796,220 | 1,171,490 | 3,333,000 | 1,325,625 | 0 | 0 | 27,057,640 | 22,220,520 | 0 | 831,380 | 0 | 642,430 | 37,336,520 | 302,320 | 18,819,420 | 9,674,240 | 1,927,290 | | 5,403,970 | 4,874,910 | 2,342,980 | 1,398,230 | 2,909,830 |
| 06.11.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 76.02 | 74.04 | 120.00 | 76.93 | 76.12 | 3,035,500 | 3,916,000 | 73 | 50 | 3.84 | 53,644 | 206,105 | 193,313 | 168,639 | 170,039 | 1.29 | 19 | 18 | 230,758,710 | EU | 3,382,890 | 5,815,530 | 8,476,230 | 836,220 | 6,461,700 | | 3,192,840 | 2,622,690 | 10,794,840 | 26,454,960 | 4,447,170 | 15,888,180 | 1,178,310 | 3,344,880 | 1,330,350 | 0 | 0 | 27,215,160 | 22,349,880 | 0 | 836,220 | 0 | 646,170 | 37,553,880 | 304,080 | 18,928,980 | 9,730,560 | 1,938,510 | | 5,435,430 | 4,903,290 | 2,356,620 | 1,406,370 | 2,926,770 |
| 03.11.2023 | 11:00 | Auction 4. Period DE | T3PA | successful | 78.35 | 76.24 | 120.00 | 79.09 | 78.30 | 2,147,000 | 3,398,500 | 75 | 33 | 3.75 | 45,313 | 169,925 | 146,818 | 113,000 | 130,150 | 1.58 | 20 | 19 | 168,217,450 | DE | | | | | | 168,217,450 | | |
| 02.11.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 77.88 | 74.98 | 120.00 | 78.00 | 77.08 | 3,035,500 | 5,149,000 | 94 | 19 | 3.92 | 54,777 | 214,542 | 223,892 | 216,821 | 186,243 | 1.70 | 24 | 14 | 236,404,740 | EU | 3,465,660 | 5,957,820 | 8,683,620 | 856,680 | 6,619,800 | | 3,270,960 | 2,686,860 | 11,058,960 | 27,102,240 | 4,555,980 | 16,276,920 | 1,207,140 | 3,426,720 | 1,362,900 | 0 | 0 | 27,881,040 | 22,896,720 | 0 | 856,680 | 0 | 661,980 | 38,472,720 | 311,520 | 19,392,120 | 9,968,640 | 1,985,940 | | 5,568,420 | 5,023,260 | 2,414,280 | 1,440,780 | 2,998,380 |
| 31.10.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 77.65 | 75.54 | 120.00 | 78.56 | 77.70 | 3,035,500 | 3,949,000 | 69 | 38 | 4.06 | 57,232 | 232,294 | 196,815 | 202,367 | 195,026 | 1.30 | 17 | 15 | 235,706,575 | EU | 3,455,425 | 5,940,225 | 8,657,975 | 854,150 | 6,600,250 | | 3,261,300 | 2,678,925 | 11,026,300 | 27,022,200 | 4,542,525 | 16,228,850 | 1,203,575 | 3,416,600 | 1,358,875 | 0 | 0 | 27,798,700 | 22,829,100 | 0 | 854,150 | 0 | 660,025 | 38,359,100 | 310,600 | 19,334,850 | 9,939,200 | 1,980,075 | | 5,551,975 | 5,008,425 | 2,407,150 | 1,436,525 | 2,989,525 |
| 30.10.2023 | 11:00 | Auction 4. Period CAP3 EU | T3PA | successful | 79.78 | 77.63 | 120.00 | 80.17 | 79.67 | 3,035,500 | 4,622,500 | 84 | 29 | 4.67 | 55,030 | 256,806 | 285,439 | 216,821 | 297,081 | 1.52 | 18 | 14 | 242,172,190 | EU | 3,550,210 | 6,103,170 | 8,895,470 | 877,580 | 6,781,300 | | 3,350,760 | 2,752,410 | 11,328,760 | 27,763,440 | 4,667,130 | 16,674,020 | 1,236,590 | 3,510,320 | 1,396,150 | 0 | 0 | 28,561,240 | 23,455,320 | 0 | 877,580 | 0 | 678,130 | 39,411,320 | 319,120 | 19,865,220 | 10,211,840 | 2,034,390 | | 5,704,270 | 5,145,810 | 2,473,180 | 1,475,930 | 3,071,530 |
| 27.10.2023 | 11:00 | Auction 4. Period DE | T3PA | successful | 79.41 | 76.99 | 120.00 | 79.99 | 79.16 | 2,147,000 | 3,819,500 | 74 | 21 | 3.89 | 51,615 | 201,026 | 224,401 | 165,154 | 232,003 | 1.78 | 19 | 13 | 170,493,270 | DE | | | | | | 170,493,270 | | |












