# Awesome Thingsboard [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]

A curated list of awesome Thingsboard cool things that for some reasons still are not in [the official repository](https://github.com/thingsboard):

- [Awesome Thingsboard](#awesome-thingsboard)
    - [Code Snippets](#code-snippets)
    - [Widgets](#widgets)
    - [Dashboards](#dashboards)
    - [Rule chains](#rule-chains)
    - [Rule nodes](#rule-nodes)
    - [SDKs and REST clients](#sdks-and-rest-clients)
    - [Tools](#tools)
    - [Integrations](#integrations)
        - [Solutions](#solutions)
        - [Hardware](#hardware)
        - [IoT systems](#iot-systems)
    - [Deployment](#deployment)
    - [Administration](#administration)
- [Contributing](#contributing)

---

## Code Snippets

 * [Custom action to dynamically add data key to chart](https://github.com/thingsboard/thingsboard/issues/13000#issuecomment-2855552949)
 * [Calling mobile action programatically](https://github.com/thingsboard/thingsboard/issues/13091#issuecomment-2778619193)
 * [How to remove state ids from dashboard toolbar](https://github.com/thingsboard/thingsboard/issues/12984#issuecomment-2739814278)
 * [Custom SVG as map marker](https://github.com/thingsboard/thingsboard/issues/12674https://github.com/thingsboard/thingsboard/issues/12674)
 * [Call REST endpoints that are not exposed in service map](https://github.com/thingsboard/thingsboard/issues/12334#issuecomment-2561829844)
 * [Assign default dashboard to user with fullscreen mode](https://github.com/thingsboard/thingsboard/issues/8599#issuecomment-1558515882)
 * [Widget Time Window Callback](https://github.com/thingsboard/thingsboard/issues/11408#issuecomment-2290740622)
 * [Export Image to File](https://github.com/thingsboard/thingsboard/issues/10808)
 * [Back Button](https://github.com/thingsboard/thingsboard/issues/10819)
 * [Location from Browser](https://github.com/thingsboard/thingsboard/issues/10891#issuecomment-2138274640)
 * [Colorize table rows without row style function](https://github.com/thingsboard/thingsboard/issues/10935#issuecomment-2155813206)

## Widgets

* [Collibellex-Thingsboard-Widgets](https://github.com/rossmann-engineering/Collibellex-Thingsboard-Widgets) - widget library for Thingsboard CE/PE 3.0+
* [Multiple Devices in HTML/Markdown widget](https://github.com/thingsboard/thingsboard/issues/10577#issuecomment-2272958117)
* [Cards Rendering Widget](https://github.com/thingsboard/thingsboard/issues/11243#issuecomment-2275872186)
* [AbCthings widgets](https://github.com/AbCthings/thingsboard-widgets) - chart and gauge widgets
* [thingsboard-widget](https://github.com/caowm/thingsboard-widget) - inter-widget communication, based on [thingsboard/thingsboard#976](https://github.com/thingsboard/thingsboard/issues/976)
* [ATAW](https://github.com/SchweizerischeBundesbahnen/thingsboard-advanced-attribute-widget) - Advanced Thingsboard Attribute Widget
* [hasankarainfo' widgets](https://github.com/hasankarainfo/ThingsBoard) - widgets bundle includes Last Value Chart, Digital Gauge Card and Delete Time Series widget
* [Time dependent polygon map widget](https://github.com/argosp/Thingsboard-widgets) - widget displays polygons in different time slices
* [Image Viewer From Base64](https://github.com/NistantriTech/ThingsboardNTWidgets)
* [Simple Button With HTTP Request](https://github.com/MathieuHalle/ThingsBoard-Widgets)
* [QR code scanner](widget/qr-code-scanner) - decode QR code using web or phone camera
* [Circle progress bar in table](https://github.com/thingsboard/thingsboard/issues/8462#issuecomment-1531219883)
* [Custom Widgets](https://github.com/AlexVishwa/thingsboardCustomWidgets) - several custom widgets
* [Energy widget for IRIS](https://github.com/novaotp/iris-energy-widget?tab=readme-ov-file) - simple energy widget with real-time data
* [Menu based on (customer) device types](https://github.com/thingsboard/thingsboard/issues/11506#issuecomment-2317241704)
 
## Dashboards

* [Live-USB-Webcam-Streaming](https://github.com/shiyazt/Live-USB-Webcam-Streaming-on-ThingsBoard-IoT-Platform) - stream USB Webcam to Thingsboard and detects the human faces
* [Smart-farming-dashboard](https://github.com/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) - rule chain and dashboard for Thingsboard PE
* [Fleet monitoring](https://github.com/davetroiano/confluent-thingsboard) - Confluent Cloud / ThingsBoard Cloud integration IoT demo

## Rule nodes

* [node-red-contrib-thingsboard-pe-rest-api](https://github.com/akashtalole/node-red-contrib-thingsboard-pe-rest-api) - Node-RED node for thingsboard-pe-rest-api

## Rule chains

* [Workaround for Cyclic Rule Chains Scenario](https://github.com/thingsboard/thingsboard/issues/7577#issuecomment-2306395426)
* [Thingsboard API token](chain/tb_api_token) - get token to call Thingsboard REST API
* [TTL for Postgres database](https://github.com/thingsboard/thingsboard/issues/11095#issuecomment-2191926770)
* [Smart-farming-dashboard](https://github.com/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) - rule chain and dashboard for Thingsboard PE
* [Fleet monitoring](https://github.com/davetroiano/confluent-thingsboard) - Confluent Cloud / ThingsBoard Cloud integration IoT demo
* [Assign dashboard to new user](chain/assign-dashboard-to-new-user)

## SDKs and REST clients

* [Laravel ThingsBoard.io Client](https://github.com/jalallinux/laravel-thingsboard) - PHP Laravel client
* [Esys Thingsboard Client](https://github.com/esysberlin/esys-thingsboard-client) - .Net HTTP and MQTT Api client for Thingsboard.io.
* [thingsboard-ruby](https://github.com/ioki-mobility/thingsboard-ruby)
* [Thingsboard.NET](https://github.com/nepton/Thingsboard.Net) - .NET client library for Thingsboard IoT Platform
* [Thingsboard Javascript SDK](https://github.com/acte-technology/thingsboard-js-sdk)
* [Thebex](https://github.com/fvicent/thebex) - Elixir client for the ThingsBoard REST API
* [Rthingsboard](https://github.com/DDorch/Rthingsboard) - R package for interacting with the API of ThingsBoard
* [ThingsBoardDotNet](https://github.com/vgolovanov/ThingsBoardDotNet) - .Net library designed to work with ThingsBoard platform
* [thingsboard-telemetry-stream](https://github.com/derhuerst/thingsboard-telemetry-stream) - fetch data from the Thingsboard telemetry [WebSocket API](https://thingsboard.io/docs/user-guide/telemetry/#websocket-api)

## Tools

* [Thingsboard tools](https://github.com/a631953720/thingsboard-tools2.0/blob/main/Readme-ENG.md) - provides API service with various features
* [thingsboard-data-migration](https://github.com/AbCthings/thingsboard-data-migration) - data migration between two instances of ThingsBoard
* [Thingsboard-Load-Test](https://github.com/wasslz/Thingsboard-Load-Test) - automated load testing tool for Thingsboard
* [TB-CLI](https://github.com/HassanMojab/tb-cli) - command-line Interface for Thingsboard
* [tb-migration](https://github.com/vo-team/tb-migration) - scripts for exporting and importing data using ThingsBoard API
* [tb-scripts](https://github.com/ICS-Energy-Team/tb-scripts) - Bash scripts for managing Thingsboard database and server
* [tb-exporter](https://github.com/oats-center/tb-exporter) - script to fetch the data for a DEVICE from ThingsBoard and merge all of the columns into one, easier to use CSV
* [thingsboard-sandbox](https://github.com/a631953720/thingsboard-sandbox) - simple service that can listen the request and response result
* [Grafana/Prometheus for Docker monolith](https://github.com/den1jkee/ThingsboardSupport/tree/monitoring_docker/monitoring/docker-monolith)

## Integrations

### Solutions

* [AI based IoT Smart Farming Solution](https://github.com/IoT-Communications/Smart-Farming)
* [Embedded-System-for-Chronic-Disease-Patient-Monitoring-using-IoT](https://github.com/MohamedAliHaoufa/Embedded-System-for-Chronic-Disease-Patient-Monitoring-using-IoT)
* [Offline-first Smart Energy Monitoring](https://github.com/arashsm79/OFMon)

### Hardware

* [Avantec Thermostat ](https://github.com/avantec-iot/avantec-thingsboard) - Using Avantec HVAC device with ThingsBoard
* [ESP32-Thingsboard-IoT-Dashboard](https://github.com/hubamatyas/ESP32-Thingsboard-IoT-Dashboard) - MQTT and I2C protocols to set up cloud-enabled dashboard with ESP32 and Arduino
* [TTGO ESP32 CO2 Monitor](https://github.com/raulgotor/co2monitor)
* [ESP32-PulseMeter](https://github.com/jpajzinka/ESP32-PulseMeter)
* [ESP32 ThingsBoard MQTT Client library](https://github.com/liang-zhu-zi/esp32-thingsboard-mqtt-client)
* [Chirpstack http integration from CNDINGTEK lorawan sensor](https://github.com/cndingtek/Chirpstack_Http_JS)
* [tfluna](https://github.com/zkmkarlsruhe/tfluna) - forward TF-Luna LIDAR sensor events over OSC, UDP, or Thingsboard.
* [IoT Agriculture Monitoring System](https://github.com/jxwleong/iot-agriculturue-monitoring-system) - monitoring system uses ESP8266 microcontroller such as NodeMCU and WeMos D1 R2 to monitor and upload plant's parameters
* [LORAPERTURA](https://github.com/fergar73/LORAPERTURA) - IOT device in the things network for door status and weather station
* [CF Arduino Humidifier](https://github.com/caiofrota/cf-arduino-humidifier) - configurable humidifier using ESP8266, ultrasonic atomizer and ThingsBoard as server
* [SGP30](https://github.com/rendzina/SGP30) - SGP30 CO2 and VOC Sensing with A Raspberry Pi
* [Weight scale IoT by ESP32](https://github.com/coniferconifer/ESP32-HX711-MQTT)
* [Arduino_To_Thingsboard](https://github.com/KudosAbhay/Arduino_To_Thingsboard) - send data to Thingsboard from Arduino Mega 2560
* [TTGO-T-Beam-GeoTracker](https://github.com/lemossilva/ThingsBoard-TTGO-T-Beam-GPSTracker-Telemetry) - geotrace each data point
* [STM32 IoT Discovery Board Tutorial](https://github.com/scottrev/STM32_ThingsBoardDemo)
* [qESP32 WiFi and Bluetooth ESP32 IOT DevKit](https://github.com/iotbotscom/qESP32_ThingsBoard)
* [Farm_IoT_ESP32Cam](https://github.com/Dewald928/Farm_IoT_ESP32Cam) - IoT crop monitoring device
* [qTop_BG9x_AxC_ThingsBoard](https://github.com/iotbotscom/qTop_BG9x_AxC_ThingsBoard) - qTop-BG9x-AxC Adafruit Feather Compatible / Arduino MKR Compatible Shield ThingsBoard Local Condition Monitoring Demo
* [qTop_BG96_AFC_ThingsBoard](https://github.com/iotbotscom/qTop_BG96_AFC_ThingsBoard) - qTop-BG96-AFC Adafruit Feather Compatible Shield ThingsBoard Local Condition Monitoring Demo
* [Park-Assist-with-Thingsboard-and-Telegram](https://github.com/abferguson/Park-Assist-with-Thingsboard-and-Telegram) - An ESP8266-based device using ultrasonic sensor to help driver park car at the correct position
* [smart-home-security](https://github.com/spacesick/smart-home-security) - mock smart home security system

### IoT systems

* [Public Dashboard with User Registration and Device Management](https://github.com/DanielBustillos/Users-self-registration-Thingsboard-community-edition)
* [tasmota-thingsboard-daemon](https://github.com/t0mer/tasmota-thingsboard-daemon) - bridge between tasmota devices and ThingsBoard server
* [IoTGateway](https://github.com/iioter/iotgateway) - a cross-platform IoT gateway based on .net6
* [The Things Stack to ThingsBoard Community Edition connector](https://github.com/rroemhild/tts-thingsboard-connector)
* [Thingsboard-HomematicIP Bridge](https://github.com/mpolitze/thingsboard-homematic-client)
* [thoscy](https://github.com/zkmkarlsruhe/thoscy) - relay messages between a ThingsBoard server and OSC (Open Sound Control) 
* [Edgex-thingsboard](https://github.com/dragonxu/edgex-thingsboard) - micro service that connects Edgex to Thingsboard by MQTT
* [rusty-mqtt](https://github.com/lrazovic/rusty-mqtt) - a bridge between the MQTT broker of TTN and ThingsBoard in Rust
* [Thingboard Smart Gateway](https://github.com/oalles/thingsboard-smartgw) - POC for distributed event driven application based on Redis, Spring Boot 3 and Apache Camel 4

## Deployment

* [thingsboard-aws-eb](https://github.com/rubenmromero/thingsboard-aws-eb) - ThingsBoard dockerized application deployment to AWS Elastic Beanstalk
* [Thingsboard on Nutanix Karbon Platform Services](https://github.com/voxic/Thingsboard_on_KPS) - deploy Thingsboard on-top of [Nutanix Karbon Platform Services](https://www.nutanix.com/products/karbon/platform-services)

## Administration

* [Docker Compose health checking via opened ports](https://github.com/thingsboard/thingsboard/issues/11254#issuecomment-2252875644)
* [Startup failures of rule chain nodes](https://github.com/thingsboard/thingsboard/issues/6492#issuecomment-2161165824)
* [Java heap configuration in Kubernetes](https://github.com/thingsboard/thingsboard/issues/10960#issuecomment-2161116976)
* [Redis policy for caching attributes](https://github.com/thingsboard/thingsboard/issues/6568#issuecomment-2175999705)

# Contributing

Your contributions are always welcome!

- - -

If you have any questions about this opinionated list, do not hesitate to open an issue on GitHub.


