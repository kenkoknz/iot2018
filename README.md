# iot2018
I have been toying with iot for a while. I still remenber internet switch I designed years ago with direct access from the net. 
Fast forward to 2018 things progreses a lot and currently esp8266 with its variants like wemos and node mcus and the raspi are in vogue now.
Software wise I am more incline to flow programming and also Android devlopment platform like MIT app inventor.

Project 1
Raspi pi3 running node red
Run script to update to latest node red and node.js, this will enable the pallett which will make additional node installation a lot easier
Install Nodes:
node-red-node-arduino; load firmata and you have analog inputs for the pi
node-red-dashboard
node-red-contrib-sensor-ds18b20; remember to set 1 wir to on in raspi config
node-red-node-dweetio
node-red-contrib-thingspeak

use ds18b20 node to dweet and freeboard to display temperature
use ds18b20 node to dweet and thingspeak to display temperature


ref:
https://www.bigmessowires.com/2017/06/29/esp8266-freeboard-io-blynk-and-iot/
