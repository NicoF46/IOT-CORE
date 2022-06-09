# IOT-CORE Proyecto IOT Funes Pablo Nicolas

## Mosquitto MQTT
- Broker mosquitto mqtt, carpetas config, data y logs
- Comandos utiles para testear.

mosquitto_sub -h 192.168.0.218 -t topic -p 8883 --cafile ca.crt --tls-version tlsv1.2  -u nico -P nico93 -dmosquitto_sub -h 192.168.0.218 -t topic -u nico -P nico93 -d

mosquitto_pub -h 192.168.0.218 -t topic -m 'hola' -p 8883 --cafile ca.crt --tls-version tlsv1.2  -u nico -P nico93 -d