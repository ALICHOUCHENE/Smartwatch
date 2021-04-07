<div align="center"><h1 style="font-family: courier;" align="center"></h1></div>
<div align="center"><img src="image/Capture.png" width="70%"></div>

# Description
Smartwatch circuit for health and fitness
This robust fitness watch was designed for football players who leads an active lifestyle and values health and well-being. 
The watch creates for a personal training plan that adapts to some fitness needs. 
This smart-watch will provide a real-time guidance while exercising to help the player at the right intensity.
24/7 activity tracking with steps, calories and sleep, together with stress and recovery monitoring, provide a real time heart rate monitoring and help to maintain a healthy balance between activity and rest.

Here the features of the board:

- Xtensa dual-core 32-bit LX6 microprocessor(WROOM-32D) is the CPU of the board. operating at 240 MHz.
- Optical Sensor IC,BH1792GLC, a heart rate monitor module integrated with LED driver, green light, and IR detection photodiode.
- 1Cell / 3.7V 230mA Battery Management System / BMS Over Voltage, Over Current, Short Circuit Protection Module for Lithium ION Batterie.
- UART programming interface.
- I2C interface for OLED display.
- USB port for charging.

 # Manufacturing
 
After finishing the Routing and verify the pcb. We made the board at JLC PCB and we chose also the PCB Assembly service.
Here is the **[BOM](https://github.com/ALICHOUCHENE/Smartwatch-/blob/main/Assembly/BOM.csv)** needed for jlcpcb assembly service:

| Designator | Value           | Footprint                                                                        | LCSC Part |
|------------|-----------------|----------------------------------------------------------------------------------|-----------|
| U2         | TP4056          | Package_SO:SO-8_3.9x4.9mm_P1.27mm                                                | C16581    |
| R5         | 1.2K            | 402                                                                              |  C25862   |
| R7         | 1K              | 402                                                                              | C11702    |
| R8         | 1K              | 402                                                                              | C11702    |
| R4         | 1K              | 402                                                                              | C11702    |
| C2         | 0.1UF           | 402                                                                              |  C1525    |
| R6         | 100             | 402                                                                              |  C25076   |
| C3         | 0.1UF           | 402                                                                              |  C1525    |
| U1         | FS8205A         | Package_SO:TSSOP-8_4.4x3mm_P0.65mm                                               | C16052    |
| R2         | 3.3K            | 402                                                                              |  C25890   |
| R3         | 3.3K            | 402                                                                              |  C25890   |
| R1         | 3.3K            | 402                                                                              |  C25890   |
| C4         | 100nF           | 402                                                                              |  C1525    |
| R9         | 10K             | 402                                                                              |  C25744   |
| U4         | ESP32-WROOM-32D | RF_Module:ESP32-WROOM-32                                                         |           |
| U3         | DW01-P          | Package_TO_SOT_SMD:SOT-23-6                                                      | C181096   |
| C1         | 0.1UF           | 402                                                                              |  C1525    |
| J1         | USB_OTG         | Connector_USB:USB_Mini-B_Lumberg_2486_01_Horizontal                              | C136451   |
| BZ1        | Buzzer          | Buzzer_Beeper:Buzzer_Murata_PKMCS0909E4000-R1                                    | C255319   |
| R11        | 330             | 402                                                                              |  C25104   |
| R10        | 330             | 402                                                                              |  C25104   |
| SW1        | SW_DIP_x01      | Button_Switch_SMD:SW_DIP_SPSTx01_Slide_6.7x4.1mm_W6.73mm_P2.54mm_LowProfile_JPin | C54948    |
| D2         | LED             | 402                                                                              |           |
| D4         | LED             | 402                                                                              |           |
| D3         | LED             | 402                                                                              |           |
| Q2         | BC847           | Package_TO_SOT_SMD:SOT-23                                                        | C8664     |
| Q3         | BC847           | Package_TO_SOT_SMD:SOT-23                                                        | C8664     |
| U5         | AMS1117-3.3     | Package_TO_SOT_SMD:TSOT-23                                                       | C83932    |
| C5         | 0.1UF           | 402                                                                              |  C1525    |


# Downloads

* [Board schematics](https://github.com/ALICHOUCHENE/Smartwatch-/blob/main/Schematic.pdf)

* [PCB layout](https://github.com/ALICHOUCHENE/Smartwatch-/blob/main/Smartwatch.kicad_pcb)

* [BOM](https://github.com/ALICHOUCHENE/Smartwatch-/blob/main/Assembly/BOM.csv)

* [Position file](https://github.com/ALICHOUCHENE/Smartwatch-/blob/main/Assembly/Smartwatch-all-pos.csv)

* [Gerber File](https://github.com/ALICHOUCHENE/Smartwatch-/blob/main/Gerber/Gerber.rar)
