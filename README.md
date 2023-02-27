# USB_bootloader_SamD21

## Bootloader UF2 for Atmel D21, D51, D54 microcontrollers
This is a bootloader UF2 (USB Flashing Format) that can be used to program Atmel D21, D51, and D54 microcontrollers. It uses the CMSIS Atmel Pack and allows for easy and fast programming of the microcontrollers via USB.

## Features
Supports Atmel D21, D51, and D54 microcontrollers
Uses the CMSIS Atmel Pack for reliable and efficient programming
Allows for easy and fast programming via USB using the UF2 format
Can be easily integrated into any project and customized as needed

## Installation and Usage

To use this bootloader, you will need to follow these steps:

Download the UF2 bootloader image file for your specific microcontroller (D21, D51, or D54).
Connect your microcontroller to your computer using a USB cable.
Put your microcontroller in bootloader mode by either:
Pressing the reset button twice quickly
Connecting the RST pin to ground for a brief period of time
A new disk drive should appear on your computer named "DAPLink". Drag and drop the UF2 bootloader image file onto the "DAPLink" drive.
Wait for the bootloader to finish programming your microcontroller. 
## Customization
This bootloader can be easily customized to fit the specific needs of your project. The source code is available on GitHub and can be modified as needed. Some possible customizations include:

Changing the bootloader LED pin or behavior
Modifying the USB VID and PID to match your product
Adding custom behaviors during programming, such as erasing specific flash pages or verifying programming results

## License
This bootloader is released under the MIT License. See the LICENSE file for more information.

## Contact
For any questions or feedback, please feel free to reach out to me at francisco.mella.torr[at]outlo??.com.
