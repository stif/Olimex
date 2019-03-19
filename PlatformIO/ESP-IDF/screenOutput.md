```
rs���� (POWERON_RESET),boot:0x1b (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0018,len:4
load:0x3fff001c,len:5776
ho 0 tail 12 room 4
load:0x40078000,len:7924
load:0x40080000,len:5916
entry 0x40080314
I (30) boot: ESP-IDF 3.30103.190221 2nd stage bootloader
I (30) boot: compile time 23:36:45
I (30) boot: Enabling RNG early entropy source...
I (35) boot: SPI Speed      : 40MHz
I (39) boot: SPI Mode       : DIO
I (43) boot: SPI Flash Size : 4MB
I (48) boot: Partition Table:
I (51) boot: ## Label            Usage          Type ST Offset   Length
I (58) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (66) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (73) boot:  2 factory          factory app      00 00 00010000 00100000
I (81) boot: End of partition table
I (85) esp_image: segment 0: paddr=0x00010020 vaddr=0x3f400020 size=0x0b488 ( 46216) map
I (110) esp_image: segment 1: paddr=0x0001b4b0 vaddr=0x3ffc0000 size=0x02024 (  8228) load
I (113) esp_image: segment 2: paddr=0x0001d4dc vaddr=0x40080000 size=0x00400 (  1024) load
I (117) esp_image: segment 3: paddr=0x0001d8e4 vaddr=0x40080400 size=0x0272c ( 10028) load
I (130) esp_image: segment 4: paddr=0x00020018 vaddr=0x400d0018 size=0x2417c (147836) map
I (186) esp_image: segment 5: paddr=0x0004419c vaddr=0x40082b2c size=0x05834 ( 22580) load
I (200) boot: Loaded app from partition at offset 0x10000
I (200) boot: Disabling RNG early entropy source...
I (201) cpu_start: Pro cpu up.
I (204) cpu_start: Starting app cpu, entry point is 0x400811c8
I (0) cpu_start: App cpu up.
I (215) heap_init: Initializing. RAM available for dynamic allocation:
I (221) heap_init: At 3FFAFF10 len 000000F0 (0 KiB): DRAM
I (227) heap_init: At 3FFCC108 len 00013EF8 (79 KiB): DRAM
I (234) heap_init: At 3FFE0440 len 00003BC0 (14 KiB): D/IRAM
I (240) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (246) heap_init: At 40088360 len 00017CA0 (95 KiB): IRAM
I (253) cpu_start: Pro cpu start user code
I (271) cpu_start: Starting scheduler on PRO CPU.
I (0) cpu_start: Starting scheduler on APP CPU.

ESP32-PoE Ethernet Demo. Press ENTER to start.

-------------------------------------

========== Ethernet Demo ==========
Plug Ethernet cable and press Enter
Start...........................................[ COMPLETE ]
Initialize LAN..................................I (8352) system_api: Base MAC address is not set, read default base MAC address from BLK0 of EFUSE
I (8352) emac: emac start !!!

I (8352) emac: emac resetting ....
I (8352) emac: emac reset done
I (8372) emac: emac start success !!!
[ COMPLETE ]
Receiving IP address............................[ ERROR ]
IP address: 0.0.0.0
Press any key to start again!
Task watchdog got triggered. The following tasks did not reset the watchdog in time:
 - IDLE (CPU 0)
Tasks currently running:
CPU 0: main
CPU 1: IDLE
Task watchdog got triggered. The following tasks did not reset the watchdog in time:
 - IDLE (CPU 0)
Tasks currently running:
CPU 0: main
CPU 1: IDLE
```