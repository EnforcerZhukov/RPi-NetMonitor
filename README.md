# RPi-NetMonitor

A Raspberry Pi project: Network Monitor

The monitor pings different public servers (i.e. DNS servers). If 4 consecutive pings fail, the monitor reboots the CPE (router/cablemodem). We use a relay for this.

## Requirements

* [my GPIO module](https://github.com/EnforcerZhukov/Another-Python-RPi-GPIO-Lib)
* [my LCD controller module](https://github.com/EnforcerZhukov/RPi-MQTT-LCD)
* [paho mqtt](https://pypi.org/project/paho-mqtt/)

## TODO

* Explain how everything works in the README
* Upload a electrical schematic of the system
