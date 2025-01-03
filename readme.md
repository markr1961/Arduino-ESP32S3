## ESP32-S3-N16R8
Connecting....  
Chip is ESP32-S3 (revision v0.2)  
Features: WiFi, BLE  
Crystal is 40MHz  
MAC: 98:3d:ae:e6:9d:54  

## hardware
closest to a [ESP32-S3-DevKitC-1-N16R8V](https://docs.espressif.com/projects/esp-dev-kits/en/latest/esp32s3/esp32-s3-devkitc-1/index.html)
Module: ESP32-S3-WROOM-2-N16R8V  
Boot: GPIO0
RGB LED, driven by GPIO48. (or maybe 38)

## Note:
Serial.printf is routed to USB OTG port, not COM/upload port. Essentially need both connected to upload _and_ use serial.
