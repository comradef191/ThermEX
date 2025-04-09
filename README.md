# ThermEX
A BlackPill powered expansion board for Klipper 3D printers, allowing the use of numerous additional Thermistors.

- Can be stacked ontop of or underneith Nyoomies using appropiate spacers
- OpenSource Hardware, licensed under the [OHLv2-S](https://opensource.org/license/cern-ohl-s)
- 10 thermistors wired directly to the STM32
- 16 additional thermistors wired up via 4 ADS1115 ICs
- Powered directly from the USB port
- Uses an ultra-low-noise [TPS7A2033](https://www.ti.com/product/TPS7A20/part-details/TPS7A2033PDBVR) 300mA 3.3v voltage regulator to power all expansion headers and the ADS1115s
- Features native support for the STM32F4x1 BlackPill, with the unused extra GPIO being broken out to a labelled expansion header alongside 3v3 & GND
- Breaks out the I2C2 & I2C3 busses to a pair of dedicated 4-pin JST-XH connectors
- Breaks out the SPI2 bus to a dedicated header, alongside PB12 to act as chip-select

## Vendors
UK / EU
- None... yet!

Contact me on Discord if you want to add yourself to this list!


## Bill of Materials
This BoM lists exclusively through-hole components, as SMD components will be assembled for you by JLCPCB
|  Component         |QTY | Cost  |  Comment               |  Sourcing URL                                                                                                |
|--------------------|----|-------|------------------------|--------------------------------------------------------------------------------------------------------------|
|JST-XH 2-Pin        | 26 | $0.39 | Thermistor Ports       | https://www.lcsc.com/product-detail/Wire-To-Board-Connector_DEALON-XH-D-2A_C5160911.html                     |
|JST-XH 4-Pin        | 2  | $0.52 | I2C Ports              | https://www.lcsc.com/product-detail/Wire-To-Board-Connector_JST-B4B-XH-A-LF-SN_C144395.html                  |
|2.54 Socket, 1x20   | 2  | $0.81 | STM32 Socket           | https://www.lcsc.com/product-detail/Female-Headers_Shenzhen-Kinghelm-Elec-KH-2-54FH-1X20P-H8-5_C2905423.html |
|2.54 Header, 2x5    | 3  | $0.40 | GPIO; Cut-Down for SPI | https://www.lcsc.com/product-detail/Pin-Headers_HanElectricity-2541WV-2x05P_C5383106.html                    |
|STM32F401 Blackpill | 1  | $3.25 | Main controller        | https://www.aliexpress.com/item/1005006127461676.html                                                        |

# Gallery
*As of 09APR25 no ThermEX26 boards have been produced, thus only KiCad Renders are present currently* 
![image](https://github.com/user-attachments/assets/f0161488-d6f9-49d0-8ce9-c8713ee32efc)
![image](https://github.com/user-attachments/assets/e42110a2-3c35-4beb-9a35-2e72bd05fab5)
