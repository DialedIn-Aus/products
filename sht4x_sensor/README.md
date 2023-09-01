# Dialedin - SHT40 Temperature Sensor (SHT4x)
A uniquely compact and high precision temperature sensor, built around the advanced Sensirion SHT40 temperature and humidity sensor technology. This sensor offers seamless integration through direct plug-and-play compatibility with StemmaQT or QWIIC  I2C setups. Boasting an impressive 16-bit resolution, it ensures exceptional accuracy, generating readings with a remarkable 0.2°C precision.

This is the 4th generation of SHT sensors from Sensirion. It keeps all the features from the previous generation, while being in a more compact package. It offers excellent accuracy of ±0.2°C for temperature and ±1.8% relative humidity (from 20% to 80% RH). One of the new featuers that has been added in this series is an internal heater that will improve the accuracy and performance when operating in humid environments.

Compatible with all popular embedded platforms such as Arduino, ESPHome, Tasmota and more. Will also happily integrate with any other microcontroller supporting I2C communication, making it an ideal choice for a wide range of applications.

<p align="middle">
    <img src="images/DI-SHT40.jpg" alt="sht4x product image" width="200px">
</p>


### Specifications

* Sensor: SHT40
* I2C Addr: 0x44
* Connector: StemmaQT / QWIIC
* Supply Voltage: 3.0V - 3.6V
* Temperature Range: -40°C to 125°C
* Temperature Accuracy: ±0.2°C (Typical)
* Humidity Range: 0% to 100% RH (Relative Humidity)
* Humidity Accuracy: ±1.8% RH (Typical) in the 20% to 80% RH range
* Dimensions: 8mm x 14.5mm x 5mm


### Links
[SHT40 Datasheet](https://sensirion.com/media/documents/33FD6951/63E1087C/Datasheet_SHT4x_1.pdf)  
[ESPEasy Plugin](https://espeasy.readthedocs.io/en/latest/Plugin/P153.html)   
[ESPHome Component](https://esphome.io/components/sensor/sht4x.html)