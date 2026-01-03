FROM ghcr.io/home-assistant/amd64-base:latest

# Node.js installieren
RUN apk add --no-cache nodejs npm

# Zigbee2MQTT installieren (exakte Version)
RUN npm install -g zigbee2mqtt@2.7.1

# Datenpfad setzen
ENV ZIGBEE2MQTT_DATA=/config/zigbee2mqtt

# Startkommando
CMD ["zigbee2mqtt"]
