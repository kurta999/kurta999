# Hi, I'm Attila 👋

**Embedded Software Engineer** — C/C++ firmware by trade, full-stack when the project needs it.

I've been writing embedded software since 2017, currently at **compact electric GmbH**, where I build firmware for **STM32H5-based grid protection systems** in the energy sector. Before that I spent a few years in automotive (AUTOSAR, C++) and industrial software.

I like problems that touch both sides of the wire: a microcontroller measuring something real, and a decent interface on top of it that someone can actually use.

Most of my day-to-day work lives in private repos at compact electric — the contribution graph here only shows the tip of it.

---

## 🔧 What I work with

**Embedded**
`C` `C++20` `STM32` `ESP32` `AVR` `ARM Cortex-M` `FreeRTOS` `ThreadX` `HAL / LL` `Driver development` `CMSIS-DSP / FFT` `Bootloaders & FOTA` `MISRA C` `AUTOSAR`

**Protocols & Comms**
`CAN` `ISO-TP` `UDS` `SOME/IP` `Modbus` `RS485` `UART / SPI / I²C` `USB` `BLE` `LoRa` `Ethernet` `lwIP` `NetX Duo` `mDNS / DHCP` `MQTT` `WebSocket / REST` `TLS`

**Backend & Tooling**
`Node.js` `gRPC / Protobuf` `Python` `Boost` `Asio` `SQL` `SQLite` `PostgreSQL` `Docker` `Linux` `Yocto` `Raspberry Pi`

**Frontend & Desktop**
`React` `TypeScript` `Qt` `wxWidgets`

**Workflow**
`Git` `Gerrit` `CMake` `GitHub Actions` `Jenkins` `Doxygen` `JTAG/SWD debugging` `Oscilloscope + logic analyzer`

**Design & Practices**
`OOP` `SOLID` `DRY` `KISS` `Design patterns` `Data structures & algorithms` `Code reviews` `Mentoring`

**Testing & Quality**
`GoogleTest` `libFuzzer` `ASan/UBSan` `CodeQL` `vcpkg`

---

## 📌 Projects

| Project | What it is |
| --- | --- |
| [**AirQualitySensors**](https://github.com/kurta999/AIrQualitySensors) [![CI](https://github.com/kurta999/AIrQualitySensors/actions/workflows/build.yml/badge.svg)](https://github.com/kurta999/AIrQualitySensors/actions/workflows/build.yml) | STM32L476 air quality sensor hub — BME680, SCD30, VEML6070, TCS34725 and an HPMA115S0 particle sensor on FreeRTOS, ST7565 display, UART or ESP32 Wi-Fi uplink into WindowsAddon for SQLite logging and graphs |
| [**CanUsbTransceiver**](https://github.com/kurta999/CanUsbTransceiver) [![CI](https://github.com/kurta999/CanUsbTransceiver/actions/workflows/ci.yml/badge.svg)](https://github.com/kurta999/CanUsbTransceiver/actions/workflows/ci.yml) | A cheap CAN ↔ USB transceiver — hardware and firmware |
| [**SpiToEthBridge**](https://github.com/kurta999/SpiToEthBridge) [![CI](https://github.com/kurta999/SpiToEthBridge/actions/workflows/build.yml/badge.svg)](https://github.com/kurta999/SpiToEthBridge/actions/workflows/build.yml) | STM32H563ZI firmware that bridges a slave SPI data stream to UDP/Ethernet (ThreadX + NetX Duo) for high-throughput, real-time bus debugging over the network |
| [**WindowsAddon**](https://github.com/kurta999/WindowsAddon) [![CI](https://github.com/kurta999/WindowsAddon/actions/workflows/ci.yml/badge.svg)](https://github.com/kurta999/WindowsAddon/actions/workflows/ci.yml) | Windows tray toolbox for automotive/embedded dev: CAN/UDS transceiver, Modbus master, macro engine, and QoL tools |
| [**MyVibeGTA**](https://github.com/kurta999/MyVibeGTA) [![CI](https://github.com/kurta999/MyVibeGTA/actions/workflows/windows-release.yml/badge.svg)](https://github.com/kurta999/MyVibeGTA/actions/workflows/windows-release.yml) | Mini City 3D — a C++17 Windows city sandbox with Direct3D 11 and optional native Direct3D 12 + AMD FSR2, Jolt Physics, XAudio2, Dear ImGui menus, Lua missions, vehicles, wildlife, combat, destructible buildings, mining/crafting builder mode, and Tracy CPU/GPU profiling |
| [**VibePhotoEditor**](https://github.com/kurta999/VibePhotoEditor) [![CI/CD](https://github.com/kurta999/VibePhotoEditor/actions/workflows/ci-release.yml/badge.svg)](https://github.com/kurta999/VibePhotoEditor/actions/workflows/ci-release.yml) | Private browser and Electron photo editor with camera-inspired looks, curves/HSL, selective masks, Magic Eraser, HEIC/HEIF support, and folder editing; GitHub Actions CI/CD tests and publishes Node.js archives and portable Windows EXEs |
| [**CDMRE_N**](https://github.com/kurta999/CDMRE_N) | English manual for compact electric's CDMRE & CDMRN — I wrote the firmware |
| [**WortWerk**](https://github.com/kurta999/WortWerk) [![CI](https://github.com/kurta999/WortWerk/actions/workflows/android.yml/badge.svg)](https://github.com/kurta999/WortWerk/actions/workflows/android.yml) | Native Android app teaching basic German to Hungarian speakers — illustrated word cards, bilingual sentences, and matching exercises |
| [**HunqzSimulator**](https://github.com/kurta999/HunqzSimulator) | Python side project |
| [**MFR**](https://github.com/kurta999/MFR) | MaXXiMuM FreeRoam — a once-popular Hungarian SA-MP gamemode; I reconstructed the lost schema/sources so the ~67k-line codebase compiles again |
| [**YSF**](https://github.com/kurta999/YSF) | Server functions plugin for SA-MP — I maintained it for years, then handed it over to [IS4Code](https://github.com/IS4Code) |

---

## 🏢 Experience

**Software Engineer (Embedded & Full Stack)** · compact electric GmbH, Vienna · *2023 – present*
Grid protection systems for power plant environments on STM32H5: real-time control logic, DSP, firmware and web-based configuration/monitoring. Two industrial products taken from concept to mass production. Currently leading a 3-phase waveform generator — STM32 firmware, Raspberry Pi backend (Node.js, gRPC, Modbus, Python), React frontend.

**C++ Software Engineer** · GlobalLogic s.r.o., Žilina · *2021 – 2023*
Automotive components in an AUTOSAR environment. Built a CAN simulation tool that let the team run client test cases without CANoe, and stabilized a legacy remote diagnostics codebase. SOME/IP, UDS, ISO-TP, Yocto, embedded Linux.

**Embedded Software Engineer / Application Developer** · effman s.r.o., Dunajská Streda · *2017 – 2021*
Intelligent waste water treatment systems, an indoor air quality sensor that went to market, reusable drivers (EEPROM, flash, SPI displays, ESP8266/ESP32, GSM, external ADCs), AVR → STM32 ports, and FFT-based acoustic monitoring of bee colonies with CMSIS-DSP.

---

## 🎮 Before all that: GTA San Andreas

*2009 – 2016* — I ran a large SA-MP multiplayer server, and that's where I actually learned to program.

It started with PAWN scripting and turned into C++ plugins: RakNet, UDP/TCP, binary bitstream serialization, real-time state sync between clients and server. Reverse engineering the game to add custom vehicles, weapon behavior and world interactions. Packet inspection to find cheats and exploits. Plus the unglamorous half — hosting, a web stack and forum, moderating, and keeping a community together.

No paycheck, but it's the reason the rest of this page exists.

---

## 💼 Open to freelance work

I take on small to mid-sized projects alongside my main role, fully remote:

- **Embedded & electronics** — firmware, board bring-up, protocol work, prototyping
- **Full-stack** — internal tools, dashboards, APIs, desktop apps, webpages, UI/UX
- **Automation** — scripting, data pipelines, glue between systems that don't talk to each other

If you have something that fits, get in touch.

---

## 🌍 Languages

🇭🇺 Hungarian (native) · 🇬🇧 English (C1) · 🇸🇰 Slovak (C1) · 🇨🇿 Czech (B2) · 🇩🇪 German (A1)

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kiss-attila111/)
[![Email](https://img.shields.io/badge/Email-nmsstulaj%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:nmsstulaj@gmail.com)

---

<sub>Away from the keyboard: lifting, running, gardening, welding, cooking, and making my own wine. 🍷</sub>
