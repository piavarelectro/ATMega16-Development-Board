# ATMega16-Development-Board
A DIY ATMega16 Development Board For Students - https://piavarelectro.com/a-diy-atmega16-development-board-for-students/
## ATMega16 AVR Development Board For Students And Hobbyists
### Overview 
After a few years of making the AVR microcontroller programming and prototyping on the breadboard. I decided to design a development board for the Atmel AVR that contain most of my previous experiment.

[![The completed assembling of the ATMega16 development board](https://github.com/piavarelectro/ATMega16-Development-Board/blob/main/20201101_171200.jpg "The completed assembling of the ATMega16 development board")](https://piavarelectro.com/a-diy-atmega16-development-board-for-students/ "The completed assembling of the ATMega16 development board")

### Features
I putted many blocks containing many components, easing the prototyping works.
1. Power Supply
2. Basic Parts Of MCU
3. RS-232
4. Digital Input And Output
5. External Interrupts
6. LED Display
7. LCD Display
8. LCD Display
9. Analog Inputs
10. Serial Peripheral Interface
11. Two Wire Interface

#### Power Supply
The power supply block fed from a DC/DC converter at the voltage of +12V. This input voltage will be converted to a +5V and a +3.3V outputs.
The +5V output supplies the microcontroller and other onboard devices. Optionally, the +3.3V output supplies to other +3.3V devices outside the board.
#### Basic Parts Of MCU
A 16MHz crystal clock is soldered with the MCU, yielding a 16MIPS executing speed. A reset circuit is already puted on board. The reset button triggers a reset signal whenever it's pressed by the user. An ISP socket allows the programm uploading to the microcontroller. It's a 10-pins  IDC socket compatiable with the USBasp.
#### RS-232
The traditional RS-232 communication port could become very classic today. However I stil use it due the rich of the MAX232 driver IC in my warehouse.
#### Digital Input And Output
PORTA is selected as a digital input PORT. The input is changed by switching the connected on-board DIP switch ON and OFF.
PORTB outputs its digital data to the Light Emitting Diodes, crossing a DIP switch.
#### External Interrupts
The external interrupts of the ATMega16 are INT0, INT1 and INT2. Three input buttons trigger the interrupt respectively.
#### LED Display
The LED display is a six digits multiplexed display. The digits are common cathode type, green color with the size of 0.4". PORTB displays the segments while PORTC controls the digits.
#### LCD Display
A 16x2 HD44780 LCD display assembed on this board. It's controlled by PORTC in 4-bit data mode.
#### Analog Inputs
The analog input fed from two analog input devices, a POT and a LM35DZ analog temperature sensor.
#### Serial Peripheral Interface
The Serial Peripheral Interface (SPI) of this board is the MCP4922 dual 12-bit  Digital to Analog Converter (DAC). The two analog voltage outputs connect to the outside device.
#### Two Wire Interface
The Two Wire Interface (TWI) Communication protocol allow the communication between the master MCU and its slave device via two wires on a single bus. The TWI slave devices here are, a DS1307 RTC and a AT24C16 EEPROM.

For more information [click here](https://piavarelectro.com/a-diy-atmega16-development-board-for-students/ "click here") to see the details.
