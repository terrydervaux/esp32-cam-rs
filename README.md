# esp32-cam-rs

## Hardware Requirements

- ESP32-CAM module
- [PL2303 USB-to-Serial Adapter]((https://www.amazon.fr/dp/B09PYQL5J6))
- Jumper wires

## Hardware Wiring

| **ESP32-CAM Pin** | **PL2303 Pin**        |
|-------------------|-----------------------|
| GND               | GND                   |
| 5V                | VCC (5V)              |
| U0R               | TXD                   |
| U0T               | RXD                   |
| IO0               | GND (Boot Mode)       |

*IO0 to GND*: is necessary *only* to put the ESP32-CAM into *flashing* mode.

## Useful Resources

- [ESP32-CAM Pinout Reference](https://lastminuteengineers.com/esp32-cam-pinout-reference/)
- [Rust on ESP-IDF template](https://github.com/esp-rs/esp-idf-template)
