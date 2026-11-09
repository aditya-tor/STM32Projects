## Project 1: OnboardLED
- This project implements blinking of the onboard LED of STM32 Nucleo G474RET6 using STM 32 HAL library.
- The project was configured using STM32CubeMX and developed in STM32CubeIDE.
- The microcontroller pin 'PA5' was configured as it is internally mapped to the onboard user LED 'LD2'.
- <img width="567" height="572" alt="Screenshot 2026-08-26 212946" src="https://github.com/user-attachments/assets/9e575857-ab03-41a3-8f82-509269da9ba6" />
- The target output of blinking the onboard LED is achieved by toggling its state using HAL_GPIO_TogglePin() function and implementing a delay using HAL_Delay() function.

## Project 2: ExternalLED
- This project implements blinking of an external LED, wired on a breadboard, using STM32 Nucleo G474RET6 using STM 32 HAL library.
- The hardware includes a red LED and a 330Ω resistor connected in series.
- Anode of the LED is connected to the microcontroller pin 'PB0' which is mapped to the Arduino 'A3' header pin.
- <img width="488" height="568" alt="Screenshot 2026-08-26 213032" src="https://github.com/user-attachments/assets/5510f621-3f30-44ee-a2d2-1195193c4c22" />

- Cathode of the LED is connected to the resistor. The other terminal of the is connected to the GND to complete the circuit.
- The blinking implemented uses the same logic as that of the OnboardLED project


