# MicroPython sprint at SciPy 2018
Austin-TX, July 14-15th 2018

The MicroPython sprint goal is to live demonstrate MicroPython to new users and attract new developers to contribute to scientific MicroPython modules, for example, by porting/adapting scientific Python 3 modules.  

### Goals

This sprint is the 2nd opportunity in SciPy history to practice :
- MicroPython on real microcontroller boards;
- connecting to sensors and actuators;
- processing sensor data with scientific MicroPython modules (statistics, error propagation, FFT, etc);
- IoT (Internet of Things) using WiFi and/or LoRa to publish sensor data;
- contributing to the MicroPython community;
- creating new MicroPython modules, from scratch or converting/adapting from scientific Python 3 modules;
- porting scientific MicroPython modules to a broad range of MicroPython boards (see below the list).

### To know more about MicroPython

First look at :
- the [**"Scientific MicroPython on Microcontrollers and IoT" talk**](http://www.robertocolistete.net/MicroPythonSciPy2017/#/) given on July 13th 2017, where MicroPython were presented and all official MicroPython boards where cited;
- the [**"Scientific MicroPython on Microcontrollers tutorial"**](https://github.com/rcolistete/MicroPython_Tutorial_SciPy_2018) given on July 10th 2018, focused on LoPy4 + sensors. 

Documentation about MicroPython :
* [MicroPython documentation (for LoPy4 and other Pycom boards)](https://docs.pycom.io/)
* [MicroPython documentation (for BBC Micro:bit)](https://microbit-micropython.readthedocs.io/en/latest/)
* [MicroPython documentation (for Pyboard)](http://docs.micropython.org/en/latest/pyboard/)
* [MicroPython documentation (for ESP8266)](http://docs.micropython.org/en/latest/esp8266/)
* [MicroPython documentation (for OpenMV CAM M4/M7)](http://docs.openmv.io/)

Some MicroPython forums :
* [MicroPython forum (for Pyboard, WiPy 1, ESP8266, ESP32, BBC Micro:bit)](https://forum.micropython.org/)
* [Pycom MicroPython forum (for WiPy 2, LoPy/LoPy, SiPy, GPy, FiPy boards)](https://forum.pycom.io/)
* [OpenMV CAM MicroPython forum (for Open MV CAM M4/M7)](http://forums.openmv.io/)

### Using real MicroPython boards on MicroPython sprint

What is need to use MicroPython boards ?
- bring your computer and (if possible) a USB-microUSB cable (many will be available in the MicroPython sprint);
- follow [MicroPython Tutorial_Software_Instructions](https://github.com/rcolistete/MicroPython_Tutorial_SciPy_2018/blob/master/1_Tutorial_Software_Instructions/Tutorial_setup_instructions.ipynb) for software setup instructions on LoPy4/LoPy/WiPy2;
 - follow the documentation above about your preferred MicroPython board to setup the software tools (Mu Editor for BBC Micro:bit, etc).

### Available hardware

The MicroPython sprint has the following microcontroller boards available :
* 19 LoPy/LoPy4 (LoRa, Sigfox, WiFi, Bluetooth);
* 2 LoPy (LoRa, WiFi, Bluetooth);
* 1 WiPy 2 (WiFi, Bluetooth);
* 3 BBC Micro:bit (Bluetooth);
* 2 Pyboards;
* 10 ESP8266/WeMos D1 Mini (WiFi);
* 1 OpenMV CAM M7 (buit-in camera).

Also almost 100 sensors and actuators are available like BME280 (pressure, humidity, temperature), MPU6050 (accelerometer, gyroscope), SI1145 (ultraviolet, visible and infrared light), etc, as well small displays.
