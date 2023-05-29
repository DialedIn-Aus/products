# Tasmota

### Templates

Template for ESP32-C3
```JSON
{"NAME":"Open Sense","GPIO":[4865,4864,1312,640,1,1,1,1,1376,32,608,0,0,0,0,0,0,0,0,0,3232,3200],"FLAG":0,"BASE":1}
```

Template for ESP8266
```
TBC
```
### MQTT

MQTT must be configured to point to your MQTT broker, so that Home Assistant or your choosen automation platform can discover the device.

### Tasmota Settings

`Teleperiod` controls how often Tasmota will send MQTT messages with sensor updates.Default interval is 300 seconds but can be set between 10 and 3600, you can adjust in Tasmota console to send updates more often

```python
TelePeriod 30
```

`TempRes` controls the resolution (number of decimal places) of temperature values for all sensors connected to Tasmota. The default `TempRes` is `1` which we recommend for most sensors, however if you require more precision you can adjust in console.

```python
TempRes 2
```

`ADC` need to be [range calibrated](https://tasmota.github.io/docs/ADC/#commands), for example 5" eTape: [not tested]
```python
AdcParam1 6 300 663 125  25
```

### Matter
Matter support in Tasmota is currently at experimental status. It will allow you to use your device directly with Alexa/Google Home/HomeKit without requiring Home Assistant.

If you are using the Dialedin Firmware, Matter support is included in the build, but will be disabled by default. You can enable Matter with

```python
SetOption151 1
```
