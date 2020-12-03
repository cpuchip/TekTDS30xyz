## TE 1-1734099-0

The 100 pin connector in the expansion port is a TE 1-1734099-0
These connectors can be purchased easily:

https://www.digikey.com/en/products/detail/te-connectivity-amp-connectors/1-1734099-0/1121334

https://www.ebay.com/itm/TE-1-1734099-0-100-Pos-RT-Angle-Thu-Hole-Board-to-Board-Connector-Plug-QTY-5/163591113538?hash=item2616ca4b42:g:IdEAAOSwkJNchlRM

Information gathered from EEVBlog:
https://www.eevblog.com/forum/testgear/reverse-engineering-tektronix-tds3gv-module-for-tds3000-series-oscilloscopes/50/
https://hackaday.io/project/172242-extension-card-for-tds3000-scopes/log/179520-the-actual-informations
https://www.eevblog.com/forum/repair/tektronix-tds3012b-repair-help-needed/


## Pin Out
|Pin  | Description   | Notes              | XPC860DEZP50D3 pin |
|-----|-------------  |--------------------|--------------------|
| 1   | GND           |                    |                    |
| 2   | DotClk        | Screen 25Mhz       |                    |
| 3   | HSync         | Screen 32.5Khz     |                    |
| 4   | VSync         | Screen 60Hz        |                    |
| 5   | GND           |                    |                    |
| 6   | Red_0         | Screen Red bit 0   |                    |
| 7   | Red_1         | Screen Red bit 1   |                    |
| 8   | Red_2         | Screen Red bit 2   |                    |
| 9   | Red_3         | Screen Red bit 3   |                    |
| 10  | GND           |                    |                    |
| 11  | EXT_CLK       | *CE of DS1742      |                    |
| 12  | 3v3           | Power 3.3V         |                    |
| 13  | SMTXD1        | Serial 38400,n,8,1 |                    |
| 14  | SMRXD1        | Serial 38400,n,8,1 |                    |
| 15  | SNI_TX        | Ethernet           |                    |
| 16  | SNI_RX        | Ethernet           |                    |
| 17  | SNI_TENA      | Ethernet           |                    |
| 18  | SNI_CLSN      | Ethernet           |                    |
| 19  | SNI_RENA      | Ethernet           |                    |
| 20  | SNI_TCLK      | Ethernet           |                    |
| 21  | GND           |                    |                    |
| 22  | SNI_RCLK      | Ethernet           |                    |
| 23  | U730.10       |                    |                    |
| 24  | CARD_DETECT   | 5k to GND for 3GM  |                    |
| 25  | U830.3        |                    |                    |
| 26  | *TSIZ0 or *REG|                    | B9??               |
| 27  | *TSIZ1        |                    | C9??               |
| 28  | A19           | Address Bus        |                    |
| 29  | A18           | Address Bus        |                    |
| 30  | A17           | Address Bus        |                    |
| 31  | A16           | Address Bus        |                    |
| 32  | GND           | Address Bus        |                    |
| 33  | A15           | Address Bus        |                    |
| 34  | A14           | Address Bus        |                    |
| 35  | A13           | Address Bus        |                    |
| 36  | A12           | Address Bus        |                    |
| 37  | A11           | Address Bus        |                    |
| 38  | GND           |                    |                    |
| 39  | A10           | Address Bus        |                    |
| 40  | A9            | Address Bus        |                    |
| 41  | A8            | Address Bus        |                    |
| 42  | A7            | Address Bus        |                    |
| 43  | A6            | Address Bus        |                    |
| 44  | A5            | Address Bus        |                    |
| 45  | GND           |                    |                    |
| 46  | A4            | Address Bus        |                    |
| 47  | A3            | Address Bus        |                    |
| 48  | A2            | Address Bus        |                    |
| 49  | A1            | Address Bus        |                    |
| 50  | A0            | Address Bus        |                    |
| 51  | Green_0       | Screen Green bit 0 |                    |
| 52  | Green_1       | Screen Green bit 1 |                    |
| 53  | GND           |                    |                    |
| 54  | Green_2       | Screen Green bit 2 |                    |
| 55  | Green_3       | Screen Green bit 3 |                    |
| 56  | Blue_0        | Screen Blue bit 0  |                    |
| 57  | Blue_1        | Screen Blue bit 1  |                    |
| 58  | GND           |                    |                    |
| 59  | Blue_2        | Screen Blue bit 2  |                    |
| 60  | Blue_3        | Screen Blue bit 3  |                    |
| 61  | IRQ6          | TMS/G18 not here   | G3                 |
| 62  | TDO           | JTAG               | G17                |
| 63  | TDI           | JTAG               | H17                |
| 64  | TCK           | JTAG               | H16                |
| 65  | SRESET        |                    | P2??               |
| 66  | HRST          | Scope Reset        | N4??               |
| 67  | GND           |                    |                    |
| 68  | TxD           | Serial             |                    |
| 69  | RxD           | Serial             |                    |
| 70  | RTS           | Serial             |                    |
| 71  | CTS           | Serial             |                    |
| 72  | 5v            | Power 5v           |                    |
| 73  | IRQ4          |                    |                    |
| 74  | *WE0          |                    |                    |
| 75  | *WE1          |                    |                    |
| 76  | *OE           | Output Enable      |                    |
| 77  | *TA           | Transfer Ack       |                    |
| 78  | *CE1          | Select GPIB ctrlr  |                    |
| 79  | *CE2          | Sel. card Type     |                    |
| 80  | GND           |                    |                    |
| 81  | R/W           | Read/Write         |                    |
| 82  | D15           | Data Bus PPC MSB   |                    |
| 83  | D14           | Data Bus           |                    |
| 84  | D13           | Data Bus           |                    |
| 85  | D12           | Data Bus           |                    |
| 86  | GND           |                    |                    |
| 87  | D11           | Data Bus           |                    |
| 88  | D10           | Data Bus           |                    |
| 89  | D9            | Data Bus           |                    |
| 90  | D8            | Data Bus           |                    |
| 91  | GND           |                    |                    |
| 92  | D7            | Data Bus           |                    |
| 93  | D6            | Data Bus           |                    |
| 94  | D5            | Data Bus           |                    |
| 95  | D4            | Data Bus           |                    |
| 96  | GND           |                    |                    |
| 97  | D3            | Data Bus           |                    |
| 98  | D2            | Data Bus           |                    |
| 99  | D1            | Data Bus           |                    |
| 100 | D0            | Data Bus           |                    |
