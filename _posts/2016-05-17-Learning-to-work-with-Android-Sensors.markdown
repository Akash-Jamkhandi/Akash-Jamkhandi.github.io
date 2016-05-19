---
layout: post
title:  "Learning to work with Android Sensors"
date:   2016-05-17 22:10:00 +0530
categories: Programming Android
---

I have never had a chance to work with Android sensors professionally, so I wanted to get a hang of how sensors are used. I started working on a Push up counter application using the proximity sensor. Turns out, not all sensors give you a distance value. My phone returns only 2 values, 0.0 and 8.0 (max distance). 

Using sensors is pretty simple. Implement a SensorEventListenerm, create a SensorManager and Sensor object and you're good to go. Just wait for the callback methods to fire. Make sure to register and unregister the sensor.

I'll update this with my progress tomorrow.

TODO :
Seperate Activity and SensorListener.
Use a backgroud service to listen if possible.
Change UI.
Push to Github.
 
