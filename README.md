<p align="center">
  <img src="./banner.svg" alt="Hafizul Husni, Embedded / Firmware Engineer" width="100%">
</p>

<p align="center">
  <b>Embedded &amp; Firmware Engineer · Selangor, Malaysia</b><br>
  Writing C that talks straight to the hardware, plus the software around it.
</p>

<p align="center">
  <a href="https://github.com/PijoyXryo/stm32-bare-metal"><img src="https://img.shields.io/badge/01-BARE--METAL_FIRMWARE-3ddc97?style=for-the-badge&labelColor=0a100e" alt="01 Bare-metal firmware"></a>
  <a href="https://github.com/PijoyXryo/monthly-commitment-calculator"><img src="https://img.shields.io/badge/02-DESKTOP_SOFTWARE-ffb547?style=for-the-badge&labelColor=0a100e" alt="02 Desktop software"></a>
  <a href="https://github.com/PijoyXryo?tab=repositories&language=javascript"><img src="https://img.shields.io/badge/03-WEB_%2F_NODE-7aa2ff?style=for-the-badge&labelColor=0a100e" alt="03 Web / Node"></a>
</p>

<p align="center">
  <a href="https://github.com/PijoyXryo?tab=repositories">All repositories</a>
</p>

<p align="center">
  <img src="./workflow.svg" alt="How I build: read, register, driver, test, ship" width="100%">
</p>

I'm **Hafizul**, an embedded and firmware engineer. I like the part of engineering where you open a 1,700-page reference manual, find the right register and make the hardware do exactly what you want, with **no HAL and no magic**. I also build desktop and web tools in Python and JavaScript, because good firmware still needs good software around it.

My **STM32 bare-metal driver project** is the main one. It's built from the startup code up and verified in the Renode simulator, so anyone can run it without a board.

## Selected work

| | Project | What it shows | Stack |
|:-:|---|---|---|
| **01** | [**stm32-bare-metal**](https://github.com/PijoyXryo/stm32-bare-metal) | Startup code, vector table, linker script and a UART driver written from the reference manual. Runs in Renode. Interrupt-driven RX, GPIO/SysTick and CI are in progress. | C · ARM Cortex-M4 · Make · Renode |
| **02** | [**monthly-commitment-calculator**](https://github.com/PijoyXryo/monthly-commitment-calculator) | Modular desktop app with a custom calendar widget, income-load meter, dark/light theme, and CSV + PDF report export. | Python · customtkinter · ReportLab |
| **03** | [**clinic-app**](https://github.com/PijoyXryo/cllinic-app) | Node.js clinic report showing age-based fee rules and follow-up date scheduling. | JavaScript · Node.js · Day.js |

## Toolbox

<p>
  <img src="https://img.shields.io/badge/C-0a100e?style=flat-square&logo=c&logoColor=3ddc97">
  <img src="https://img.shields.io/badge/ARM_Cortex--M-0a100e?style=flat-square&logo=arm&logoColor=3ddc97">
  <img src="https://img.shields.io/badge/STM32-0a100e?style=flat-square&logo=stmicroelectronics&logoColor=3ddc97">
  <img src="https://img.shields.io/badge/Renode-0a100e?style=flat-square&logoColor=3ddc97">
  <img src="https://img.shields.io/badge/Make-0a100e?style=flat-square&logo=gnu&logoColor=3ddc97">
  <img src="https://img.shields.io/badge/Python-0a100e?style=flat-square&logo=python&logoColor=ffb547">
  <img src="https://img.shields.io/badge/JavaScript-0a100e?style=flat-square&logo=javascript&logoColor=ffb547">
  <img src="https://img.shields.io/badge/TypeScript-0a100e?style=flat-square&logo=typescript&logoColor=ffb547">
  <img src="https://img.shields.io/badge/React-0a100e?style=flat-square&logo=react&logoColor=ffb547">
  <img src="https://img.shields.io/badge/Git-0a100e?style=flat-square&logo=git&logoColor=7aa2ff">
  <img src="https://img.shields.io/badge/Linux-0a100e?style=flat-square&logo=linux&logoColor=7aa2ff">
</p>

## Currently working on

- Interrupt-driven UART RX with a unit-tested ring buffer
- GPIO and SysTick drivers
- Automated Renode tests running in GitHub Actions
