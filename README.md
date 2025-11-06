# Temperature Sensor Interfacing and Real-Time Fan Control Using PIC24

## Project Overview

This project demonstrates the development of a temperature-sensing control system using a TMP36 analog temperature sensor and a PIC24 microcontroller. The system reads temperature data, digitizes it using the microcontroller’s ADC, and implements real-time fan control based on predefined temperature thresholds.  

The project showcases embedded system design, microcontroller programming, analog-to-digital conversion, and sensor-driven automation.

---

## System Design

### Hardware Components
- **TMP36 Analog Temperature Sensor:** Provides an analog voltage proportional to temperature.  
- **PIC24 Microcontroller:** Reads analog temperature, executes control logic, and communicates via UART.  
- **Fan (DC or PWM controlled):** Activated when temperature exceeds threshold.  
- **Components** LEDs for status indication, resistors for pull-ups, and breadboard for prototyping.

### Software Components
- **C/Embedded C:** For programming the PIC24 microcontroller.  
- **MPLAB X IDE / XC16 Compiler:** For firmware development and debugging.  
- **UART Serial Communication:** Asynchronous communication for monitoring temperature values in real-time.  
