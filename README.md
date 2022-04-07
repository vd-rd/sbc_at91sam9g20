# Microchip AT91SAM9G20

![board_render](/assets/front.png)

## Description
 The follow-up to my previous [SBC based on AT91SAM9260](https://github.com/vd-rd/sbc_at91sam9260), enhancing the board specs in computing power and flexibility. The board is smaller 60x40mm now (SAM9260 was 80x40mm) while keeping the same amount of supported RAM and interfaces. AT91SAM9G20 boosts core speed to 400MHz and bus speed to 133MHz.
 
Board overview (draft):
[TBD]


### Features


| Characteristic | Description |
| --- | --- |
| Dimensions | 60mm x 40mm |
| Processor | AT91SAM9G20 - ARM926EJ @ 400MHz |
| Oscillators |  18.432MHz main clock, 32.768kHz RTC |
| RAM | SDRAM 128MB max (2x512Mbit modules) |
| Storage | microSD |
| USB | 1 microUSB client, 2 USB Host|
| Ethernet | RMII header |
| WiFi/BT | N/A |
| Supply | USB 5V, ACIN 5V |

Common interfaces such as I2C, SPI, UART and GPIO are exposed on the header.


### Building and flashing

Build U-Boot and Linux kernel + rootFS - TBD

Flash to SDCard - TBD

 
### Resources

You can find all necesary information to build or evaluate the module here:
   - [Fabrication files](https://github.com/vd-rd/sbc_alw_a13/releases)
