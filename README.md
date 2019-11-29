# iot-kit-hello-world

🌏世界の情報を集めて表示するデモ

## To Implement

* [x] Touch pHAT - send message
* [ ] UnicornHAT 0 - country flag 🇬🇧 
* [ ] UnicornHAT 1 - time and temperature 🌡 
* [x] UnicornHAT 2 - weather icon ⛅️ 
* [ ] Enviro pHAT - send environment data
* [ ] VoiceKit - speak country information

## Demo

### touchp

Touch pHATのデモ

```bash
MQTT_TARGET_NAME=CITY \
MQTT_NAME=hoge \
MQTT_HOST=***.cloudmqtt.com \
MQTT_USER=aaa \
MQTT_PASSWORD=bbb \
MQTT_PORT=10185 \
python3 touchp/main.py
```

### unicorn2

世界の天気を表示する

```bash
MQTT_NAME=CITY \
MQTT_HOST=***.cloudmqtt.com \
MQTT_USER=aaa \
MQTT_PASSWORD=bbb \
MQTT_PORT=15610 \
OPENWEATHER_API_KEY=****** \
python3 unicorn2/main.py
```

## Install

### touchp

```bash
$ sudo apt update && sudo apt upgrade -y
$ sudo pip3 install touchphat
$ sudo apt install python3 python3-pip python3-smbus -y
$ sudo apt install i2c-tools -y
```

### unicorn2

```bash
$ sudo raspi-config
# enable SPI Interface
$ sudo pip3 install unicornhathd
```
