# iot-kit-hello-world
🌏世界の情報を集めて表示するデモ

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

```bash
MQTT_TARGET_NAME=CITY \
MQTT_NAME=hoge \
MQTT_HOST=soldier.cloudmqtt.com \
MQTT_USER=fsehnfkb \
MQTT_PASSWORD=NEPtNke-75gx \
MQTT_PORT=15610 \
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

```bash
MQTT_NAME=CITY \
MQTT_HOST=soldier.cloudmqtt.com \
MQTT_USER=fsehnfkb \
MQTT_PASSWORD=NEPtNke-75gx \
MQTT_PORT=15610 \
OPENWEATHER_API_KEY=ed257be33b1cc25c39837b9a30336171 \
python3 unicorn2/main.py
```
