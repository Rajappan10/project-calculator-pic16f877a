# circuit
<img width="692" height="463" alt="Screenshot 2026-01-15 110421" src="https://github.com/user-attachments/assets/bb354181-92f3-4151-9528-3b683f375f37" />


## aim


The aim of this project is to design a keypad-based calculator using the PIC16F877A microcontroller with a 16×2 LCD in 4-bit mode. It reads user input from a 4×4 keypad, performs basic arithmetic operations, and displays the results on the LCD. This project demonstrates practical interfacing of input and output devices with a microcontroller.


## components required
 * PIC16F877A microcontroller
 * 16×2 LCD display
 * 4×4 matrix keypad
 * 4 MHz crystal oscillator
 * 2 × 22 pF capacitors (for crystal)
 * 10 kΩ resistor (for MCLR pull-up)
 * 10 kΩ potentiometer (for LCD contrast)
 * 5 V power supply
 * Connecting wires / breadboard or PCB
 ### procedure
 
 This program interfaces a 4×4 keypad and a 16×2 LCD with the PIC16F877A microcontroller in 4-bit mode. It scans the keypad by activating one row at a time and reading column inputs using internal pull-ups. The pressed keys are displayed on the LCD, and digits are combined to form multi-digit numbers. When the = key is pressed, the microcontroller performs the selected arithmetic operation and shows the result on the second line of the LCD. The C key clears the display and resets all values.

 #### reference
 
 https://deepbluembedded.com/
