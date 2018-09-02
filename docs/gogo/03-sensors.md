# Using Sensors

Up to 8 analog sensors can be connected to the GoGo Board. The sensor ports are located at the lower part of the GoGo Board and are labeled 1-8. The GoGo Board also has two digital sensor ports located at the upper right corner and labeled I2C-1, I2C-2.

Analog sensors are simple to use. The GoGo kit comes with a rich set of sensors out of the box. Since the GoGo Board is compatible with the "[Grove](https://www.google.com/url?q=http://www.seeedstudio.com/wiki/Grove_System&sa=D&ust=1516951079209000&usg=AFQjCNHxLEdoCB67xV8K6qe_BsNtzbv_2A)" system, a much bigger selection of sensors can be obtained from [SEEED studio](https://www.google.com/url?q=https://www.seeedstudio.com&sa=D&ust=1516951079210000&usg=AFQjCNHybadFBnfDzeIcUBDcZAyKJ1GuEw). Note that not all sensors on the SEEED store are compatible with the GoGo Board. Please refer to the compatibility chart (link required) before making a purchase.

To use a sensor, simply use the supplied sensor cable to connect any sensor to a sensor port. The GoGo Widget displays sensor values as bar graphs with numbers below them. As an example, try connecting a light sensor to port number 1. Exposing this sensor to different levels of brightness will cause the sensor value to change. Try to cover the light sensor using your hand and then release it. You should see sensor 1’s value change accordingly as illustrated in the images below.

![light sensor demo](https://lh3.googleusercontent.com/vacLSnU69A5KbTvpA-7kqdfsQ_ljvbpEYNq7-fAAe5LVwR9Z7kq2YY8nTq4PZU3tMXivyzBnZB0ymlh5MZEde96ERP4jpwD_FOSQXCLpisdlz_56eq-tsVyLOlV0rTRq_L4ZfrIR)
The value of a light sensor will be higher in the top figure because it receives more light than the one below it.

### Overview of Sensors Provided in the GoGo Board Kit 

##### Lever Switches and Buttons
![Lever Switches and Buttons](https://lh6.googleusercontent.com/XXhoiviM0cP9LWZSgzPx0pWmHF0x-tR4V8OhTWUseZfxY3xGaHsyGhh-O5gTvfPI-BFfGeMEibbzyN9AMxTOgTI_vG4uYLYIu8t6anoM7GqdF8GhQbq1BX0YVVc38N52Md8o0loC)

Lever switches and buttons are similar. They both produce a high value readout when pressed and become near zero when released. Lever switches (also called limit switches) are suitable for detecting objects such as walls, balls, and other mechanical parts. Buttons, on the other hand, are usually for humans to press.

##### Button Set
![Button Set](https://lh5.googleusercontent.com/VUuiVQfDIceaurA8ryCCKjCOdan_ojwqc-Ogk9oiTRG6wBkPoh3-9_3EjxNkxEgRUqDUo_AL_sG_9mdyHAXpLfrVwb0iCmKGt-oUY4JY7gBwwPLyMTdp5RJ7jfbck4nPfMl6uJOx)

Useful as a game or motion controller, the button set produces different readouts for each button.

##### Light Sensor
![Light Sensor](https://lh5.googleusercontent.com/Rmta4SQ9rb1CuqJC9vY8uw2z4zgpFS7AN6q9hSuqbtxWINkbDGAognrPA6hnccv69Y8ekl-TX3fxjedsuwo3xmHmx09xpjsnYAJB_OJgzHxJvoyNSvG8lybrCexIjteQXqjVuOnZ)

The readout value varies  according to the amount of light the sensor receives.

##### Temperature Sensor
![Temperature Sensor](https://lh5.googleusercontent.com/ec1kkqFywSPdfv0K6UxZHlfoQaQxUUETpQNnWNWIVhACiKBn0X8nm8DHSp_9twDveYbGnupKMMISXga4RLLAlDAbfIYvwBa4M_t70_FS-wB9EiG1BjmrJpUUTb1TxwPBQAw9D33W)

The readout value corresponds to the ambient temperature. Note that the readout is not in Celsius or Fahrenheit. The value is reflects the resistance of the sensor. Mappings between the resistance and the standard units must be done manually.

##### Magnetic Sensor
![Magnetic Sensor](https://lh6.googleusercontent.com/CQGNhkdfH75drhz385lKoW1OglalqJBSMLQhiySijjqP--X6O6tu1wlXJOunjBo812kH5iarjZ3BdrSkZTjiJ4qFYrz-Be1pFbg5Ih_bgaO-koYnUkgcByjTe5c2BLh3POmkZuE5)

Magnetic sensors are often used as a non-contact switch. For example, to measure the speed of a bicycle, a magnetic sensor can be placed on the wheel’s frame. A magnet is stuck on to the wheel. With this setup, the magnetic sensor will detect the magnet every time it passes by. Measuring the time between counts can be later used to calculate the bicycle’s speed.

##### Infrared Reflective Sensor
![Infrared Reflective Sensor](https://lh6.googleusercontent.com/9bqUi-qv_uhq71zSn1qe5G5Q2os-9ULuRJx4bYSiWGFkwLS6zst3X9RLamf2FFtss5Z84vbJSwBFot1EuPXAiKHHl78HWCK0QvImOj_90SzTNkjAKNDW9R7ATZbA-Ty3MOQCzG-f)

This sensor is commonly used to measure proximity. It emits infrared light and measures how much of that light is reflected back. Therefore, if there is no object to bounce back the light, the sensor will give a small measurement. The closer an object is to the sensor, the higher the measurement. The effective range of this sensor is less than 5 centimeters. Note that color of the object also determines how much light is reflected. For example, black objects absorbs more light than lighter colors and, at the same distance, produces a lower measurement. Therefore, this sensor can also be adapted as a color sensor.  

> **Caution** - This sensor is sensitive to infrared light from other sources as well. Therefore, the interference of sunlight, fluorescent light or other infrared light sources may lead to irregular readings.

##### Rain Sensor
![Rain Sensor](https://lh6.googleusercontent.com/Syxw8-t7T8gElVNzcRClX8MVIrQu5OnVxiJ7ZqqEiTO-xmxtVwgXgBJ-Xgyj1UN5-syZ2WDSDqpjLuDL39UdrzepjDW_JQqMME0R2KVSntoxuOqeixBVcHAf2tROFyNFADtiXM0Z)

The metal below this sensor is  very sensitive to raindrops. In the event of a rainfall, it is best to turn this side up for direct rainfall detection. Make sure to keep the connector dry.

##### Soil Humidity Sensor
![Soil Humidity Sensor](https://lh5.googleusercontent.com/ShjcJG_JzPDLen6CHoZZ4e0Sj32jGRE9LkxeuEOF3dj6xbNRnLBs99zIflF2-HfLuEQvP3Mxs25vxdhhigT3l7XoaJ09EYUyPRfVp_y9uOvdiCScQY8JnIfMLVQ_Ea48FmfoWtS4)

Under this sensor lies 2 metal plates to measure soil humidity or moisture in the soil. After inserting the probe into the soil, make sure the connector stays dry for an accurate readout.

##### Terminal Connector
![Terminal Connector](https://lh6.googleusercontent.com/BsDQ0Lmmj7k9reFACTEsyOA4DZzNWpNU4UPFLcLUXE90ZmSS-JHGJHknNh9i-nWG90HLG6i3DOGQdDADIxE3sIH4rUigGNeczo-xpQE5f32wpqlR7wWbCZlke0e652HwQEYGV5Og)

This terminal connector is used for additional sensors that are not included in this kit. Three screws in the adapter are used for power, ground, and signal (VCC, GND, Sig).  
