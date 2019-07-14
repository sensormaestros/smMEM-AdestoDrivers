## Welcome to the Sensor Maestros Adesto Technologies Serial Memory Driver/Demo Page
This page provides a high level overview of the Sensor Maestros firmware developed for Adesto Technologies Serial Memory Devices and provides a demo that can be used with the smWSP and smMEM products to read, write, erase all smMEM Adesto based products.  The firmware demo is targeted to use the EFM32 Leopard Starter Kit in combination with the smWSP(Wireless Sensor Platform) board that allows smMEM, smSENSR, smCOM, smRF, and smPWR products to be plugged into the smBlocks on the smWSP board.  The smWSP can be directly connected to any of the Silicon Labs EFM32 and EFR32 STK's with the 20pin expansion header.  The demo provides a means to meaure Power Consumption for any of the operations and provides an easy to use GUI that is displayed on the LCD of the EFM32 STK for any of the operations such as Write, Read, Erase, and Power Down using the Silicon Labs Power Profiler that is available with the FREE Silicon Labs Simplicity Studio.  The drivers can easily be adapted to other MCU/SOC's of your choice but will not offer the Power Profiler capability and Menu Command Selection via the LCD available on the Silicon Labs EFM32/EFR STK's.  

### Project Directory Structure
.settings -> Project Settings for use with Eclipse/Simplicity Studio IDE  
BSP -> This folder contains the source file for the Trace capability which can be used with the Energy Profiler.  
CMSIS -> This folder contains the the Leopard Gecko startup files.  
Docs -> This folder contains PDF's of the Quick Start Guide and the Porting Guide.  
Drivers -> This folder contains the EFM32 Driver files for capacitive sensing, RTC, LCD, etc.  
emlib -> This folder contains EFM32 library files/drivers for various pieces of functionality.  
src -> This folder contains the source code for the demo itself.  

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sensormaestros/smMEM-AdestoDrivers/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
