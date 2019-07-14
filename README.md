![SM_LOGO](https://sensormaestros.com/wp-content/uploads/sensor-maestros-logo-200.png)


# Welcome to the Sensor Maestros Adesto Technologies Serial Memory Driver/Demo Page
This page provides a high level overview of the Sensor Maestros firmware developed for Adesto Technologies Serial Memory Devices and provides a demo that can be used with the smWSP and smMEM products to read, write, erase all smMEM Adesto based products.  The firmware demo is targeted to use the EFM32 Leopard Starter Kit in combination with the smWSP(Wireless Sensor Platform) board that allows smMEM, smSENSR, smCOM, smRF, and smPWR products to be plugged into the smBlocks on the smWSP board.  The smWSP can be directly connected to any of the Silicon Labs EFM32 and EFR32 STK's with the 20pin expansion header.  The demo provides a means to meaure Power Consumption for any of the operations and provides an easy to use GUI that is displayed on the LCD of the EFM32 STK for any of the operations such as Write, Read, Erase, and Power Down using the Silicon Labs Power Profiler that is available with the FREE Silicon Labs Simplicity Studio.  The drivers can easily be adapted to other MCU/SOC's of your choice but will not offer the Power Profiler capability and Menu Command Selection via the LCD available on the Silicon Labs EFM32/EFR STK's.  

## Sensor Maestros Prodcucts for use with Adesto Firmware Drivers/Demo
[smWSP(Allows all smMEM, smSENSR, smCOM, smRF-CYW2073xS, and smPWR products to be plugged into smBlocks. Plugs directly into SiLabs EFM32 STK)] [smWSP]  
[smWSP-ARD(Arduino Compatible shield version of the smWSP)]  [smWSP-ARD]  
[smMEM-AT25SF041(4Mb Standard SPI Flash)] [smMEM-AT25SF041]  
[smMEM-AT25XE021(2Mb Ultra-Low Power SPI Flash)] [smMEM-AT25XE021]  
[smMEM-AT25XE041(4Mb Ultra-Low Power SPI FLash)] [smMEM-AT25XE041]  
[smMEM-AT45DB081(8Mb Dual SRAM ULP SPI Flash)] [smMEM-AT45DB081]  
[smMEM-AT45DB641(16Mb Dual SRAM ULP SPI Flash)] [smMEM-AT45DB641]  
[smMEM-RM25C512C-L(512Kb SPI CBRAM/Resistive Memory)] **COMING SOON!!**  
[smMEM-RM24C512C-L(512Kb I2C CBRAM/Resistive Memory)] **COMING SOON!!**  

[smWSP]: https://sensormaestros.com/products/sensor/wireless-sensor-platforms/smwsp/
[smWSP-ARD]: https://sensormaestros.com/products/sensor/wireless-sensor-platforms/smwsp-ard/
[smMEM-AT25SF041]: https://sensormaestros.com/products/memory/serial-flash/smmem-at25sf041/
[smMEM-AT25XE021]: https://sensormaestros.com/products/memory/serial-flash/smmem-at25xe021/
[smMEM-AT25XE041]: https://sensormaestros.com/products/memory/serial-flash/smmem-at25xe041/
[smMEM-AT45DB081]: https://sensormaestros.com/products/memory/serial-flash/smmem-at45db081/
[smMEM-AT45DB641]: https://sensormaestros.com/products/memory/serial-flash/smmem-at45db641/

### Project Directory Structure
.settings -> Project Settings for use with Eclipse/Simplicity Studio IDE  
BSP -> This folder contains the source file for the Trace capability which can be used with the Energy Profiler.  
CMSIS -> This folder contains the the Leopard Gecko startup files.  
Docs -> This folder contains PDF's of the Quick Start Guide and the Porting Guide.  
Drivers -> This folder contains the EFM32 Driver files for capacitive sensing, RTC, LCD, etc.  
emlib -> This folder contains EFM32 library files/drivers for various pieces of functionality.  
src -> This folder contains the source code for the demo itself.  
HTML Documentation -> Provides a Doxygen based output of the firmawre project

## Sensor Maestros
**Sensor Maestros provides wireless sensor based products for rapid prototyping and OEM wireless sensor products.  Sensor Maestros provides complete design services for hardware, firmware, software, mobile app, mechanical/enclosure development.  Sensor Maestros also can provide turn-key manufacturing services for high volume, low-cost off-shore manufacturing for PCB, PCBA, Plastics, Metals, and complete Final Test and Assembly procedures.**

**For inquiries contact Sensor Maestros at sales@sensormaestros.com**

**Regards,**  
www.sensormaestros.com  

**Thank You!!**


