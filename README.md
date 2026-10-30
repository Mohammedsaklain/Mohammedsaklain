# Hi, I'm Mohammed Saklain 👋

**Embedded Firmware Engineer** · India

I build deterministic, real-time firmware for ARM Cortex-M and wireless microcontrollers, from register-level peripheral drivers and bootloaders to RTOS-based, multi-node systems with automated build pipelines.

---

## What I Do

- **Firmware engineering:** bare-metal C, FreeRTOS, modular architecture, register-level driver development
- **Communication & networking:** UART, SPI, I2C, CAN, Modbus, Ethernet (lwIP over UDP/TCP) and BLE
- **Real-time & control:** motor control, DMA circular buffers, digital filtering, deterministic execution
- **Bring-up & verification:** startup code, linker scripts, bootloaders, low-power modes and Unity unit tests on bare-metal targets
- **Engineering workflow:** Git, GitHub Actions CI for embedded builds, GCC / Makefile / CMake toolchains, OpenOCD + GDB debugging

---

## Tech Stack

| Area | Tools |
| :--- | :--- |
| **Languages** | Embedded C, C++, Python, Bash |
| **MCUs & platforms** | ARM Cortex-M (STM32, Renesas RA2E1 / RA6E1), RP2040, ESP32, ESP8266, 8051 / AVR |
| **RTOS & networking** | FreeRTOS, lwIP (UDP/TCP sockets), BLE |
| **Protocols & interfaces** | UART, SPI, I2C, CAN, Modbus, Ethernet PHY |
| **Build & CI** | STM32CubeIDE, GCC / Makefiles, CMake, Git, GitHub Actions |
| **Debug & test** | OpenOCD, GDB, SEGGER J-Link, VS Code + Cortex-Debug, Renesas e² studio, Unity |
| **Circuit simulation** | Logisim, Logic Circuit Simulator Pro, Electric Circuit Studio |

---

## Featured Work

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [**STM32F0 Bare-Metal Firmware**](https://github.com/Mohammedsaklain/STM32-DISCOVERY-F051R8T6) | Register-level drivers written from scratch, no HAL: GPIO, SysTick and timers (PWM, input capture), EXTI, UART, I2C, ADC, RTC, hardware CRC and flash. Includes a UART bootloader (framed ERASE / WRITE / JUMP protocol with checksum and a Python uploader), measured Sleep / Stop / Standby current, and Unity unit tests. | C, Cortex-M0, CMSIS, Makefiles, Unity, Python |
| [**Renesas RA6E1 Bare-Metal**](https://github.com/Mohammedsaklain/RA6E1-Bare-Metal-Programming) | Bare-metal firmware for the FPB-RA6E1 (Cortex-M33) with the GNU Arm toolchain, Make and J-Link debugging: custom startup code and linker script, register-level GPIO and SysTick, SCI UART driver in progress. | C, Cortex-M33, GNU Arm GCC, Make, J-Link |
| **Natural Language Microcontroller Programmer** | Final-year capstone: a device that lets you program development boards (ESP32, Arduino Uno/Nano) in plain English. It generates the code, compiles it and flashes the binary automatically. | Embedded C, C++, Python, AI, ESP32, Arduino |
| **Multi-Node Distributed Control & Telemetry** | A distributed embedded network on FreeRTOS with custom packet framing, checksum validation and low-latency lwIP UDP telemetry. | STM32, FreeRTOS, lwIP, Python |

---

## More Public Repositories

### Microcontroller platforms

- [**Renesas-RA2E1**](https://github.com/Mohammedsaklain/Renesas-RA2E1): FPB-RA2E1 (Cortex-M23) with Renesas FSP and e² studio: a BLINK project plus jumper and E2 Lite debugger setup notes.
- [**Renesas-RAJ306001**](https://github.com/Mohammedsaklain/Renesas-RAJ306001): getting started with Renesas' RAJ306001 motor-control IC (BLINK in the CubeSuite+ simulator).
- [**esp12f**](https://github.com/Mohammedsaklain/esp12f): ESP-12F (ESP8266) bring-up notes, four button-debounce implementations (timer, FSM, shift register, interrupt) with an RC-filter write-up, serial communication and Wi-Fi station mode.

### Embedded C & Python fundamentals

- [**Embedded-C-Programs**](https://github.com/Mohammedsaklain/Embedded-C-Programs): embedded-focused C by topic: bit manipulation, `volatile` / `const`, fixed-point arithmetic, unions and type punning, packed bitfields, function pointers, circular buffers, a memory-pool allocator and state machines.
- [**C-programs**](https://github.com/Mohammedsaklain/C-programs): C fundamentals: arrays, pointers, structures, enums, loops, Makefile setups and Project Euler problems.
- [**Python-Programs**](https://github.com/Mohammedsaklain/Python-Programs): Python for tooling and scripting: socket networking, binary data with `struct`, file handling, `os` / `psutil`, packaging, plus Kivy and Folium examples.

### Electronics & digital design

- [**Logisim-Projects**](https://github.com/Mohammedsaklain/Logisim-Projects): digital design in Logisim, including a 2-bit ALU.
- [**Logic-Circuit-Simulator-Pro**](https://github.com/Mohammedsaklain/Logic-Circuit-Simulator-Pro): digital electronics simulated in Logic Circuit Simulator Pro, with a 74-series DIP-14 IC reference.
- [**ECstudio-circuits**](https://github.com/Mohammedsaklain/ECstudio-circuits): analog circuits: voltage divider, full-wave rectifier and a water level alarm.

---

## 🌐 Connect

<a href="https://www.linkedin.com/in/mohammed-saklain">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>

I'm always happy to talk about firmware architecture, communication protocols and embedded build/test workflows.

---

*Thanks for stopping by! Let's connect, collaborate, and build something robust.*
