## **19 Juni 2023**  
initial project, 
make electronic design for Simple high voltage AC controller with SSR and avr (ATMega16). use [Mighty Core](https://github.com/MCUdude/MightyCore).   
**GOAL**
  1. device can control delivered power of AC voltage, controlled by AVR ATMega16
  2. add simple tft/oled display to device
  3. add input to uC
  4. add USB-Serial to device, 
  5. if posible, manufacture design with PCB factory service
  6. and so on...
## **20 Juni 2023**  
learn about recomended _hardware design consideration AVR by ATMEL_.
- in avr there 2 power supply: digital and analog, for digital supply, avr will draw just few miliamps for each clock, each clock will draw current and make spike current, the more I/O used at eachtime more spike current will drawn by device. so if power is delivered with long distance, there need to add inductor (ferrite bead) for prevent down. atmel was give recomended schematic for that.

![digital supply recomended by atmel](img/fig1_digitalSupply.png )
