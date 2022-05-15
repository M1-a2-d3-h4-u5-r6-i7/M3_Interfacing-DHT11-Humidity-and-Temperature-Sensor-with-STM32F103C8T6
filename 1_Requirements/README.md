## Description :


Sensors are great little devices that bridge the gap between the raw analog World with Microcontroller’s digital World. Sensors can be very simple like the very famous LM35 Temperature Sensor or they can be some complex mathematical units like the MPU6050 Gyro and Accelerometer combi sensor.

Simple or complex, Sensors are a key part of many consumer, automobile, robotic and industrial applications and several applications cannot be completed without integration of proper sensors.

Let us scale down a little bit from industrial applications to everyday projects and hobbyists. A very common and popular project, be it an IoT application or just a regular character LCD application, is the Weather Station.

The key component of such weather station projects is the ability to detect weather related parameters like Temperature, Humidity etc. The DHT11 Humidity and Temperature Sensor is just the device for these types of projects.

I have already used the DHT11 Sensor in an Arduino Project called “DHT11 Humidity Sensor on Arduino”. In that project, I have interfaced the DHT11 Sensor with Arduino, calculated the temperature and humidity values and displayed it on the 16×2 LCD Display. I will do the same thing here as well but this time I will be interfacing DHT11 Humidity and Temperature Sensor with STM32F103C8T6 MCU.



## Requirements :


### Components Required :-

    STM32F103C8T6 MCU based STM32 Blue Pill Board
    DHT11 Humidity and Temperature Sensor
    16×2 LCD Display
    PCF8574 I2C LCD Module
    5KΩ Resistor (Optional, no required if it is present on DHT11 Module)
    Connecting Wires
    USB to UART Converter (needed only if programming through UART)
    
    ## 4'W 1'H
    
    ### What:-
       
       Temperature and humidity sensor (or rh temp sensor) is devices that can convert temperature and humidity into electrical
       signals that can easily measure temperature and humidity.
       
    ### Why:-
      
       Humidity sensors are electronic devices that measure and report the moisture and air temperature of the surrounding 
       environment where they are deployed e.g., in air, soil, or confined spaces. Humidity measurements indicate the
       concentration of water vapor presented in the air.
        
    ### When:-
    
       Temperature and humidity sensors are among the most commonly used environmental sensors. Humidity sensors are also
       sometimes referred to as hygrometers. These devices are used to provide the actual humidity condition within the air
       at any given point or in any given place.
       
     ### Who:-
     
       Measuring humidity within the environment can be critical due to the fact that the higher the humidity, the warmer 
       it may seem. In industries, humidity measurement is often important because it can affect the health and safety of
       personnel as well as the cost of the product. As a result, temperature and humidity sensors are often quite important.
       
     ### How:-
     
       It can be used in fields to check wheter ground having suficient water or not and it indicates the concentration of
       water vapour present in air.
      
      
      
