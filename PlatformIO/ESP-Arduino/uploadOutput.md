```
> Executing task: platformio run --target upload <

Processing pio-esp32-poe-arduino (framework: arduino; platform: https://github.com/platformio/platform-espressif32.git#feature/stage; board: esp32-poe)
----------------------------------------------------------------------------------------------------------------------------
Verbose mode can be enabled via `-v, --verbose` option
CONFIGURATION: https://docs.platformio.org/page/boards/espressif32/esp32-poe.html
PLATFORM: Espressif 32 (Stage) > OLIMEX ESP32-PoE
HARDWARE: ESP32 240MHz 320KB RAM (4MB Flash)
DEBUG: CURRENT(esp-prog) EXTERNAL(esp-prog, iot-bus-jtag, jlink, minimodule, olimex-arm-usb-ocd, olimex-arm-usb-ocd-h, olimex-arm-usb-tiny-h, olimex-jtag-tiny, tumpa)
Library Dependency Finder -> http://bit.ly/configure-pio-ldf
LDF MODES: FINDER(chain) COMPATIBILITY(soft)
Collected 26 compatible libraries
Scanning dependencies...
Dependency Graph
|-- <WiFi> 1.0
Retrieving maximum program size .pioenvs/pio-esp32-poe-arduino/firmware.elf
Checking size .pioenvs/pio-esp32-poe-arduino/firmware.elf
Memory Usage -> http://bit.ly/pio-memory-usage
DATA:    [=         ]  11.7% (used 38276 bytes from 327680 bytes)
PROGRAM: [=====     ]  53.0% (used 694631 bytes from 1310720 bytes)
Configuring upload protocol...
AVAILABLE: esp-prog, esptool, iot-bus-jtag, jlink, minimodule, olimex-arm-usb-ocd, olimex-arm-usb-ocd-h, olimex-arm-usb-tiny-h, olimex-jtag-tiny, tumpa
CURRENT: upload_protocol = esptool
Looking for upload port...
Auto-detected: /dev/ttyUSB0
Uploading .pioenvs/pio-esp32-poe-arduino/firmware.bin
esptool.py v2.6
Serial port /dev/ttyUSB0
Connecting......
Chip is ESP32D0WDQ6 (revision 1)
Features: WiFi, BT, Dual Core, 240MHz, VRef calibration in efuse, Coding Scheme None
MAC: 24:0a:c4:9c:c3:1c
Uploading stub...
Running stub...
Stub running...
Configuring flash size...
Auto-detected Flash size: 4MB
Compressed 16432 bytes to 10880...
Wrote 16432 bytes (10880 compressed) at 0x00001000 in 1.0 seconds (effective 136.6 kbit/s)...
Hash of data verified.
Compressed 3072 bytes to 144...
Wrote 3072 bytes (144 compressed) at 0x00008000 in 0.0 seconds (effective 1336.5 kbit/s)...
Hash of data verified.
Compressed 8192 bytes to 47...
Wrote 8192 bytes (47 compressed) at 0x0000e000 in 0.0 seconds (effective 6374.6 kbit/s)...
Hash of data verified.
Compressed 694752 bytes to 408794...
Wrote 694752 bytes (408794 compressed) at 0x00010000 in 36.1 seconds (effective 154.0 kbit/s)...
Hash of data verified.

Leaving...
Hard resetting via RTS pin...
========================================================================== [SUCCESS] Took 41.32 seconds ==========================================================================

Das Terminal wird von Aufgaben wiederverwendet, drücken Sie zum Schließen eine beliebige Taste.
```