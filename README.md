# 👋 Marek Czelen

**Principal Embedded Systems Engineer & System Architect**  
📍 Kraków, Poland | 🌐 [GitHub](https://github.com/marek-czelen) | 💼 [LinkedIn](https://linkedin.com/in/marek-czelen)

---

> I design complete systems that connect real hardware with reliable software — from MCU timers and MOSFET gate drivers to globally deployed enterprise platforms.

---

## 🎯 Profile

With **20+ years of engineering experience**, I architect and build systems across the full stack: bare-metal and RTOS firmware, power electronics and motor control, communication protocols, distributed engineering platforms, web applications, mobile apps, and applied AI. I am most effective at the boundary where physical hardware meets software that must control, measure, and explain it.

**What sets me apart:** I own the system from interrupt-level timing and PCB diagnostics all the way to globally distributed enterprise architecture. My public repositories document real engineering work — including design decisions, oscilloscope-led debugging, limitations, and next steps — not polished prototypes.

---

## 📊 Impact by the Numbers

| Metric | Value |
|---|---|
| **Global engineering platform** | 1,000+ users, ~100,000 equipment assets, ~1M process instances |
| **Embedded products shipped** | Firmware for tools in 2,000+ measurement cards |
| **Communication protocol throughput** | ~3,000 requests/second for distributed occupancy detection |
| **Global deployment scope** | Systems deployed across Europe, USA, Mexico, and China |
| **AI research publication** | Springer: ~80% recognition accuracy with 3 cooperating neural networks |

---

## 🛠️ Core Competencies

### Embedded Firmware & Low-Level Systems
| Skill | Evidence |
|---|---|
| **C / C++** bare-metal & RTOS firmware | [`bldc_driver_v3_m365`](https://github.com/marek-czelen/bldc_driver_v3_m365), [`bldc_driver_v2_stm`](https://github.com/marek-czelen/bldc_driver_v2_stm), [`bldc_driver_esp32`](https://github.com/marek-czelen/bldc_driver_esp32) |
| **STM32** (F1, F4), **ESP32**, **NXP**, **AVR**, **PIC** | All BLDC driver repos — register-level, no HAL |
| **TIM1 advanced timer**, complementary PWM, COM events | `bldc_driver_v3_m365` — atomic commutation |
| **MCPWM**, **ADC**, **DMA**, **EXTI**, **USART** | `bldc_driver_esp32` — IRAM-safe 20 kHz TEZ ISR |
| **Bootloaders**, **HAL**, **device drivers**, **memory optimization** | Professional work at APTIV |
| **Embedded Linux**, **FreeRTOS** | Professional experience |

### Motor Control & Power Electronics
| Skill | Evidence |
|---|---|
| **BLDC 6-step block commutation** | All three BLDC repos |
| **Sinusoidal PWM (SPWM/DPWM)** with Hall interpolation | [`bldc_driver_v3_m365`](https://github.com/marek-czelen/bldc_driver_v3_m365), [`bldc_driver_v2_stm`](https://github.com/marek-czelen/bldc_driver_v2_stm) |
| **FOC** — Clarke/Park, d/q PI regulators, SVPWM | [`bldc_driver_esp32`](https://github.com/marek-czelen/bldc_driver_esp32) |
| **Hall sensors, encoders**, current sensing | All BLDC repos — synchronized injected ADC |
| **MOSFET gate drivers** (EG2113, IR2103, IR2113) | Hardware documentation in all BLDC repos |
| **Hardware BREAK**, overcurrent protection, dead-time | `bldc_driver_v2_stm` — safety layer |
| **PCB design** (KiCAD), oscilloscope diagnostics | Hardware debugging documented across repos |

### Communication & Protocols
| Skill | Evidence |
|---|---|
| **CAN / CAN FD**, **LIN**, **SPI**, **UART**, **I2C** | Professional & project experience |
| **TCP/IP**, **UDP**, **Ethernet/IP**, **REST**, **SOAP** | [`mailing`](https://github.com/marek-czelen/mailing), professional platforms |
| **Proprietary binary protocols** | APTIV — occupancy detection system |
| **Wi-Fi**, embedded HTTP servers | [`bldc_driver_esp32`](https://github.com/marek-czelen/bldc_driver_esp32) — dashboard + REST API |

### Application Development
| Skill | Evidence |
|---|---|
| **Node.js / Express**, **Vue 3**, **JavaScript** | [`mailing`](https://github.com/marek-czelen/mailing) — full-stack email campaign platform |
| **C# / .NET** (WPF, Xamarin, .NET Core) | [`CertificateFactory`](https://github.com/marek-czelen/CertificateFactory), [`edccWallet`](https://github.com/marek-czelen/edccWallet) |
| **Java / Android** (native) | [`FamilySonar`](https://github.com/marek-czelen/FamilySonar) — foreground services, SMS, GPS |
| **SQL** (MySQL, MariaDB, PostgreSQL, MS SQL) | `mailing`, professional platforms |
| **PHP** | Professional experience |

### Systems Architecture & Platforms
| Skill | Evidence |
|---|---|
| **Distributed enterprise platforms** | APTIV — global asset management (1,000+ users) |
| **Deployment automation** | APTIV — zero-downtime updates + rollback |
| **Database architecture & synchronization** | Professional platforms across 4 global regions |
| **CI / automation** | Professional experience |

### AI & Applied Intelligence
| Skill | Evidence |
|---|---|
| **Neural networks, medical imaging, pattern recognition** | [Springer publication](https://link.springer.com/chapter/10.1007/978-3-319-26250-1_30) |
| **AI-assisted content generation** | [`mailing`](https://github.com/marek-czelen/mailing) — Hugging Face integration |
| **LLM-assisted technical analysis & code generation** | Active daily workflow |

---

## 📁 Featured Public Projects

### 🔧 Motor Control & Embedded Systems

**[bldc_driver_v3_m365](https://github.com/marek-czelen/bldc_driver_v3_m365)** — `C` · `STM32F103` · `PlatformIO`
Sensor-based BLDC controller with BLOCK and SINUS modes, TIM1 complementary PWM, atomic COM-event commutation, synchronized injected ADC current measurement, automatic Hall learning, duty ramps, persistent Flash configuration, and a diagnostic UART CLI.

**[bldc_driver_v2_stm](https://github.com/marek-czelen/bldc_driver_v2_stm)** — `C` · `STM32F411` · `CMSIS` · `No HAL`
CMSIS-based BLDC firmware with six-step and sinusoidal DPWM, Hall interpolation, hardware BREAK shutdown, current/temperature supervision, safe output states (OSSR/OSSI), and modular low-level architecture. Includes hardware documentation and a safety layer.

**[bldc_driver_esp32](https://github.com/marek-czelen/bldc_driver_esp32)** — `C++` · `ESP32` · `MCPWM` · `Arduino`
Multi-mode e-bike controller with six-step, 12-step, sinusoidal, and FOC modes. Features IRAM-safe 20 kHz MCPWM ISR, Hall tracking, regenerative braking, PAS, S866 display protocol, Wi-Fi dashboard with REST API, and NVS configuration.

### 📱 Applications & Integration

**[mailing](https://github.com/marek-czelen/mailing)** — `Vue 3` · `Node.js` · `Express` · `MySQL`
Full-stack email campaign platform with multi-tenant contact databases, SMTP delivery, IMAP reply/bounce monitoring, JWT/RBAC authentication, AI content generation (Hugging Face), heuristic spam analysis, and bilingual UI (PL/EN).

**[FamilySonar](https://github.com/marek-czelen/FamilySonar)** — `Java` · `Android` · `SDK 36`
Native Android location-sharing app using foreground services, SMS-triggered workflows, GPS/network location, geocoding, runtime permissions, and battery-aware background operation — all without a backend server.

**[edccWallet](https://github.com/marek-czelen/edccWallet)** — `C#` · `Xamarin.Forms` · `Android`
Digital COVID Certificate wallet for Android with QR scanning, Base45/COSE/CBOR decoding, local certificate storage, and a reusable DCC processing library.

**[CertificateFactory](https://github.com/marek-czelen/CertificateFactory)** — `C#` · `WPF` · `Xamarin.Android`
Cross-platform certificate generation and QR validation system combining a WPF desktop creator (SQLite) with an Android QR scanner, sharing a common .NET Standard encryption domain.

**[node-red-contrib-crypto-js-fields](https://github.com/marek-czelen/node-red-contrib-crypto-js-fields)** — `JavaScript` · `Node-RED`
Custom Node-RED nodes for field-level encryption/decryption with CryptoJS, editor-side configuration, and dot-separated message path traversal.

---

## 💼 Professional Experience

### APTIV — Automotive Engineering & Validation Systems (Europe, USA, Mexico, China)

**Senior Software Engineer** (current) · **Expert Software Engineer** · **Software Engineer**

- **Architected a global laboratory equipment management platform** used by 1,000+ users across 4 continents, managing ~100,000 equipment assets and ~1,000,000 related process instances
- **Contributed firmware** for tools deployed in 2,000+ measurement cards for automotive test systems
- **Designed distributed deployment infrastructure** with automated discovery, scheduling, non-disruptive updates, verification, and rollback — deployed in Europe and USA
- **Engineered a proprietary communication protocol** and occupancy-detection system handling ~3,000 requests/second
- **Global technical ownership** of the engineering work-request platform for APTIV validation operations

### Wydawnictwo ZNAK — Lead Software / Systems Engineer

- **Delivered an ERP-integrated mobile sales and logistics platform** adopted by the entire field-sales organization
- Integrated mobile workflows, logistics processes, and central business data

---

## 📚 Research & Education

### Springer Publication
**Sequential Analysis of Medical Images Using Neural Networks**  
Applied AI research combining medical imaging, pattern recognition, and **three cooperating neural networks** to support inexperienced physicians during medical-image interpretation. **Reported accuracy: ~80%.**

### AGH University of Krakow
**Master of Science in Automation and Robotics**

---

## 🎯 Open To

Senior, Staff, Principal, and Lead roles involving:

- Embedded systems & firmware architecture
- Motor control (BLDC, FOC, power electronics)
- Hardware/software integration & co-design
- Automotive engineering platforms & validation systems
- Industrial communication & IoT
- Embedded AI / edge intelligence
- Distributed engineering infrastructure

**Remote / Hybrid / Kraków or relocation** — open to discussion.

---

## 💬 Why Interview Me?

> *"The best conversations usually start with a real system constraint: a timing budget, a noisy measurement, a difficult power stage, an unreliable deployment path, or a product that needs to remain understandable after it leaves the lab."*

I bring:
- **End-to-end ownership** — from soldering and oscilloscope probes to globally distributed architecture
- **Hardware-aware engineering judgment** — firmware decisions informed by electrical behavior, not just algorithms
- **Systems thinking** — interfaces, state machines, failure modes, diagnostics, and operability as first-class concerns
- **20+ years of delivery** — across embedded, enterprise, mobile, web, and AI domains
- **Honest documentation** — I write down assumptions, measurements, limitations, and next steps

📩 **Let's talk:** [LinkedIn](https://linkedin.com/in/marek-czelen) · [GitHub](https://github.com/marek-czelen) · Located in **Kraków, Poland** · English: B2+

---

<sub>⭐ This profile is regularly updated. Last refresh: July 2026.</sub>
