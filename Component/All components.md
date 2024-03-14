# Esp8266-01 Wife Wireless
-Specific:
Voltage using: 3.3VDC
Electric consumption : Max 320mA (Better using a separate power supply module for the circuit).
Support standard: 802.11 b/g/n.
Wi-Fi 2.4 GHz, support security standard like: OPEN, WEP, WPA_PSK, WPA2_PSK, WPA_WPA2_PSK.
Support TCP and UDP protocol.
Having 3 activities mode: Client, Access Point, Both Client and Access Point.
Size: 24.8 x 14.3mm
-Pins feature:
1>VCC: 3.3V 
2>GND: 0V
3>Tx: TX pin of UART protocol, connect to RX pin of MCU
4>Rx: RX pin of UART protocol, connect to TX pin of MCU
5>RST:  chân reset, kéo xuống mass để reset.
6>CH_PD: if this pin pulled up to high, module will start to transmit wifi, pulled down to low, module stop to transmit wifi.
7>GPIO0: pull down for upgrade firmware regime and using like normal General Purpose Input and Output
8>GPIO2: using like normal General Purpose Input and Output

#SSD1306 OLED 0'96 inch
-Specific:
Control chip: SSD1306
Display area: 21.744 x 10864mm
Physical size: 27.3 x 27.8mm
Interface type: Default 4-wire SPI
Switchable rear resistor to use 3-wire SPI, IIC interfaces
Number of pins: 7
Display color: yellow blue
Working temperature: -40~70°C
Net weight: 5g
-Pins feature:
1> GND (Power ground)
2> VCC (Power + 3.3-5V)
3> D0 (SPI clock line for SPI interface and IIC clock line for IIC interface)
4> D1 (SPI data line for SPI interface and IIC data line for IIC interface)
5> RES (OLED reset, OLED needs to be reset once after power-on)
6> DC (SPI data/command selection pin, used to set IIC address when IIC interface)
7> CS (OLED SPI chip select, active low, if you do not want to use must be grounded)
 
