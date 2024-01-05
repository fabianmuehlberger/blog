---
title: Update
date: 2024-01-05T11:08:52+01:00
draft: false
menu: projects
---

# Small Update on Dewpoint Control

Since I initally started the project and the installation, one of the sensors stopped working. The original TH sensor was no longer available and I had to find a replacement for it. 

I switched to the [SHT31](https://www.dfrobot.com/product-2160.html), a fairly inexpensive sensor that is also available in a waterproof version. The sensor is connected via I2C and can be used in a simmilar way as the AM2315.

Additionally, I did a small cleanup of the code and switched the [sht31 library](https://github.com/kfricke/micropython-sht31/blob/master/sht31.py) 

## Things I learned 
The project is never over, and the 80/20 rule applies. 
