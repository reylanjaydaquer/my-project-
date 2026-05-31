**PROJECT TITLE**

**ESP32-DevKit-V1 Custom Board with Regulated Power Supply & Mode Selector**

## Project Description

This project is a custom-designed printed circuit board (PCB) based on the ESP32-DevKit-V1 development module. It is designed for embedded systems, IoT prototyping, and general electronics engineering use. The board includes a complete 5V regulated power supply circuit using the AMS1117-5.0 voltage regulator, input power jack, main power switch, and a DPDT slide switch for selecting between two operating modes or signal paths. The layout follows best practices: proper power filtering, stable regulation, short direct traces, clear ground planes, and all GPIO pins broken out to standard headers — making it a reliable, compact, and fully functional development platform.

## Features

* ESP32-DevKit-V1 compatible design
* 5V regulated power supply using AMS1117-5.0
* DC input power jack
* Main power ON/OFF switch
* DPDT slide switch for mode selection
* Power filtering capacitors for stable operation
* Standard header pin breakout for all GPIOs
* Compact and organized PCB layout
* Suitable for embedded systems and IoT applications
* Easy integration with sensors and external modules
* # pcb image/screenshots
* ![image](https://github.com/reylanjaydaquer/my-project-/blob/cb6a95e606846f01cd4274cb37c80f7f2b474182/Screenshot%202026-05-30%20204940.png)
* ![image](https://github.com/reylanjaydaquer/my-project-/blob/3d7e81f39fca781b86bd795ce1b05214a89414ac/Screenshot%202026-05-30%20205033.png)
* ![image](https://github.com/reylanjaydaquer/my-project-/blob/f4dbc170a39238fc94ff2b5b1a73d7cdbb1c611e/Screenshot%202026-05-30%20205130.png)
* ## Features

| ESP32-DevKit-V1 Module | 5V Regulated Power Supply | DC Power Input  |
| ---------------------- | ------------------------- | --------------- |
| Main Power Switch      | Mode / Signal Selector    | Power Filtering |
| Full I/O Breakout      | Organized Layout          | Compact Design  |

## Components Used

| Reference | Component Name                                             |
| --------- | ---------------------------------------------------------- |
| U1        | ESP32-DevKit-V1 (30-pin Wi-Fi/Bluetooth Module)            |
| U2        | AMS1117-5.0 (5V / 1A Voltage Regulator)                    |
| U3        | MINI-SPDT-SW (Power ON/OFF Switch)                         |
| U4        | POWER-JACK (2.1mm DC Input Jack)                           |
| U5        | MTSW-102-10-L-D-472-RA (DPDT Slide Switch — Mode Selector) |

*The lower part of the image is cut off, so components below U5 are not visible.*
**Components Used (continued)**

| Reference     | Component Name                                               |
| ------------- | ------------------------------------------------------------ |
| C2, C4        | 100nF Ceramic Capacitor                                      |
| C3, C5        | 10µF Electrolytic Capacitor                                  |
| Headers       | 2×15 Female Headers (2.54mm pitch, for all GPIO pins)        |
| Miscellaneous | Mounting holes, ground plane, silkscreen labels, solder pads |

## Software Used

• EasyEDA —

## Author Name

**REYLAN DAQUER**

## Course & Section

**Electronics Engineering — [EN1A]**
