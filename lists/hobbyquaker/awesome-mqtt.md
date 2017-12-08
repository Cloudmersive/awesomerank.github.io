---
layout: default
title: Awesome Rank for hobbyquaker/awesome-mqtt
---

<p align="center">
	This list is a copy of <a href="https://github.com/hobbyquaker/awesome-mqtt">hobbyquaker/awesome-mqtt</a> with ranks
</p>
---
# Awesome MQTT 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★69735](https://github.com/sindresorhus/awesome)

> A curated list of MQTT related stuff.

MQTT is a lightweight client-server publish/subscribe messaging protocol, optimized for high-latency or unreliable networks. This protocol is a good choice for Internet of Things applications, Telemetry, Sensor Networks, Smart Metering, Home Automation, Messaging and Notification Services.   

## Contents

- [Community Resources](#community-resources)
- [Broker](#broker)
- [Tools](#tools)
- [Clients](#clients)
- [Scripting](#scripting)
- [Interfaces](#interfaces)
    - [Makers](#makers)
    - [Industry](#industry)
    - [Telephony, PBX](#telephony-pbx)
    - [Operating System](#operating-system)
    - [Monitoring](#monitoring)
    - [Location Tracking](#location-tracking)
    - [Logging](#logging)
    - [Smart Home Hardware Interfaces](#smart-home-hardware-interfaces)
    - [Smart Home Integration Software](#smart-home-integration-software)
    - [Lighting](#lighting)
    - [Home Entertainment](#home-entertainment)
    - [Smart Metering](#smart-metering)
    - [Messaging](#messaging)
    - [Misc](#misc)
- [Visualization, Dashboards](#visualization-dashboards)
- [Architecture, Convention](#architecture-convention)    


### Community Resources

* [mqtt.org](http://mqtt.org/).
* [MQTT community wiki](https://github.com/mqtt/mqtt.github.io/wiki).
* [Google Groups: MQTT](https://groups.google.com/forum/#!forum/mqtt).
* [IRC channel #mqtt on the freenode network](irc://irc.freenode.net/mqtt).
* [A list of public brokers](http://moxd.io/2015/10/17/public-mqtt-brokers/).

#### Blogs

* [Ben Hardill](https://www.hardill.me.uk/wordpress/tag/mqtt/)
* [Dominik Obermaier](http://forkbomb-blog.de/category/mqtt)
* [Jan-Piet Mens](http://jpmens.net/)
* [Nick O'Leary](https://knolleary.net/)


### Broker

* [ActiveMQ](http://activemq.apache.org/) - A fast Java multiprotocol messaging and Integration Patterns server.
* [eMQTT](http://emqtt.io/) - The Massively Scalable MQTT Broker written in Erlang/OTP.
* [esp_uMQTT_broker ★40](https://github.com/martin-ger/esp_mqtt) - A basic MQTT Broker on the ESP8266.
* [hbmqtt ★246](https://github.com/beerfactory/hbmqtt) - Python MQTT broker using asyncio.
* [hrotti ★86](https://github.com/alsm/hrotti) - A MQTT broker written in Go.
* [HiveMQ](https://www.hivemq.com/) - Java based commercial MQTT Broker.
* [Moquette ★749](https://github.com/andsel/moquette) - Java MQTT lightweight broker.
* [Mosca](http://www.mosca.io/) - Mosca is a node.js MQTT broker, which can be used Standalone or Embedded in another Node.js application.
* [Mosquitto](http://mosquitto.org/) - "The" Open Source MQTT Broker.
* [RabbitMQ](https://www.rabbitmq.com/mqtt.html) - RabbitMQ offers a MQTT Adapter.
* [SurgeMQ](http://zhen.org/categories/surgemq/) - High Performance MQTT Server and Client Libraries in Go.
* [VerneMQ](https://vernemq.com/) - an Apache2 licensed distributed MQTT broker, developed in Erlang.
* [Vert.x MQTT ★47](https://github.com/vert-x3/vertx-mqtt) - Vert.x component to handle connections, communication and messages exchange with remote MQTT clients.


### Tools

* [imqtt ★17 ⏳1Y](https://github.com/shafreeck/imqtt) - Interactive MQTT packet manipulation shell based on IPython.
* [mqtt-admin ★49](https://github.com/hobbyquaker/mqtt-admin) - Web based MQTT frontend. [Direct Link](https://hobbyquaker.github.io/mqtt-admin/).
* [mqtt-benchmark ★113 ⏳5Y](https://github.com/chirino/mqtt-benchmark) - A benchmarking tool for MQTT Servers.
* [mqttcli ★53 ⏳1Y](https://github.com/shirou/mqttcli) - MQTT Client for shell scripting.
* [mqtt-forget ★0](https://github.com/hobbyquaker/mqtt-forget) - Command line tool to remove retained MQTT topics by wildcard.
* [mqtt-fuzz ★33 ⏳2Y](https://github.com/F-Secure/mqtt_fuzz) - A simple fuzzer for the MQTT protocol.
* [MQTT.fx](http://mqttfx.jfx4ee.org/) - MQTT.fx is a MQTT Client written in Java based on Eclipse Paho. Supports scripting.
* [MQTTInspector ★54](https://github.com/ckrey/MQTTInspector) - A general MQTT testing app for iOS (iPhone and iPad).
* [MQTTLens](https://chrome.google.com/webstore/detail/mqttlens/hemojaaeigabkbcookmlgmdigohjobjm) - A Google Chrome application, which connects to a MQTT broker and is able to subscribe and publish to MQTT topics.
* [mqtt-malaria ★169 ⏳1Y](https://github.com/remakeelectric/mqtt-malaria) - scalability and load testing utilities for MQTT environments.
* [mqtt-spy](http://kamilfb.github.io/mqtt-spy/) - Java based MQTT frontend. Supports scripting.
* [mqtt-utils ★7 ⏳4Y](https://github.com/dsell/mqtt-utils) - A collection of MQTT utilities.
* [mqtt-wall ★17](https://github.com/bastlirna/mqtt-wall) - Subscription only web-based client – like Twitter wall for MQTT.
* [mqtt-wildcard ★6](https://github.com/hobbyquaker/mqtt-wildcard) - Node.js Module to match a MQTT Topic against wildcards.
* [Python MQTT Client Shell ★13](https://github.com/bapowell/python-mqtt-client-shell) - a text console-based, interactive shell for exercising various tasks associated with MQTT client communications.
* [Wireshark-MQTT ★60 ⏳2Y](https://github.com/menudoproblema/Wireshark-MQTT) - MQTT dissector for Wireshark.

### Clients

* [CocoaMQTT ★567](https://github.com/emqtt/CocoaMQTT) - MQTT for iOS and OS X written with Swift.
* [emqttc ★99](https://github.com/emqtt/emqttc) - Asynchronous Erlang MQTT Client.
* [Moscapsule ★177](https://github.com/flightonary/Moscapsule) - MQTT Client for iOS written in Swift.
* [hbmqtt ★246](https://github.com/beerfactory/hbmqtt) - Python MQTT client using asyncio.
* [Hulaaki ★88](https://github.com/suvash/hulaaki) - An Elixir library for clients communicating with MQTT brokers.
* [Machine Head ★47](https://github.com/clojurewerkz/machine_head) - A Clojure MQTT Client.
* [M2Mqtt](https://m2mqtt.wordpress.com/) - A MQTT client available for all .Net platforms (.Net Framework, .Net Compact Framework and .Net Micro Framework) and WinRT platforms (Windows 8.1, Windows Phone 8.1 and Windows 10).
* [Mosquitto-PHP ★224](https://github.com/mgdm/Mosquitto-PHP) - A wrapper for the Mosquitto MQTT client library for PHP.
* [mqtt-client ★11 ⏳2Y](https://github.com/centamiv/mqtt-client) - A Polymer Web Component that implements a MQTT client (uses Paho mqttws31.js).
* [MQTT-Client-Framework ★786](https://github.com/novastone-media/MQTT-Client-Framework) - iOS, OSX, tvOS native ObjectiveC MQTT Client Framework.
* [mqtt.dart ★11](https://github.com/jnguillerme/mqtt.dart) - Dart mqtt client.
* [mqtt-elements ★21 ⏳1Y](https://github.com/mqttjs/mqtt-elements) - Polymer elements for MQTT.
* [mqttex ★41 ⏳2Y](https://github.com/alfert/mqttex) - MQTT implementation in Elixir.
* [MQTTKit ★375 ⏳1Y](https://github.com/mobile-web-messaging/MQTTKit) - MQTT Objective-C client for iOS.
* [mqtt_cpp ★37](https://github.com/redboltz/mqtt_cpp) - MQTT client for C++14 based on Boost.Asio.
* [mqtt_lua](http://geekscape.github.io/mqtt_lua/) - MQTT Client library for the Lua language.
* [MQTT.js](https://github.com/mqttjs) - MQTT client for Node.js.
* [mqtt-rs ★32](https://github.com/zonyitoo/mqtt-rs) - MQTT protocol library for Rust.
* [Paho](http://www.eclipse.org/paho/) - Open source client implementations (C/C++, Java, Python, Javascript, Go, C#).
* [pubsubclient ★1420](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [rumqtt ★31](https://github.com/AtherEnergy/rumqtt) - A fast, lock free pure rust MQTT client.
* [ruby-mqtt ★300](https://github.com/njh/ruby-mqtt) - Pure Ruby gem that implements the MQTT protocol.
* [tcl-mqtt ★2 ⏳3Y](https://github.com/Tingenek/tcl-mqtt) - Small library to connect to a MQTT broker. Very, very basic.
* [TMQTTClient](http://jamiei.com/blog/code/mqtt-client-library-for-delphi/) - MQTT Client Library for Delphi.
* [Vert.x MQTT ★47](https://github.com/vert-x3/vertx-mqtt) - Vert.x component that provides methods for connecting/disconnecting to a broker, publishing messages and subscribing to topics.
* [wolfMQTT](https://www.wolfssl.com/products/wolfmqtt/) - A client implementation of the MQTT written in C for embedded use. It supports SSL/TLS via the wolfSSL library.


### Scripting

* [logic4mqtt ★9 ⏳1Y](https://github.com/owagner/logic4mqtt) - Java based Logic and scripting engine for use with MQTT. Uses Java's general scripting interface, so scripts can be written in a multitude of languages like Javascript, Groovy etc.
* [mqtt-scripts ★12](https://github.com/hobbyquaker/mqtt-scripts) - Node.js based script runner.
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things.


### Interfaces

#### Makers

* [arduinoTemps2mqtt ★8 ⏳2Y](https://github.com/matbor/arduinoTemps2mqtt) - Arduino sketch, grab One-wire Temperature's and publish to a MQTT broker.
* [esp_mqtt ★786](https://github.com/tuanpmt/esp_mqtt) - MQTT client library for ESP8266.
* [mqtt-ir-transceiver ★47](https://github.com/enc-X/mqtt-ir-transceiver) - ESP8266 based bidirectional gateway between MQTT and IR. Use with PlatformIO.
* [MySensors](https://www.mysensors.org/) - Arduino NRF24L01 based sensor network with support for an MQTT gateway
* [nodemcu-gpiomqtt ★2 ⏳1Y](https://github.com/hobbyquaker/nodemcu-gpiomqtt) - Lua script to connect ESP8266 GPIOs to MQTT.
* [pubsubclient ★1420](https://github.com/knolleary/pubsubclient) - A client library for the Arduino Ethernet Shield that provides support for MQTT.
* [RFM69-MQTT-client ★78](https://github.com/computourist/RFM69-MQTT-client) - Arduino RFM69 based sensors and MQTT gateway.
* [rpi2mqtt ★11](https://github.com/hobbyquaker/rpi2mqtt) - Connect a RaspberryPis GPIOs and 1-Wire Temperature Sensors to MQTT.
* [xbee2mqtt ★16 ⏳1Y](https://github.com/xoseperez/xbee2mqtt) - XBee to MQTT gateway.


#### Industry

* [modbus2mqtt ★35](https://github.com/owagner/modbus2mqtt) - Modbus master which publishes register values via MQTT.
* [mqtt2opcua ★25](https://github.com/nzfarmer1/mqtt2opcua) - Bi Directional MQTT to OPCUA Bridge.


#### Telephony, PBX

* [agi-mqtt ★17 ⏳3Y](https://github.com/zeha/agi-mqtt) - Interface between Asterisk and MQTT.
* [fritz2mqtt ★4](https://github.com/akentner/fritz2mqtt) - Connect FRITZ!Box to MQTT.


#### Operating System

* [mqttlauncher ★36](https://github.com/jpmens/mqtt-launcher) - Execute shell commands triggered by published MQTT messages.
* [mqtt-os-status ★6 ⏳3Y](https://github.com/oskarhagberg/mqtt-os-status) - Operating-system related data, published to an MQTT broker at fixed intervals.
* [mqttpc ★3 ⏳1Y](https://github.com/hobbyquaker/mqttpc) - Control processes via MQTT. Ability to send signals via MQTT and to publish stdout/stderr or pipe MQTT payloads into stdin.
* [mqttwatchdir ★16 ⏳2Y](https://github.com/jpmens/mqtt-watchdir) - Recursively watch a directory for modifications and publish file content to an MQTT broker.
* [psmqtt ★16](https://github.com/eschava/psmqtt) - Utility reporting system health and status via MQTT.
* [WinThing ★10](https://github.com/msiedlarek/winthing) - Remotely control Windows through MQTT.


#### Monitoring

* [check-mqtt ★24](https://github.com/jpmens/check-mqtt) - A Nagios/Icinga plugin for checking connectivity to an MQTT broker.
* [nag2mqtt ★2](https://github.com/DE-IBH/nag2mqtt) - Nagios event broker to MQTT gateway.
* [notify-by-mqtt ★10 ⏳3Y](https://github.com/jpmens/notify-by-mqtt) - A Nagios/Icinga notification module which wraps data into JSON and fires it off to an MQTT broker.


#### Location tracking

* [OwnTracks](http://owntracks.org/) - Location tracking and geofencing for MQTT.


#### Logging

* [mqttcollect ★15 ⏳1Y](https://github.com/jpmens/mqttcollect) - A collectd "Exec" plugin for MQTT.
* [graylog-plugin-mqtt ★7 ⏳1Y](https://github.com/graylog-labs/graylog-plugin-mqtt) - MQTT Input Plugin for Graylog.
* [mqtt2graphite ★49](https://github.com/jpmens/mqtt2graphite) - Subscribe to MQTT topics and push to Graphite's Carbon server.
* [influx4mqtt ★7](https://github.com/hobbyquaker/influx4mqtt) - Subscribe to MQTT topics and insert into InfluxDB.
* [mqtthandler ★6 ⏳1Y](https://github.com/changyuheng/MQTTHandler) - A Python logging handler module for MQTT.


#### Smart Home Hardware Interfaces

* [aqara-mqtt ★45](https://github.com/monster1025/aqara-mqtt) - Aqara (Xiaomi) Gateway to MQTT bridge.
* [cul2mqtt ★1 ⏳1Y](https://github.com/hobbyquaker/cul2mqtt) - Interface between [Busware CUL](http://shop.busware.de/product_info.php/cPath/1/products_id/29) (868MHz RF-Devices like ELV FS20, HMS, EM, ...) and MQTT.
* [domiqtt ★1](https://github.com/etobi/domiqtt) - Connects to a Domiq Base (LCN) and translate from and to MQTT.
* [eno2mqtt ★5 ⏳1Y](https://github.com/owagner/eno2mqtt) - Interface between an Enocean USB300 (TCM310) adapter and MQTT.
* [Evohome2mqtt ★0](https://github.com/svrooij/evohome2mqtt) - MQTT Interface for the Honeywell Evohome system.
* [helios2mqtt ★0](https://github.com/mreschka/helios2mqtt) - A daemon for syncing a helios easy controls system like my KWL EC 220D to MQTT.
* [hm2mqtt.js ★11](https://github.com/hobbyquaker/hm2mqtt.js) - Interface between EQ-3's Homematic line of smarthome devices and MQTT. Supports Homematic IP.
* [HS100toMQTT ★0](https://github.com/dersimn/HS100toMQTT) - Gateway between TPLink HS100/HS110 and MQTT.
* [knx2mqtt ★11 ⏳2Y](https://github.com/owagner/knx2mqtt) - Interface between the KNX home automation standard and MQTT.
* [mqtt2homekit](https://github.com/forty2/mqtt2homekit) - Roughly the opposite of [homekit2mqtt ★111](https://github.com/hobbyquaker/homekit2mqtt): Control your HomeKit-enabled devices with MQTT and without Siri or iPhone.
* [mqtt-dss-bridge ★3 ⏳2Y](https://github.com/cgHome/mqtt-dss-bridge) - MQTT digitalSTROM-Server Bridge.
* [node-lox-mqtt-gateway ★12](https://github.com/alladdin/node-lox-mqtt-gateway) - Gateway for Loxone™ mini server to communicate with MQTT broker.
* [xiaomi2mqtt ★7](https://github.com/svrooij/node-xiaomi2mqtt) - bridge between the Xiaomi Smart Home Gateway Aquara and a MQTT server.
* [smartthings-mqtt-bridge ★161](https://github.com/stjohnjohnson/smartthings-mqtt-bridge) - Bridge between [SmartThings](https://www.smartthings.com/) and MQTT.


#### Smart Home Integration Software

* [control-freak ★6](https://github.com/tx4x/control-freak) - IDE for IoT & friends. Built in MQTT support.
* [Domoticz](http://www.domoticz.com/) - Domoticz beta supports MQTT.
* [FHEM](http://fhem.de/fhem.html) has a [MQTT module](http://fhem.de/commandref.html#MQTT) since V5.6.
* [Home Assistant](https://home-assistant.io/) has a MQTT component.
* [Homegear](https://www.homegear.eu/index.php/Main_Page) has build in MQTT support.
* [homekit2mqtt](https://github.com/hobbyquaker/homekit2mqtt) - Interface between [HAP-NodeJS ★1660](https://github.com/KhaosT/HAP-NodeJS) and MQTT. Control MQTT connected devices with Siri or HomeKit Apps.
* [Home.Pi ★184 ⏳2Y](https://github.com/denschu/home.pi) is based on MQTT.
* [ioBroker](https://github.com/ioBroker) has a [MQTT adapter ★10](https://github.com/ioBroker/ioBroker.mqtt).
* [Lelylan](http://www.lelylan.com/) - IOT Cloud Platform. Microservices Architecture. For Developers.
* [Node-RED](https://nodered.org/) - A visual tool for wiring the Internet of Things, has native MQTT Support.
* [openHAB](https://github.com/openhab) has a [MQTT binding](https://github.com/openhab/openhab1-addons/wiki/MQTT-Binding).
* [pimatic](https://pimatic.org/) has a MQTT plugin.


#### Lighting

* [chromoflex2mqtt ★2 ⏳2Y](https://github.com/owagner/chromoflex2mqtt) - Control Chromoflex USP3 RGB LED modules via MQTT.
* [h801/mqtt](https://github.com/open-homeautomation/h801/tree/master/mqtt) - Alternative firmware for the H801 LED dimmer that uses MQTT as a control channel.
* [hue2mqtt.js ★4](https://github.com/hobbyquaker/hue2mqtt.js) - Interface between the Philips Hue bridge and MQTT.
* [MQTT DMX Controller ★7](https://github.com/hobbyquaker/mqtt-dmx-controller) - DMX Controller with MQTT support.
* [mqtt-dmx-sequencer](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - Headless counterpart to [MQTT DMX Controller ★5](https://github.com/hobbyquaker/mqtt-dmx-sequencer) - use scenes and sequences exported from the MQTT DMX Controller and control them via MQTT.
* [TRADFRI2MQTT ★38](https://github.com/hardillb/TRADFRI2MQTT) - MQTT Bridge for IKEA TRÅDFRI Light Gateway.


#### Home Entertainment

* [airtunes2mqtt ★9 ⏳2Y](https://github.com/hobbyquaker/airtunes2mqtt) - MQTT controlled Multi-Room Audio with Airplay/Airtunes Devices.
* [bravia2mqtt ★2](https://github.com/forty2/bravia2mqtt) - Control your Sony Bravia TV with MQTT.
* [broadlink-mqtt ★52](https://github.com/eschava/broadlink-mqtt) - MQTT client to control BroadLink RM devices.
* [chromecast-mqtt-connector ★10](https://github.com/nohum/chromecast-mqtt-connector) - Control your Google Chromecast devices using MQTT.
* [kodi2mqtt ★42](https://github.com/owagner/kodi2mqtt) - Interface between a Kodi media center instance and MQTT.
* [harmony-api ★175](https://github.com/maddox/harmony-api) - A simple server allowing you to query/control multiple local Harmony Home Hubs over HTTP or MQTT.
* [htd2mqtt ★0 ⏳1Y](https://github.com/TheOriginalAndrobot/htd2mqtt) - Bridge between an HTD Lync audio system and MQTT.
* [lgtv2mqtt ★16](https://github.com/hobbyquaker/lgtv2mqtt) - Interface between LG WebOS Smart TVs and MQTT.
* [lirc2mqtt ★9](https://github.com/hobbyquaker/lirc2mqtt) - Send and receive infrared via [LIRC](www.lirc.org).
* [mqtt2atlonamatrix ★0](https://github.com/forty2/mqtt2atlonamatrix) - Control Atlona HDMI matrix switches with MQTT.
* [mqtt2tivoremote ★2](https://github.com/forty2/mqtt2tivoremote) - Make TiVo DVR remote control available through an MQTT smarthome style interface.
* [onkyo2mqtt ★7 ⏳1Y](https://github.com/owagner/onkyo2mqtt) - Interface between Onkyo AVR's EISCP network remote protocol and MQTT. Uses the onkyo-eiscp library.
* [VLC MQTT Module](https://wiki.videolan.org/Documentation:Modules/mqtt/) - Control VLC via MQTT.
* [xbmc2mqtt ★5 ⏳2Y](https://github.com/gordonjcp/xbmc-mqtt) - A simple plugin for XBMC to listen for a particular topic on an MQTT broker, and display a popup message.
* [yamaha-avr2mqtt ★3 ⏳1Y](https://github.com/akentner/yamaha-avr2mqtt) - A simple adapter for connection Yamaha AVR to MQTT.


#### Smart Metering

* [bcontrol2mqtt ★1](https://github.com/hobbyquaker/bcontrol2mqtt) - Publish measurements from [TQ Energy Manager](https://www.tq-group.com/produkte/produktdetail/prod/energy-manager/extb/Main/) to MQTT.


#### Messaging

* [mqtt-irc-bot ★13 ⏳2Y](https://github.com/dobermai/mqtt-irc-bot) - A MQTT to IRC / IRC to MQTT bridge or bot.
* [mqttwarn ★607](https://github.com/jpmens/mqttwarn) - Subscribe to MQTT topics (with wildcards) and notifiy pluggable services.
* [twitter-to-mqtt ★12 ⏳5Y](https://github.com/knolleary/twitter-to-mqtt) - A python daemon that uses the Twitter Streaming API to access tweets and republishes them to an MQTT topic.


#### Misc

* [AlexaMqttBridge ★11](https://github.com/mhdawson/AlexaMqttBridge) - Bridge between Amazon Alexa and Mqtt.
* [buderus2mqtt ★0](https://github.com/krambox/buderus2mqtt) - Bridge between Buderus KM200 internet gateway and Mqtt.
* [dashbutton2mqtt ★6](https://github.com/hobbyquaker/dashbutton2mqtt) - Publish Amazon Dash Button presses to MQTT.
* [flowerpower2mqtt ★4 ⏳2Y](https://github.com/hobbyquaker/flowerpower2mqtt) - Publish measurements from Parrot Flower Power plant sensors to MQTT.
* [haiku2mqtt ★0](https://github.com/forty2/haiku2mqtt) - A bridge between Haiku smart fans and MQTT.
* [homely ★7 ⏳1Y](https://github.com/baol/homely) - Collection of Go daemons for connecting Domoticz and other stuff.
* [kobold2mqtt ★0](https://github.com/krambox/kobold2mqtt) - Bridge between Vorwerk Kobold Vr200 internet gateway and Mqtt.
* [leaf-python-mqtt ★14](https://github.com/glynhudson/leaf-python-mqtt) - Extract data from Nissan Leaf API and post to mqtt.
* [miflora-mqtt-daemon ★22](https://github.com/ThomDietrich/miflora-mqtt-daemon) - Linux service to send Xiaomi Mi Flora plant sensor data to an MQTT broker.
* [mqtt2ble ★10](https://github.com/hardillb/mqtt2ble) - A way to bridge MQTT topics to BLE Gatt characteristics.
* [mqttclpro ★24](https://github.com/dc297/mqttclpro) - MQTT Client with tasker integration Android app.
* [mqttDB ★4](https://github.com/hobbyquaker/mqttDB) - A JSON store with MQTT interface.
* [node-mqtt-for-anki-overdrive ★38 ⏳1Y](https://github.com/IBM-Bluemix/node-mqtt-for-anki-overdrive) - Node.js Controller and MQTT API for Anki Overdrive.
* [parrot-sample ★17](https://github.com/IBM-Bluemix/parrot-sample) - Sample code which uses MQTT to control a Parrot AR Drone.
* Tasker (Automation for Android) [MQTT Publisher Plugin](https://play.google.com/store/apps/details?id=net.nosybore.mqttpublishplugin).
* [wlan-thermo-mqtt-addon](https://bitbucket.org/IOcastor/wlan-thermo-mqtt-addon/) - Addon for a popular DIY barbecue thermometer.

### Visualization, Dashboards

* [Crouton](http://crouton.mybluemix.net/crouton/gettingStarted) - A dashboard that taps into your IOT network, using only MQTT and JSON.
* [d3-MQTT-Topic-Tree ★65 ⏳1Y](https://github.com/hardillb/d3-MQTT-Topic-Tree) - A MQTT Topic Tree viewer using the d3 collapsable tree and MQTT over websockets.
* [HelloIoT ★5](https://github.com/adrianromero/helloiot) - HelloIoT is a MQTT client and dashboard application.
* [HOMR-REACT ★6](https://github.com/klauserber/homr-react) - A configurable MQTT Visualization.
* [Linear MQTT Dashboard ★25 ⏳1Y](https://github.com/ravendmaster/linear-mqtt-dashboard) - Easy, customizable control panel - MQTT-client.
* [node-red-dashboard ★322](https://github.com/node-red/node-red-dashboard) - A dashboard UI for Node-RED.
* [MMM-mqtt ★6](https://github.com/javiergayala/MMM-mqtt) - This is an extension for the MagicMirror². It provides the ability to subscribe to MQTT topics and display them.
* [mqtt2highcharts ★41 ⏳1Y](https://github.com/matbor/mqtt2highcharts) - Plotting live numbered data from a subscribed mqtt topic using Highcharts.
* [MQTT Dash](https://play.google.com/store/apps/details?id=net.routix.mqttdash&hl=de) - Android App: With the app you can create dashboards for your MQTT enabled IoT Smart Home devices and applications.
* [mqtt-panel ★168](https://github.com/fabaff/mqtt-panel) - A web interface for MQTT.
* [mqtt-svg-dash ★35 ⏳4Y](https://github.com/jpmens/mqtt-svg-dash) - Subscribe to MQTT, extract JSON from a message and make lights blink on an SVG page.
* [thingsboard](https://thingsboard.io/) - Device management, data collection, processing and visualization for your IoT projects.

Other tools that can be used to create Visualization/Dashboards can be found under [Smart Home Integration Software](#smart-home-integration-software)


### Architecture, Convention

* [Homie ★267](https://github.com/marvinroger/homie) - A lightweight MQTT convention for the IoT.
* [mqtt-smarthome ★136](https://github.com/mqtt-smarthome/mqtt-smarthome) - Smart home automation with MQTT as the central message bus - Architectural proposal.


## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/hobbyquaker/awesome-mqtt/blob/master/contributing.md) first.


## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)
---
<p align="center">
	This list is a copy of <a href="https://github.com/hobbyquaker/awesome-mqtt">hobbyquaker/awesome-mqtt</a> with ranks
</p>
