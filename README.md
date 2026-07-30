# STM32 Clean LED Animation 🚀

This repository shows my next huge step in my Embedded Systems journey! After my initial Arduino projects, I am finally stepping into the professional 32-bit ARM Cortex-M4 world with STM32. 

Instead of using standard processor-halting delays (like `HAL_Delay`), this project demonstrates a clean, "non-blocking" loading bar LED animation using the system tick timer.

## Hardware Configuration
* **Microcontroller:** STM32F407G-DISC1 Board (STM32F407VGT6)
* **Indicators:** 4x Onboard LEDs (Green, Orange, Red, Blue)
* **Connection:** GPIOD Pins (PD12, PD13, PD14, PD15)
* **Clock Speed:** 168 MHz (Maximum performance achieved using external 8 MHz HSE crystal and PLL)

## Software Architecture
* **Framework:** STM32 HAL Library
* **Logic:** Non-blocking state machine using `HAL_GetTick()` to keep the processor free for other tasks.

## Personal Note
It makes me feel really excited to step into the ARM architecture and transform my theoretical knowledge from Gebze Technical University into industrial-grade software practices. Writing clean code without freezing the processor is a great milestone for me. I am looking forward to what can I develop more on this powerful board in next days in sha Allah. Stay tuned!
