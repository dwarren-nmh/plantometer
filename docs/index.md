# Making Things Together
## Plantometer (or how to not kill a plant)

With a microcontroller, a few lines of python, and a capacitive soil moisture sensor, we can create a tool to help us remember to water our plant. Not only will we create an IoT (internet of things) device, but we'll also learn some things about computer science and the internet along the way.

### 1. [M5Stick C](https://m5stack.com/collections/m5-core/products/stick-c)
![M5Stick C](./documentation/img/M5Stick.png)

The M5Stick C is a little computer. Built around an [esp32](http://esp32.net/), the M5Stick C has a 2 core procesor that can run up to 240MHz. With this we can get input values from sensors and other devices, and create outputs as well. It has a little 80x160 pixel screen, LED, battery, gyroscope and a microphone all in one tiny package. Even better, it has the ability to connect to a wifi network and communicate with other computers on the internet.

This will be the "thing" in our "internet of things" device. We will use this little computer to communicate with the soil sensor, connect to a wifi network, and then send the data to a server. We'll also use the screen to create a nice visual that shows us the information in real time.

### 2. [Adafruit STEMMA Soil Sensor](https://www.adafruit.com/product/4026)
![Stemma soil sensor](./documentation/img/stemmasoilsensor.png)

The STEMMA Soil Sensor is a capacitive moisture sensor. It uses capicitance to measure the amount of moisture in the soil, which is different from the resistive measurement of other probes. This sensor will be more durable and more accurate over time, but we'll need to talk about how to use it. It's a sensitive device, pun intended.

# Tutorials
[Getting Started with M5Stick C](/getting-started-m5stick)