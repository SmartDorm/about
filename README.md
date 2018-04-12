# About SmartDorm

SmartDorm is an IoT device designed to control various things in a dorm room. This project will be submitted to ECESS Spark Challenge. It is gonna be awesome!

### Features

Features right now include the following:
- Getting Weather (Sync with Online)
- Voice Input (Microphone)
- Output to a Display
- Voice regonition
- Timer / Alarm 
- Controllable Volume
- Control Lights
- Fan for Primitive Temperature Control
- Android App for Administrative Control

### Hardware
- STM32F0-Discovery Board
- NHD-0216K3Z-FL-GBW-V3

### Peripherals
- TIM (Timer)
  - Drive a real time clock in the board
- GPIO
  - Drive feeback LEDs
  - Used for other peripherals
- SPI (Serial Peripheral Interface)
  - STM32F0 Board and an LCD Display 
  - Ethernet
- UART (Serial TX/RX)
  - Bluetooth TX/RX
- I2S
  - Audio Speakers (Music)
- DAC (Digital to Analog Converter)
  - Audio Speakers (Alarm)

### Software
- STM32F0-Discovery Hardware Abstraction Layer (HAL)
- Embedded C Programming
- Android Studio (Associated App)
