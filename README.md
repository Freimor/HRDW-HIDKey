## HID Key
A HID device for loadout system with a setup script. Made for the OPS team of School 21. This device allows to easily set up new workstations with just one keychain-like device. Before that the team used Arduino Micro with a bulky case and a usb cable. That device connects to MAC via Type-C, it is protected from electrostatic discharge, has an additional programmable button, an RGB LED and is very small in size.

The project is completed in Q3 2021.

<img src="https://user-images.githubusercontent.com/21167984/193593493-8cdf39be-4885-4ba6-a70c-4b82b353fef2.PNG" width="200"> <img src="https://user-images.githubusercontent.com/21167984/193795669-d742e2fb-d2b0-4742-b1b7-ab67f8b81542.png" width="200">

## Parameters for PCB order (JLCPCB compatible)
0.8mm thickness

0.3mm min hole size

## BOM list
| №  | Designator      | Qty | Description         | Manufacturer      | Name           | Package   | Link |
| -- | --------------- | --- | ------------------- | ----------------- | -------------- | --------- | ---- |
| 1  | C1              | 1   | 10uf MLCC           |                   |                | 0402      |      |
| 2  | C2,C3           | 2   | 14pf MLCC           |                   |                | 0402      |      |
| 3  | C4,C5,C7,C9,C10 | 5   | 100nf MLCC          |                   |                | 0402      |      |
| 4  | C6,C8           | 2   | 1uf MLCC            |                   |                | 0402      |      |
| 5  | R1              | 1   | 1MΩ smd             |                   |                | 0402      |      |
| 6  | R2              | 1   | 5.1kΩ smd           |                   |                | 0402      |      |
| 7  | R3,R4           | 2   | 22Ω smd             |                   |                | 0402      |      |
| 8  | R5,R6,R12       | 3   | 10kΩ smd            |                   |                | 0402      |      |
| 9  | R7,R8,R9,R10,R11| 5   | 1kΩ smd             |                   |                | 0402      |      |
| 10 | D1              | 1   | ESD protection chip | Nexperia          | IP4220CZ6      | TSOP6     |      |
| 11 | D2              | 1   | Yellow smd led      |                   |                | 0402      |      |
| 12 | D3              | 1   | Green smd led       |                   |                | 0402      |      |
| 13 | D4              | 1   | RGB smd led         | Foshan NationStar | FM-B2020RGBA-HG| 2020      |      |
| 14 | J1              | 1   | USB Type-C 24pin    | XKB Connectivity  | U261-241N-4BS60|           |      |
| 15 | SW1, SW2        | 2   | Tactile switch      | KLS Electronic    | KLS7-TS5401    |           |      |
| 16 | U1              | 1   | 8bit microcontroller| Atmel             | ATmega32u4     | QFN44     |      |
| 17 | Y1              | 1   | 16mhz crystal       | CREC              |                | SMD02520C4|      |
