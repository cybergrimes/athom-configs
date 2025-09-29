# Only applicable to ESP8285,[Please click for ESP32 devices](https://github.com/athom-tech/esp32-configs)

### Athom ESPHome configurations

This repository contains a bunch of ESPHome configurations for https://athom.tech devices.

If you are prompted that there is not enough space, you should upgrade `ESP8266_MINI.bin` first

- mini is a transit firmware, after running, it will generate a hotspot of "ESP_UPDATE_XXXXXX"
- Connect to the hotspot and visit `http://192.168.4.1/update` in the browser
- Upload updated ESPHome firmware

### Migrating to Tasmota

- Select firmware upgrade, upload `tasmota.bin.gz` and click Update, ***Please don't choose `tasmota.bin`***
- Download Tasmota firmware here http://ota.tasmota.com/tasmota/release/tasmota.bin.gz

### Migrating from Tasmota

- First execute `SetOption78 1` in the console of Tasmota
- Select firmware upgrade, upload `tasmota-minimal.bin.gz` and click start upgrade
- Select the firmware upgrade again, upload the firmware of ESPHome and click to start upgrade

### Device List
device|picture|file name|notice
:---:|:---:|:---:|:---:
Athom_Presence_Sensor|<img src="/images/Athom_Presence_Sensor.png" width="50%" height="40%">|athom-presence-sensor.yaml
Athom_Garage_Door_Opener|<img src="/images/Athom_Garage_Door_Opener.png" width="50%" height="20%">|athom-garage-door.yaml|<h4>Discontinued</h4>
