# LUA_RC522

MFRC522 RFID reader/writer for the NodeMCU
Based on original work by Ben Jackson updated by Nikos Georgousis

*This is a port of:*

- *https://github.com/ondryaso/pi-rc522		>>>	Python*

- *https://github.com/ljos/MFRC522			>>>	Arduino*

This lua script works with **nodeMCU dev kit** modules, **Wemos D1 mini** or any other ESP-8266 based compatible  board and it is intent to be used with MFRC522 RFID reader. s50 tags can be used (but can work with other Mifare based tags).

You can use https://nodemcu-build.com/ web service to build your Nodemcu firmware. Modules required are:  bit,file,gpio,net,node,spi,tmr,uart,wifi
Connections between RFID-RC522 module and WEMOS D1-MINI (Wemos can be replaced with NODEMCU or any other compatible ESP-8266 module)

**Connections**

> RFID-RC522			WEMOS D1-MINI 
> SDA						D4
> SCK						D5
> MOSI					D7
> MISO					D6
> IRQ					- (no connection)
> GND					G (Gnd)
> RST					D3
> 3V3					3V3



