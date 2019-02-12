---
layout: post
title:  "Assignment One, Digital I/O"
date:   2018-10-23 11:24:07 +0800
categories: [assignment]
---

# Assignment One : Digital I/O

1. ATMega328 has six 10-bit 5V ADC ports.
  * Which ports are used? <br /> 
     - Port C of the ATMega328 are used as the ADC ports
     
  * What is the command used to read the ADC <br />
  * What is the solution?
  
  * how is voltage accuracy achieved?
     - The volatage accuracy is +-2LSB which is around +-9.8mV
     - The resolution 4.88mV
     
  * How fast are the ADC ports?
     - Between 50-200kHz
     - While it is possible to go above 200kHz, there will be a drop in the resolution
     
  * I need a better ADC, what can I do?
     - Get an External module with higher bits resolution:
         - [ADS1015 12-Bit ADC](https://www.adafruit.com/product/1083) 
         - [ADS1115 16-Bit ADC](https://www.adafruit.com/product/1085) 
     
  * How fast does the ADC need to be?
  
2. Experimentations with digital I/O
  * Here's a link to a separate blog post on the experiments [LINK]({{ site.baseurl  }}{% post_url 2018-10-24-digital-io-experiments %})
