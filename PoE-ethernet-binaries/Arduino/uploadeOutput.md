```
[stif@stif-laptop Arduino]$ python /home/stif/.arduino15/packages/esp32/tools/esptool_py/2.6.1/esptool.py --chip esp32 --port /dev/ttyUSB0 --baud 115200 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m --flash_size detect 0xe000 /home/stif/.arduino15/packages/esp32/hardware/esp32/1.0.2-rc1/tools/partitions/boot_app0.bin 0x1000 /home/stif/.arduino15/packages/esp32/hardware/esp32/1.0.2-rc1/tools/sdk/bin/bootloader_dio_80m.bin 0x10000 /home/stif/workspace/arduino/Olimex/PoE-ethernet-binaries/Arduino/ESP32_PoE_Ethernet_Arduino.ino.bin 0x8000 /home/stif/workspace/arduino/Olimex/PoE-ethernet-binaries/Arduino/ESP32_PoE_Ethernet_Arduino.ino.partitions.bin 
esptool.py v2.6
Serial port /dev/ttyUSB0
Connecting....
Chip is ESP32D0WDQ6 (revision 1)
Features: WiFi, BT, Dual Core, 240MHz, VRef calibration in efuse, Coding Scheme None
MAC: 24:0a:c4:9c:c3:1c
Uploading stub...
Running stub...
Stub running...
Configuring flash size...
Auto-detected Flash size: 4MB
Compressed 8192 bytes to 47...
Wrote 8192 bytes (47 compressed) at 0x0000e000 in 0.0 seconds (effective 6524.7 kbit/s)...
Hash of data verified.
Compressed 17968 bytes to 11766...
Wrote 17968 bytes (11766 compressed) at 0x00001000 in 1.0 seconds (effective 138.0 kbit/s)...
Hash of data verified.
Compressed 689024 bytes to 406130...
Wrote 689024 bytes (406130 compressed) at 0x00010000 in 35.9 seconds (effective 153.6 kbit/s)...
Hash of data verified.
Compressed 3072 bytes to 144...
Wrote 3072 bytes (144 compressed) at 0x00008000 in 0.0 seconds (effective 1325.6 kbit/s)...
Hash of data verified.

Leaving...
Hard resetting via RTS pin...
```