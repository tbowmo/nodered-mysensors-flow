home_automation
===============

Home automation flows

### About

Control flows for a MySensors home automation setup in nodered, using the following items:

mosquitto
influxdb
grafana
chromecast control (python script)

Currently I'm using a mySensors serial gateway, so the first flows on the Mysensors subflow, is converting the serial gateway to MQTT and back again

the rest is running with mqtt as transport layer for all the different parts of the system
