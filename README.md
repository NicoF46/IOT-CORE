# IOT-CORE Proyecto IOT Funes Pablo Nicolas

## Mosquitto MQTT
- Broker mosquitto mqtt, carpetas config, data y logs
- Comandos utiles para testear.

mosquitto_pub -h 192.168.0.218 -t topic -m 'hola' -u nico -P nico93 -d
mosquitto_sub -h 192.168.0.218 -t topic -u nico -P nico93 -d
