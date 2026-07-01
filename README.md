# Arduino LED Blinking Controller (1-Second Delay)

## Project Overview
This project demonstrates a basic LED Blinking System simulated using an Arduino Uno in Proteus 8 Professional. The system automatically turns a green LED ON and OFF at a regular interval using standard timed delays (`delay(1000)`), making it an ideal foundational project for embedded systems.

---

## Components Used
* **Arduino Uno** (Microcontroller)
* **LED-GREEN (D1)** (Visual Signal Indicator)
* **Proteus 8 Professional** (Simulation Platform)

---

## Circuit Connections

| Component / LED | Arduino Pin | Description |
|-----------------|-------------|-------------|
| **LED-GREEN (D1)** | D12 | Output Signal (Automatically blinks with 1000ms delay) |

*Note: The cathode terminal of the LED-GREEN (D1) is connected directly to the common Ground (GND).*

---

## Features
* **Automatic Timed Switching:** Automatically cycles through turning the LED HIGH (ON) and LOW (OFF) with an exact 1-second (1000ms) interval.
* **Simplistic Logic:** Uses core digital output programming (`digitalWrite`), which serves as the entry-level program for understanding GPIO operations.
* **Customizable Delay Rates:** The blinking frequency can be easily modified by changing the value within the `delay()` function in the source code.

---

## Software Requirements
* **Arduino IDE** (For writing and compiling the C++ control code)
* **Proteus 8 Professional** (For circuit layout and real-time simulation)

---

## How to Run the Simulation
1. Clone or download this project repository.
2. Open the control code file (`.ino`) in the Arduino IDE.
3. Compile the code and generate the binary file by selecting **Sketch -> Export Compiled Binary**.
4. Open the project schematic named `Screenshot 2026-07-01 194829.png` in Proteus 8 Professional.
5. Double-click the Arduino Uno board, click the folder icon under **Program File**, and select the generated `.hex` file.
6. Click the **Play / Run** button at the bottom-left corner of the Proteus window to start the automatic LED blink sequence.

---

## Simulation Preview
Below is the circuit setup capture during simulation:

<img width="1920" height="1080" alt="Screenshot 2026-07-01 194829" src="https://github.com/user-attachments/assets/5915b654-587e-4aff-aba0-4ab234cabe93" />


---

## Author
Pavithra M
