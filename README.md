# OpenPowerMeter
An open source power meter design including hardware and software

This is an open source power meter design. It is compatible with the **YHDC SCT-013-000** current clamp to measure AC mains current without contact. Optionally, 3 phase mains voltage can be measured by connecting it to the bottom screw terminal. The PCB is designed to fit into the Bopla CNC 87.5 DIN rail casing and consists on a lower and upper half of hardware which fit together through 2.54 mm pinheaders.

![alt text](https://github.com/MKroen93/OpenPowerMeter/blob/main/analogue_frontend/Power_Meter.png?raw=true)

The lower part contains the analog frontend for converting the input signals to true rms values and for converting the input waveforms to a rectangular 3.3V output signal which can be used to detect the phase using a simple timer.

![alt text](https://github.com/MKroen93/OpenPowerMeter/blob/main/esp32_mcu_board/ESP32_MCU_Board.png?raw=true)

The upper part contains the MCU (ESP32) and ADC and is not yet finished.

**Please note:** This project is currently in early development and not yet tested or ready to be used.
