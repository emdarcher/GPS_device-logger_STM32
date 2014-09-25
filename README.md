GPS_device-logger_STM32
=======================

This a project that I have been brainstorming and conceptualizing for a while, after I got some old SmartSensor STM32 dev boards and a Delorme gps2058 serial GPS module from my work. It will display the coordinates and time on an LCD of some sort and also log GPS data to a 2MB SPI flash IC. Some additional features may include dumping the logged data over serial or USB CDC, Solar Power and charging, and 3D printed enclosure. The code will likely run within and RTOS of some sort (most likely ChibiOS/RT ) to help manage the multiple tasks and communication.

Link to the [Hackaday Projects page](http://hackaday.io/project/3062-GPS_device-logger_STM32) for this thing.
