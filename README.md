# STM32-ThrusterTesting

Simple and clean firmware to control **8 thrusters** using STM32F103 (Blue Pill) with TIM1 and TIM2 PWM.

## Features
- 8 independent PWM channels (1100–1900 µs)
- Centered at 1500 µs (neutral/stop)
- Built-in test loop that ramps each thruster up and down

## Hardware
- MCU: STM32F103C8T6 (Blue Pill)
- Timers: TIM1 (CH1–CH4) + TIM2 (CH1–CH4)
- ESCs: Any standard ESC
- Power Source (depend on your ESCs)

<img width="6798" height="3205" alt="STM32 to ESC Thruster-2026-05-21-070319" src="https://github.com/user-attachments/assets/ede63e09-bec1-425c-aa73-cd2291c47706" />
