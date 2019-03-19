```
Der Sketch verwendet 688899 Bytes (52%) des Programmspeicherplatzes. Das Maximum sind 1310720 Bytes.
Globale Variablen verwenden 38244 Bytes (11%) des dynamischen Speichers, 289436 Bytes für lokale Variablen verbleiben. Das Maximum sind 327680 Bytes.
python /home/stif/.arduino15/packages/esp32/tools/esptool_py/2.6.1/esptool.py --chip esp32 --port /dev/ttyUSB0 --baud 115200 --before default_reset --after hard_reset write_flash -z --flash_mode dio --flash_freq 80m --flash_size detect 0xe000 /home/stif/.arduino15/packages/esp32/hardware/esp32/1.0.2-rc1/tools/partitions/boot_app0.bin 0x1000 /home/stif/.arduino15/packages/esp32/hardware/esp32/1.0.2-rc1/tools/sdk/bin/bootloader_dio_80m.bin 0x10000 /tmp/arduino_build_761932/ESP32_PoE_Ethernet_Arduino.ino.bin 0x8000 /tmp/arduino_build_761932/ESP32_PoE_Ethernet_Arduino.ino.partitions.bin 
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

Writing at 0x0000e000... (100 %)
Wrote 8192 bytes (47 compressed) at 0x0000e000 in 0.0 seconds (effective 6518.0 kbit/s)...
Hash of data verified.
Compressed 17968 bytes to 11766...

Writing at 0x00001000... (100 %)
Wrote 17968 bytes (11766 compressed) at 0x00001000 in 1.0 seconds (effective 138.1 kbit/s)...
Hash of data verified.
Compressed 689024 bytes to 406130...

Writing at 0x00010000... (4 %)
Writing at 0x00014000... (8 %)
Writing at 0x00018000... (12 %)
Writing at 0x0001c000... (16 %)
Writing at 0x00020000... (20 %)
Writing at 0x00024000... (24 %)
Writing at 0x00028000... (28 %)
Writing at 0x0002c000... (32 %)
Writing at 0x00030000... (36 %)
Writing at 0x00034000... (40 %)
Writing at 0x00038000... (44 %)
Writing at 0x0003c000... (48 %)
Writing at 0x00040000... (52 %)
Writing at 0x00044000... (56 %)
Writing at 0x00048000... (60 %)
Writing at 0x0004c000... (64 %)
Writing at 0x00050000... (68 %)
Writing at 0x00054000... (72 %)
Writing at 0x00058000... (76 %)
Writing at 0x0005c000... (80 %)
Writing at 0x00060000... (84 %)
Writing at 0x00064000... (88 %)
Writing at 0x00068000... (92 %)
Writing at 0x0006c000... (96 %)
Writing at 0x00070000... (100 %)
Wrote 689024 bytes (406130 compressed) at 0x00010000 in 35.8 seconds (effective 153.8 kbit/s)...
Hash of data verified.
Compressed 3072 bytes to 144...

Writing at 0x00008000... (100 %)
Wrote 3072 bytes (144 compressed) at 0x00008000 in 0.0 seconds (effective 1329.4 kbit/s)...
Hash of data verified.

Leaving...
Hard resetting via RTS pin...
```