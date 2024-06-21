# Birch Sliding USB Joystick
The Birch Sliding USB Joystick is a small, proportional joystick that has a sliding motion and can be used for adaptive gaming. It has a small range of motion of ±2mm and requires approximately 115 grams-force to fully deflect. It is low profile, with a height of 2.4 mm with the standard topper. This joystick has interchangable toppers and optional mount adapters. The Birch Sliding USB Joystick has the same joystick mechanism as the Aspen Sliding Joystick, but is the USB version.

The Birch Sliding USB Joystick has a cable with a USB-A connector. It acts as a USB HID gamepad with a single joystick and is compatible with a variety of devices including PC and the USB ports of the Microsoft Xbox Adaptive Controller. The deadzone can be adjusted through a serial interface.

<img src="Photos/Birch-Mini-Joystick-U.jpeg" width="500" alt="Picture of the Birch Sliding USB Joystick, it is blue and small with MMC written on the side and an arrow on top.">

<!---
## More info at
- [Makers Making Change Project Page](<Add link>)
- [Makers Making Change Forum Thread](<Add link>)
--->

## How to Obtain a Birch Sliding USB Joystick
### 1. Do it Yourself (DIY) or Do it Together (DIT)

This is an open-source assistive technology, so anyone is free to build it. All of the files and instructions required to build the Birch Sliding USB Joystick are contained within this repository. Refer to the Maker Guide below.

### 2. Request a build of this device

If you would like to obtain a Birch Sliding USB Joystick , you may submit a build request through the [MMC Library Page](https://makersmakingchange.com/project/birch-sliding-usb-joystick/). The requestor is responsible for the cost of materials and any shipping.

### 3. How to build this device for someone else

If you have the skills and equipment to build this device, and would like to donate your time to create the switch for someone who needs it, visit the [MMC Maker Wanted](https://makersmakingchange.com/maker-wanted/) section.

## Getting Started

### 1. Verify Joystick Type
The Birch Sliding USB Joystick is a USB joystick that emulates an HID gamepad allowing use either directly with a PC or with the Microsoft Xbox Adaptive Controller (XAC). Verify that this is the type of joystick the user would like. 

If they want an analog joystick with the same sliding motion instead, they should be directed to the Aspen Sliding Joystick. Note: the Aspen Sliding Joystick is compatible with the Sony Access Controller, but the Birch Sliding USB Joystick is not. 

<!---
Other available joysticks can be found through the [Joystick Selection Guide](https://makersmakingchange.com/resource/analog-joystick-selection-guide/)
--->

### 2. Read through the Maker Guide

The [Maker Guide](/Documentation/Birch_Joystick_Maker_Guide.pdf) contains all the neccessary information to build the device.

### 3. Read the Makers Checklist

Use the Makers Checklist in the [Maker Guide](/Documentation/Birch_Joystick_Maker_Guide.pdf) to confirm details and customization options with the user.

### 4. Order the Off-The-Shelf Components

The [Bill of Materials](/Documentation/Birch_Joystick_BOM.csv) lists all of the parts and components required to build the Birch Sliding USB Joystick. 


### 5. Print the 3D Printable components

Print the components needed for the Birch Sliding USB Joystick. Make sure to ask the user if they would like any of the optional prints such as toppers or mount adapters.

All of the files and individual print files can be in the [/Build_Files/3D_Print_Files](/Build_Files/3D_Print_Files/) folder.

### 6. Assemble the Aspen Sliding Joystick

Reference the Assembly Guide section in the [Maker Guide](/Documentation/Birch_Joystick_Maker_Guide.pdf) for the tools and steps required to build the device.

## Files
### Documentation
| Document             | Version | Link | 
|----------------------|---------|------------------------------------------------------------------------------------------|
| Design Rationale     | 1.0     | [Birch_Joystick_Design_Rationale](/Documentation/Birch_Joystick_Design_Rationale.pdf)    | 
| Maker Guide          | 1.0     | [Birch_Joystick_Maker_Guide](/Documentation/Birch_Joystick_Maker_Guide.pdf)     	        | 
| Bill of Materials    | 1.0     | [Birch_Joystick_Bill_of_Materials](/Documentation/Birch_Joystick_BOM.csv)     		    | 
| User Guide           | 1.0     | [Birch_Mini_Joystick-U_User_Guide](/Documentation/Birch_Joystick_User_Guide.pdf)    	    |
| Changelog            | 1.0     | [CHANGES](/CHANGES.txt)     			| 

### Design Files
 - [CAD Files](/Design_Files)

### Build Files
 - [3D Printing Files](/Build_Files/3D_Print_Files)
 - [Firmware](/Build_Files/Software/OpenAT_Joystick_Software_Birch)

## License

Everything needed or used to design, make, test, or prepare the Birch Mini Joystick is licensed under the CERN 2.0 Weakly Reciprocal license <https://ohwr.org/project/cernohl/wikis/Documents/CERN-OHL-version-2> (CERN-OHL-W).

Accompanying material such as instruction manuals, videos, and other copyrightable works that are useful but not necessary to design, make, test, or prepare the Oak Compact Joystick are published under a Creative Commons Attribution-ShareAlike 4.0 license <https://creativecommons.org/licenses/by-sa/4.0/> (CC BY-SA 4.0).

## Attribution

Contributors 
- Josie Versloot, Neil Squire. Hardware and enclosure design, coding, documentation. 
- Tyler Fentie, Neil Squire. Hardware and enclosure design. 
- Milad Hajihassan, Neil Squire. Coding.


The USB variant software utilizes the [Adafruit TinyUSB Library for Arduino](https://github.com/adafruit/Adafruit_TinyUSB_Arduino) which is made available under an [MIT license](https://github.com/adafruit/Adafruit_TinyUSB_Arduino/blob/master/LICENSE).

The documentation template was created by Makers Making Change / Neil Squire and is used under a CC BY-SA 4.0 license. It is available at the following link: https://github.com/makersmakingchange/OpenAT-Template

---

## About Makers Making Change
[<img src="https://raw.githubusercontent.com/makersmakingchange/makersmakingchange/main/img/mmc_logo.svg" width="500" alt="Makers Making Change Logo">](https://www.makersmakingchange.com/)

Makers Making Change is a program of [Neil Squire](https://www.neilsquire.ca/), a Canadian non-profit that uses technology, knowledge, and passion to empower people with disabilities.

Makers Making Change leverages the capacity of community based Makers, Disability Professionals and Volunteers to develop and deliver affordable Open Source Assistive Technologies.

 - Website: [www.MakersMakingChange.com](https://www.makersmakingchange.com/)
 - GitHub: [makersmakingchange](https://github.com/makersmakingchange)
 - X (formerly Twitter): [@makermakechange](https://twitter.com/makermakechange)
 - Instagram: [@makersmakingchange](https://www.instagram.com/makersmakingchange)
 - Facebook: [makersmakechange](https://www.facebook.com/makersmakechange)
 - LinkedIn: [Neil Squire Society](https://www.linkedin.com/company/neil-squire-society/)
 - Thingiverse: [makersmakingchange](https://www.thingiverse.com/makersmakingchange/about)
 - Printables: [MakersMakingChange](https://www.printables.com/@MakersMakingChange)

### Contact Us
For technical questions, to get involved, or to share your experience we encourage you to [visit our website](https://www.makersmakingchange.com/) or [contact us](https://www.makersmakingchange.com/s/contact).
