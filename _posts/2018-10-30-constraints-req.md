---
layout: post
title: "Constraints & Requirements"
date: 2018-10-30 11:00:00 +0800
categories: [log]
---


|Spec #|D/W|Date added/modified|Description|Specifications|Responsibility|Test|
|:---------|:------|:-----------|:-----------|:-----------|:------------|:-----------|
|1         |D      |2018-10-31  |Simple operation of watercraft|Using a PS2 controller|Selwyn|-|
|2         |D      |2018-10-31  |Streamlined bodyshape|Reduce drag as much as possible.<br> Achieve drag coefficient < 0.3|Selwyn|-|
|3         |D      |2018-10-31  |Able to carry a heavy payload|Min. payload weight = 2 kg, Max = 3kg |Selwyn|Add weights|
|4         |W      |2018-10-31  |Able to be used from afar|Min. 5m|Elvis|Simple majority voting|
|5         |W      |2018-10-31  |Swappable sensor modules|Suggested usage of "keying"|Elvis|Check whether data connection is common|
|6         |W      |2018-10-31  |Can return to original resting position when capsized.|-|Selwyn|Test it in a rasin/basin/pool with a prototype|
|7         |D      |2018-10-31  |Electronics insulated from water|2m depth, minimum 10mins of immersion|Selwyn|Test it in a rasin/basin/pool with a prototype|
|8         |D      |2018-10-31  |Able to provide real time feedback for sensor data|Delay < 500ms |Glenn|Test it with Arduino before attaching to submarine. (Test in air and underwater)|
|9         |D      |2018-10-31  |At least 0.2m/s| |Glenn|-|