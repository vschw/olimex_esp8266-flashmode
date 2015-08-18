############################################
Olimex MOD-WIFI-ESP8266-DEV flash mode setup
############################################


Pinouts
=======
::

         +------------------------+
 3.3V    |1    || || || || ||   22|   GPIO4
 GND     |2         UEXT        21|   GPIO0
 GPIO1   |3                     20|   GPIO2
 GPIO3   |4                     19|   GPIO15
 SD_CLK  |5                     18|   GPIO13
 SD_D2   |6                     17|   GPIO14
 SD_D1   |7                     16|   GPIO12
 SD_CMD  |8                     15|   GPIO16
 SD_D0   |9                     14|   CHIP_E
 SD_D3   |10                    13|   RSTB
 GPIO5   |11                    12|   ADC
         |                        |
         |        Antenna         |
         +------------------------+



Flashing Mode
=============
::

         +------------------------+
 3.3V    |1    || || || || ||   22|   
 GND     |2         UEXT        21|   GND
 TX      |3                     20|   
 RX      |4                     19|   
         |5                     18|   
         |6                     17|   
         |7                     16|   
         |8                     15|   
         |9                     14|   
         |10                    13|   
         |11                    12|   
         |                        |
         |        Antenna         |
         +------------------------+
        


Arduino IDE Flashing Setup
==========================

Board
    Generic ESP8266 Module
    
Flash Mode
    DIO

Flash Frequency
    40Mhz

Upload Using
    Serial
    
CPU Frequency
    80Mhz
    
Flash Size
    512K (64 SPIFFS)

Upload Speed
    115200
    
Port
    <select>
    
Programmer
    AVRISP mkII

