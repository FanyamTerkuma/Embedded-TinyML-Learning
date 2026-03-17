# Phase 2: Firmware Programming & Advanced Embedded

## Goal

Drop Arduino abstractions and write firmware the way professionals do.

## Timeline and Schedule (8 Weeks)

| Period | Focus | Key Tasks | Milestone |
|---|---|---|---|
| Wk 1-2 | Bare-Metal C (no Arduino) | Quantum Leaps free YouTube course videos 1-6. Code along in Wokwi bare-metal style. Learn registers and direct GPIO access. | LED control without digitalWrite |
| Wk 3-4 | Interrupts, Timers, PWM Deep Dive | Custom LED dimmer with hardware timer and button ISR project. Learn NVIC, timer peripherals, hardware debounce. | Hardware timer PWM demo |
| Wk 5-6 | ADC, UART, Low Power Modes | Data logger storing values in an array, serial communication simulation. Learn sleep modes and power optimization basics. | Serial data logger project |
| Wk 7-8 | FreeRTOS Introduction | Two tasks (sensor read + display update) with queue. Capstone: multi-task plant monitor firmware. Learn tasks, semaphores, queues. | FreeRTOS plant monitor running |

## Expected Outcome

Professional-quality bare-metal firmware plus FreeRTOS multitasking.

## Resources

Phase resources are organized in [resources/README.md](resources/README.md).
