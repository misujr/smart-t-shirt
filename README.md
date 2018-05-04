# smart-t-shirt
Smart t-shirt with tranceiver based on Arduino and Nrf24L01

The smart t-shirt is a personal project that I have developed back in 2013 with the intention of creating smart clothing for :
- Elder people
- People working in high risk positions
- Undercover workers
- and many others...

This project was developed by me fully using public available libraries and modifications added to them . 

Main features : flex sensors, pressure sensors, temperature sensor, pulse sensor, 3 axis accelerometer, wireless communication, mobile phone connectivity
Wireless protocol frequency : 2,4 Ghz
Data Rate ; max 2Mb/s
Channels : 6
Flex sensors : 11 cm long
Pressure sensors : 4x4 cm but we are now testing 20x20cm ones
3 Axis accelerometer
Digital pulse sensor
Digital temperature sensor
Battery : 2000mAh li-Pol or 3600mAh li-Pol
Authonomy : 9 hours with the 2000mAh version


The main idea is that the board that acts as a t-shirt will gather the data from all the sensors and then will send it OTA using the NRF24L01 TX/RX moculeds to a receiver board that will show the data on an LCD/Display and also output it on a serial port. 

This code can be modified or transformed to work with BLE, Zigbee and so on...

This code is released to encourage people to learn and push their boundaries. 

This code can not be copied, modified or used in any commercial product as it is the IPR or Pauciuc Mihai-Stefan and it would consist the background IP of any project in which it will be used. 

This code comes with no guarantee and it is your sole responsibility if you shall wish to use it to check pinouts, pin definitions in both comments of the and libraries and make the proper electrical connections to get it up and running. 



TO DO : 
- Add sensors datasheet
- Add the Tshirt board Code
- Add the Receiver board code
