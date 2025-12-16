# SensePuck: The Addon Board for the Seeed Round Display


<p align="center"> 
<img src="./Images/Front.jpg">
</p>



<p align="center"> 
<img src="./Images/Back.jpg" width="600" height="400"/>
</p>

 <p align="center"> 
<img src="./Images/Front2.jpg" width="600" height="400"/>
</p>

## Features:

1. **2xAudioAmplifier MAX98357**: Listen to your favourite Tunes with an Audio Amplifier

2. **SI4735 with Digital and Analog Audio**: Listen to AM/FM Radio

3. **SI4732 with Analog Audio**: Listen to AM/FM Radio

4.  **Heltec Lora HT-CT62 **: For Recieving and Transmittng LoRa, Meshtastic, TheThingsNetwork, Meshcore

5.  SI5351 VCO Generator, 3 Outputs to 160MHz 

6. **I2C Connector for Sensor**: Connect your favourite I2C Sensor board with the embedded 2.54mm connector

7. **Wireless Control**: Untehther your development process with the wireless capabilities. With WiFi and BLE, this tool allows remote control and data logging. Users can adjust settings and monitor data from a distance, offering a more flexible development experience.

8. USB-C Connector for Debuggung and Power Supply

9. **LSM6 Gyro+ACC**: Check Movements, Steps Pedometer

5. **Open Source & Programmable**: As an open-source device, the Device offers unmatched versatility. It is fully programmable, allowing you to tailor its functionality to your specific applications. This customization extends to software and hardware, opening up endless possibilities for creative and efficient project development.

6. **Compact Design**: Designed for convenience, the LoRaCam Board compact and sleek form factor allows for seamless integration into existing setups. Its compatibility with USB PD power sources and inline integration capability minimizes the need for additional equipment or extensive redesign, making it a versatile and user-friendly addition to any development environment.

7. **Display+Touchscreeen**: Monitor live the current status on an 1.8" or 1.28" LCD Touch Display

8. **RTC**: RealTimeClock RV3032 Temp Compensated for RealTime Clock

9. Extension Modules - Compatible to Seeed Sensors and Displays
<p align="center"> 
<img src="./Images/Display.jpg" width="400" height="400"/>
</p>

9. **RGB LED**: Status LED

10. **Battery Charger** Use the Battery Charger on the Seeed Display

11. **Rotary Encoder** Perfect for switching the Radio Station

12.  BME680: Measure Temperature, Humidity, Air Pressure, TVOC, eCO² (might update to BME688 or BME690 soon)
    
## Specifications

<p align="center"> 
<img src="./Images/Schematic.jpg">
</p>

<p align="center"> 
<img src="./Images/PCB_TOP.jpg" width="400" height="400"/>
</p>

<p align="center"> 
<img src="./Images/Housing.jpg" width="400" height="400"/>
</p>

<p align="center"> 
<img src="./Images/PCB_BOTTOM.jpg" width="400" height="400"/>
</p>


Needed Libaries:

https://github.com/schreibfaul1/ESP32-audioI2S
https://github.com/pololu/lis3mdl-arduino
https://github.com/pololu/lsm6-arduino
https://github.com/Seeed-Projects/SeeedStudio_TFT_eSPI
https://github.com/Seeed-Projects/SeeedStudio_lvgl
https://github.com/Seeed-Studio/Seeed_Arduino_RoundDisplay

### Key Features:


### Future Developments:

AI Detection of objects, radio Signal and determine if the device shall sent the data via LoRa 

## Testing for Performance

At the heart of SensePuck's design is a commitment to reliability and performance. To ensure that SensePuck stands up to real-world demands, we subjected it to testing under use conditions.


## License

MIT License

Copyright (c) 2025 blue2monster

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
