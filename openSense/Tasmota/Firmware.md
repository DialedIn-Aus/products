### Custom Firmware Build
The firmware images in this [folder](firmware) are built with the following options enabled:  

Base image: `tasmota32c3cdc`  

Additional configuration:  
```C++
  #define USE_DISPLAY
  #define USE_DISPLAY_SSD1306 
  #define USE_DISPLAY_SH1106

  #define USER_TEMPLATE     "{\"NAME\":\"Open Sense\",\"GPIO\": 
    [4865,4864,1312,640,1,1,1,1,1376,32,608,0,0,0,0,0,0,0,0,0,1,1],\"FLAG\":0,\"BASE\":1}"

```