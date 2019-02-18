---
layout: post
title: Calculations
date: 2019-01-19 12:00:00 +0800
categories: [log]
---
# Requirements for neutral buoyancy calculations
<img src="/speaalpha18/asset_images/calculations/IMG_6623.jpg"/>

# Power draw

|Parts used| Voltage(V)| Amperage (A)| Qty| Safety factor| Max Amperage Consumed (A)| Max Power Consumption(W)|
|:-|:-|:-|:-|:-|:-|:-|
|350 GPH bilge pump|12|1.5|2|2|4|48|
|1100GPH bilge pump|12|3|2|5|10|120|
|Arduino|8|0.3|2|-|0.6|4.8|
|5W LED|12|0.4|1|-|0.4|5|
|Camera|12|0.03|1|-|0.03|0.84|
|Camera receiver|8|0.07|1|-|0.07|0.056|
|LM7805|5|0.00025|1|-|0.00025|0.00125|
|LM7808|8|0.3|1|-|0.3|2.4|
| | | | |Total|15.69|181.09725|
*The maximum current of 15.69 A refers to the maximum current drawn by the entire system, assuming everything is switched on with all 4 motors are stalling.

# Under normal circumstances
Based from the average ampere each component consumes (3rd Column),
Total amperage draw = (1.5 x 2) + (3 x 2) + (0.3 x 2) + 0.4 + 0.03 + 0.07 = 10.1A

Batteries given: 3S 11.1V, 2250mAh (2.2A) , 25Wh, 45C (99A max discharge)
Therefore, run time of the entire craft is:
(2.2/10.1) x 60 = 13.1 mins

Given that under normal circumstances, the craft can run for 13.1 mins before the battery must be recharged.

# Under maximum circumstances
If the watercraft is running at overload current, from the table, the craft draws about 15.1A.

Batteries given: 3S 11.1V, 2250mAh (2.2A) , 25Wh, 45C (99A max discharge)
Therefore, run time of the entire craft is:
(2.2/15.1) x 60 = 8.7 mins

So this means that the minimum time the craft should run for is 8.7 mins.
