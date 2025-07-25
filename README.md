# LVGL ESPhome Guition ESP32-S3-4848S040 custom firmware

<p align="center">
 <img width="200px" src="/doc/img/screen1.png">
 <img width="200px" src="/doc/img/screen2.png">
 <img width="200px" src="/doc/img/screen3.png">
 <img width="200px" src="/doc/img/screen4.png">
 <img width="200px" src="/doc/img/screen5.png">
 <img width="200px" src="/doc/img/screen6.png">
 <img width="200px" src="/doc/img/screen7.png">
 <img width="200px" src="/doc/img/screen8.png">
 <img width="200px" src="/doc/img/screen9.png">
 <img width="200px" src="/doc/img/screen10.png">
 <img width="200px" src="/doc/img/screen12.png">
</p>

<p align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/made%20by-alaltitov-blue">
    <img alt="Static Badge" src="https://img.shields.io/badge/version-v1.0%20Beta-green">
    <img alt="Static Badge" src="https://img.shields.io/badge/esphome min version-2025.5.2-red">
    <img alt="Static Badge" src="https://img.shields.io/badge/license-MIT-orange">
</p>

## ✨ Features

- Status indicators for Wi-Fi, Home Assistant, thermostat, air conditioner, touchscreen lock, alarm panel
- Weather icons with current conditions and temperature
- Date and time
- Sensor readings from Home Assistant
- Thermostat control with built-in display relay
- Air Conditioner control with built-in display relay
- Vacuum control
- Shutter control
- Media player control
- Control of lights
- Alarm panel
- Settings:
  * Backlight adjustment
  * Screen timeout settings
  * Language selection for states (ru, en, pl, pt, fr, es, de, it, us)

## 📦 Installation
> [!WARNING]
> All versions ESPHome firmware now available!!! (Big thanks [сlydebarrow](https://github.com/clydebarrow) ).

> 📹 **Video [instruction](https://youtu.be/HYN_2hvcbes?si=JfYQH4vCuFlr8Q9r)**

<img width="400px" src="/doc/img/screen11.png">

- You must enable the "Allow the device to perform Home Assistant actions." option in the ESPHome integration to Home Assistant to control devices.
- Install custom component for translations and covers for media player from [here](https://github.com/alaltitov/homeassistant-display-tools).
- Copy repository to vscode or to esphome folder of your Home Assistant. Change in substitutions your entities in all widgets (only in substitution, in code everything will be substituted automatically).

## 🐛 Known Issues
- The weather status text does not change depending on day/night, only the picture
- When the connection with the API is lost/reboot, the screen lock state is not restored

## ⚠️ Important Notice
- Regarding shutter and vacuum widgets: Testing was conducted on demo entities (as I don't have real devices), so errors may occur when working with real entities. Feedback is welcome! 🙏

## 📖 Documentation

- https://esphome.io/components/lvgl/

## 🤝 Thanks for your help

- Thanks, [сlydebarrow](https://github.com/clydebarrow), [jesserockz](https://github.com/jesserockz), [ssieb](https://github.com/ssieb) for helping me with the project!

## 💝 Support the Project
This project was made in my free time and if it was useful to you, you can support me if you find it necessary 😊:

**ETH/USDT (ERC-20):** `0x9fF0E16a58229bEcdFDf47d9759f20bE77356994`

Or just put ⭐ Thank you
