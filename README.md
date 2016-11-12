# NodeMCU toilet project display integrated with AWS IoT rule engine

__This is work in progress. I've just uploaded my CRUD project files for now. Please be patient with me.__

### TL;DR

![Toilet project light sketch](img/fritzing-toilet-project-leds.jpg)

* Hook up your lights: `RED` = `D2`, `GREEN` = `D1` and `YELLOW` = `D3`
* Run a couple of commands:
```bash
$ cp ./platformio-dist.ini platformio.ini
$ pio lib install PubSubClient
```

Edit `platformio.ini` with your credentials and other settings.

Upload and run your code:
```bash
$ pio run -e nodemcuv2 -t upload && pio serialports monitor -b 115200
```

Weee :-)

... more to come.


## Other resources

* [Getting started with Arduino, NodeMCU or Wemos D1 mini](https://github.com/5orenso/arduino-getting-started)
* [Toilet project sensors](https://github.com/5orenso/nodemcu-mqtt-toilet-project)
* [Bitbar toilet menu plugin](https://github.com/TeliaSoneraNorge/iot-hackaton-toilet-u1-bitbar)


## Contribute

Please contribute with pull-requests.
