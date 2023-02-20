# Lytko ESPHome Configurations

This repository contains ESPHome configurations for [Lytko](https://lytko.com) devices. Pick a configuration / pre-built firmware which corresponds to your device. Please make sure ESPHome 2022.9.0 or newer is used in case you need to recompile the firmware (yes, that's exactly how you'll use it).

Refer to the [installation manual (RUS)](/docs/installation.rus.md) to convert your Lytko device into a ESPHome based one.

## Lytko 101 Headless Thermostat

![Photo of Lytko 101 headless](/picts/lytko101hl.png?raw=true "Lytko 101 headless")

[[YAML configuration file]](/lytko-101-headless.yaml) [[Prebuilt firmware]](../../tree/gh-pages/lytko101-hl-esp8266/lytko101-hl-esp8266.bin)

## Lytko 101 Thermostat

![Photo of Lytko 101 while](/picts/lytko101w.png?raw=true "Lytko 101 while")
![Photo of Lytko 101 black](/picts/lytko101b.png?raw=true "Lytko 101 black")

Need to take the screen off and check the PCB. The difference is in the way how screen is connected.

### Lytko 101 version 1
![Photo of Lytko 101 v1 PCB](/picts/lytko101v1_pcb.jpg?raw=true "Lytko 101 v1 PCB")

[[YAML configuration file]](/lytko-101-v1.yaml) [[Prebuilt firmware]](../../tree/gh-pages/lytko101v1-esp8266/lytko101v1-esp8266.bin)

### Lytko 101 version 2
![Photo of Lytko 101 v2 PCB](/picts/lytko101v2_pcb.jpg?raw=true "Lytko 101 v2 PCB")

[[YAML configuration file]](/lytko-101-v2.yaml) [[Prebuilt firmware]](../../tree/gh-pages/lytko101v2-esp8266/lytko101v2-esp8266.bin)

### Lytko 101 version 3
![Photo of Lytko 101 v2 PCB](/picts/lytko101v3_pcb.jpg?raw=true "Lytko 101 v3 PCB")

ESPHome based open source firmware is coming late 2022 - early 2023. I haven't seen these devices yet.

## Lytko 101+ Thermostat

![Photo of Lytko 101+](/picts/lytko101plus.png?raw=true "Lytko 101+")

ESPHome based open source firmware is coming late 2022 - early 2023. Screen is a bottleneck. Please file an issue if you are interested in a version without screen but sooner. 
