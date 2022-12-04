# Awesome Thingsboard [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]

A curated list of awesome Thingsboard cool things that for some reasons still are not in [the official repository](https://github.com/thingsboard):

- [Awesome Thingsboard](#awesome-thingsboard)
    - [Widgets](#widgets)
    - [Dashboards](#dashboards)
    - [Rule chains](#rule-chains)
    - [Rule nodes](#rule-nodes)
    - [Patches](#patches)
    - [SDKs and REST clients](#sdks-and-rest-clients)
    - [Tools](#tools)
    - [Integrations](#integrations)
        - [Hardware](#hardware)
        - [IoT systems](#iot-systems)
    - [Deployment](#deployment)
- [Resources](#resources)
    - [Books](#books)
    - [Newsletters](#newsletters)
    - [Podcasts](#podcasts)
    - [Websites](#websites)
- [Contributing](#contributing)

---

## Widgets

*Ready to use widgets or even widget bundles.*

* [Collibellex-Thingsboard-Widgets](https://github.com/rossmann-engineering/Collibellex-Thingsboard-Widgets) - widget library for Thingsboard CE/PE 3.0+
* [AbCthings widgets](https://github.com/AbCthings/thingsboard-widgets) - chart and gauge widgets
* [thingsboard-widget](https://github.com/caowm/thingsboard-widget) - inter-widget communication, based on [thingsboard/thingsboard#976](https://github.com/thingsboard/thingsboard/issues/976)
* [ATAW](https://github.com/SchweizerischeBundesbahnen/thingsboard-advanced-attribute-widget) - Advanced Thingsboard Attribute Widget
* [hasankarainfo' widgets](https://github.com/hasankarainfo/ThingsBoard) - widgets bundle includes Last Value Chart, Digital Gauge Card and Delete Time Series widget
* [Time dependent polygon map widget](https://github.com/argosp/Thingsboard-widgets) - widget displays polygons in different time slices
* [Image Viewer From Base64](https://github.com/NistantriTech/ThingsboardNTWidgets)
* [Simple Button With HTTP Request](https://github.com/MathieuHalle/ThingsBoard-Widgets)
* [QR code scanner](widget/qr-code-scanner) - decode QR code using web or phone camera

## Dashboards

*Ready to use dashboards.*

* [Live-USB-Webcam-Streaming](https://github.com/shiyazt/Live-USB-Webcam-Streaming-on-ThingsBoard-IoT-Platform) - stream USB Webcam to Thingsboard and detects the human faces
* [Smart-farming-dashboard](https://github.com/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) - rule chain and dashboard for Thingsboard PE
* [Fleet monitoring](https://github.com/davetroiano/confluent-thingsboard) - Confluent Cloud / ThingsBoard Cloud integration IoT demo

## Rule chains

*Ready to use rule chains.*

* [Thingsboard API token](chain/tb_api_token) - get token to call Thingsboard REST API
* [Smart-farming-dashboard](https://github.com/arifulmrislam/Smart-farming-dashboard-with-ThingsBoard) - rule chain and dashboard for Thingsboard PE
* [Fleet monitoring](https://github.com/davetroiano/confluent-thingsboard) - Confluent Cloud / ThingsBoard Cloud integration IoT demo
* [Assign dashboard to new user](chain/assign-dashboard-to-new-user)

## Rule nodes

*Ready to use rule nodes.*

* [node-red-contrib-thingsboard-pe-rest-api](https://github.com/akashtalole/node-red-contrib-thingsboard-pe-rest-api) - Node-RED node for thingsboard-pe-rest-api

## Patches

*Awesome patches.*

* [Disable chart selection feature](patch/disable-chart-selection-feature-on-mobile) - make chart scrolling on mobile device more comfortable.

## SDKs and REST clients
* [Thingsboard.NET](https://github.com/nepton/Thingsboard.Net) - .NET client library for Thingsboard IoT Platform
* [Thingsboard Javascript SDK](https://github.com/acte-technology/thingsboard-js-sdk)
* [Thebex](https://github.com/fvicent/thebex) - Elixir client for the ThingsBoard REST API
* [Rthingsboard](https://github.com/DDorch/Rthingsboard) - R package for interacting with the API of ThingsBoard
* [ThingsBoardDotNet](https://github.com/vgolovanov/ThingsBoardDotNet) - .Net library designed to work with ThingsBoard platform
* [thingsboard-telemetry-stream](https://github.com/derhuerst/thingsboard-telemetry-stream) - fetch data from the Thingsboard telemetry [WebSocket API](https://thingsboard.io/docs/user-guide/telemetry/#websocket-api)

## Tools

*Awesome tools.*

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

### Hardware

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
* [IoT Agriculture Monitoring System](https://github.com/jxwleong/iot-agriculturue-monitoring-system) - monitoring system uses ESP8266 microcontroller such as NodeMCU and WeMos D1 R2
* [Farm_IoT_ESP32Cam](https://github.com/Dewald928/Farm_IoT_ESP32Cam) - IoT crop monitoring device
* [qTop_BG9x_AxC_ThingsBoard](https://github.com/iotbotscom/qTop_BG9x_AxC_ThingsBoard) - qTop-BG9x-AxC Adafruit Feather Compatible / Arduino MKR Compatible Shield ThingsBoard Local Condition Monitoring Demo
* [qTop_BG96_AFC_ThingsBoard](https://github.com/iotbotscom/qTop_BG96_AFC_ThingsBoard) - qTop-BG96-AFC Adafruit Feather Compatible Shield ThingsBoard Local Condition Monitoring Demo
* [Park-Assist-with-Thingsboard-and-Telegram](https://github.com/abferguson/Park-Assist-with-Thingsboard-and-Telegram) - An ESP8266-based device using ultrasonic sensor to help driver park car at the correct position

### IoT systems

* [Thingsboard-HomematicIP Bridge](https://github.com/mpolitze/thingsboard-homematic-client)
* [thoscy](https://github.com/zkmkarlsruhe/thoscy) - relay messages between a ThingsBoard server and OSC (Open Sound Control) 
* [Edgex-thingsboard](https://github.com/dragonxu/edgex-thingsboard) - micro service that connects Edgex to Thingsboard by MQTT
* [rusty-mqtt](https://github.com/lrazovic/rusty-mqtt) - a bridge between the MQTT broker of TTN and ThingsBoard in Rust

## Deployment

* [thingsboard-aws-eb](https://github.com/rubenmromero/thingsboard-aws-eb) - ThingsBoard dockerized application deployment to AWS Elastic Beanstalk
* [Thingsboard on Nutanix Karbon Platform Services](https://github.com/voxic/Thingsboard_on_KPS) - deploy Thingsboard on-top of [Nutanix Karbon Platform Services](https://www.nutanix.com/products/karbon/platform-services)

# Resources

Where to discover learning resources.

## Books

* [TBD](https://example.com/) - Waiting for your contibution.

## Websites

* [TBD](https://example.com/) - Waiting for your contibution.)

## Newsletters

* [TBD](https://example.com/) - Waiting for your contibution.

## Podcasts

* [TBD](https://example.com/) - Waiting for your contibution.

# Contributing

Your contributions are always welcome!

- - -

If you have any question about this opinionated list, do not hesitate to open an issue on GitHub.


