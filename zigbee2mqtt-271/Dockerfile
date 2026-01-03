FROM ghcr.io/home-assistant/base:latest

# Node.js installieren
RUN apk add --no-cache nodejs npm

# Zigbee2MQTT installieren (exakte Version)
RUN npm install -g zigbee2mqtt@2.7.1

# Datenpfad setzen
ENV ZIGBEE2MQTT_DATA=/config/zigbee2mqtt

CMD ["zigbee2mqtt"]

