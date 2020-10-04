# esp-weather

The esp-weather application collects several weather inputs and sends weather messages to an
MQTT broker. The application connects to the broker URI selected using `idf.py menuconfig`
(using mqtt tcp transport).

## How to use esp-weather

### Hardware Required

This is developed and tested on an ESP32-S2 development board, the only required interface is
WiFi and connection to your LAN.

### Configure the project

* Open the project configuration menu (`idf.py menuconfig`)
* Configure Wi-Fi or Ethernet under "Example Connection Configuration" menu. See "Establishing
  Wi-Fi or Ethernet Connection" section in [examples/protocols/README.md](../../README.md) for
  more details.
* When using Make build system, set `Default serial port` under `Serial flasher config`.

### Build and Flash

Build the project and flash it to the board, then run monitor tool to view serial output:

```
idf.py -p PORT flash monitor
```

(To exit the serial monitor, type ``Ctrl-]``.)

See the Getting Started Guide for full steps to configure and use ESP-IDF to build projects.

## Example MQTT Events

```

```

## Example Log Output

```

```
