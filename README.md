![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/%5B%20Multi%20%5D%20-%20Laser%20PM%202.5%20Sensor.jpg?raw=true)

# Laser-PM-2.5-Sensor
**The Grove – Laser PM2.5 Sensor (HM3301)** is a new-generation laser dust sensor designed for real-time and continuous monitoring of airborne particles. Unlike traditional sensors that use air pumps, the HM3301 uses built-in fan blades to draw air into the detection chamber, ensuring stable measurements with low noise and ultra-low power consumption. It works based on the Mie scattering principle, where particles scatter light from a laser source. This scattered light is collected by a photosensitive diode, amplified, and analyzed with an advanced algorithm to determine particle count and mass concentration. Its high sensitivity allows detection of particles as small as 0.3 µm, making it highly reliable for indoor air quality monitoring and environmental applications.

## This sensor is suitable for:
- Smart air purifiers and intelligent air conditioners
- Air quality monitoring equipment
- Industrial PM2.5 and PM10 analysis
- Dust and smoke detection systems
- Real-time PM2.5, PM10, and TSP detectors
- Environmental testing stations
- Smart ventilation and HVAC systems

## Specifications
|Parameter|Value|
|-|-|
|**Model**|Grove – Laser PM2.5 Sensor (HM3301)|
|**Operating Voltage**|3.3 V / 5 V|
|**Operating Temperature**|–10 °C to 60 °C|
|**Operating Humidity**|10% – 90% RH (non-condensing)|
|**Detection Particle Size**|3 channels: 2.5 µm, 5 µm, 10 µm|
|**Measurement Range (PM2.5)**|1 – 500 µg/m³ (effective), up to 1000 µg/m³ (maximum)|
|**Resolution**|1 µg/m³|
|**Counting Concentration**|1 s / 0.1 L|
|**Stability Time**|30 s after power-on|
|**Interface**|I²C|
|**Features**|Real-time detection, high sensitivity, laser light scattering technology, low noise, ultra-low power|

![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/Example%20code.png?raw=true){{{width="250" height="auto"}}} 
[**Download the working code here**](https://code.gogoboard.org/#/program/368a4709-621f-4e75-b2ba-6d46cd737f01)

## Block Code Reference
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%205.png?raw=true){{{width="100" height="auto"}}}| Use this block to read the PM1.0 concentration (μg/m³) from the sensor.|
|-|-|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%204.png?raw=true){{{width="110" height="auto"}}}|**Use this block to read the PM2.5 concentration (μg/m³) from the sensor.**|
|![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%206.png?raw=true){{{width="100" height="auto"}}}|**Use this block to read the PM10 concentration (μg/m³) from the sensor.**|

## **Required Equipment**
|Air Pressure Sensor|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/pm2.5.png?raw=true){{{width="200" height="auto"}}}|
|-|-|
|**Grove cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/only%20grove%20(test).png?raw=true){{{width="200" height="auto"}}}|
|**Computer or Tablet**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/computer%20or%20tablet.png?raw=true){{{width="200" height="auto"}}}|
|**GoGo Board and USB-C cable**|![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/Ultrasonic%20Sensor/gogoboard%20and%20usb.png?raw=true){{{width="200" height="auto"}}}|

## **How to use**
**1. Connect the GoGo Board**
- Connect the GoGo Board to your computer or tablet via USB-C cable or Wi-Fi
![](https://github.com/thegogoboard/gogodoc/blob/main/Automation/Image%20(91).jpg?raw=true){{{width="500" height="auto"}}}

**2. Connect the Grove Laser PM2.5 Sensor**
- Connect the Grove Laser PM2.5 Sensor to a Grove cable, then plug it into the purple Multi Port on the GoGo Board.
![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM.gif?raw=true){{{width="500" height="auto"}}} ![Description](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/pm2.5%20with%20board%20(bright%20version).png?raw=true){{{width="400" height="auto"}}}

## Getting Started with the Grove Laser PM2.5 Sensor on GoGo Code 

**1. Visit the GoGo Code website:**
- Go to [GoGo Code](https://code.gogoboard.org/#/program) to start programming and controlling your device.

**2. Add the Grove Laser PM 2.5 Sensor extension:**
- Click on the **Add Extension** category

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%201.gif?raw=true){{{width="1000" height="auto"}}}

- Select **Official**, then click the **[ Multi ] - Laser PM 2.5 Sensor** card. The system will automatically return to the main page.

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%202.gif?raw=true){{{width="1000" height="auto"}}}

**3. Add sensor command blocks:**
- Click on the **[ Multi ] - Laser PM 2.5 Sensor** category. You will see two available blocks:

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%203.gif?raw=true){{{width="1000" height="auto"}}}

**4. Write a simple program to display sensor data:**
- Use the **show number** block from the **Built-in Display** category and place it inside the start block.
- Insert the **"PM 2.5 (µg/m³)"** block into the show number block.
- To display the value continuously, place everything inside the **“forever do each time wait…”** block from the **Loops** category. You can also set how often the value is updated (e.g., every 1 second).

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%207.png?raw=true5){{{width="500" height="auto"}}}

**5. Download and test your code:**
- Click **Download**, then click **Run Code** to start running your program

![](https://github.com/bigbangcmu/bigbang/blob/bigbangcmu/PM2.5/PM%20code%208.gif?raw=true){{{width="1000" height="auto"}}}

::: details Additional information
  **Buy online** [PM2.5 Sensor](https://th.cytron.io/p-grove-laser-pm2p5-dust-sensor-hm3301)
  
  **Cautions**
- Avoid modifying wires or connecting them incorrectly, as this may damage the device.
- Do not touch the sensor head while it is operating, as it may affect detection accuracy.
- If the sensor does not work, check the voltage and wiring connections.
:::
