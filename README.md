# Marek Czelen

## Embedded Systems Engineer | Firmware, Motor Control and System Architecture

I build systems that connect real hardware with reliable software.

My work spans low-level firmware, real-time control, electronics, communication protocols, diagnostics, distributed engineering platforms, web systems, mobile applications and applied AI. I am most effective at the boundary between the physical system and the software that has to control, measure and explain it.

With 20+ years of engineering experience, I design from the MCU, timer and interrupt level up to system architecture, deployment and operational workflows. My public repositories show hands-on development in C/C++, STM32, ESP32, motor control, Android, Node.js, Vue and Node-RED.

## What I work on

- **Embedded firmware:** bare metal, CMSIS, STM32, ESP32, RTOS concepts, timers, interrupts, DMA, ADC, UART, GPIO and persistent configuration
- **Motor control:** BLDC, Hall-sensor commutation, six-step, sinusoidal PWM, DPWM, FOC foundations, PWM timing, dead-time and power-stage diagnostics
- **Hardware-aware software:** current sensing, MOSFET gate drivers, fault shutdown, overcurrent and thermal protection, oscilloscope-led debugging and hardware/software co-design
- **Systems and platforms:** distributed services, REST APIs, databases, synchronization, deployment automation, monitoring and rollback
- **Application development:** C, C++, C#, Java, JavaScript, Node.js, Vue, SQL and native Android
- **Applied AI and automation:** neural networks, medical-image analysis, AI-assisted application features and reusable integration components

## Selected public projects

### Motor control and embedded systems

- [bldc_driver_v3_m365](https://github.com/marek-czelen/bldc_driver_v3_m365) - Sensor-based BLDC controller for STM32F103C8T6. Implements BLOCK and SINUS modes, Hall learning, TIM1 complementary PWM, atomic commutation through COM events, synchronized injected ADC current measurement, duty ramps, persistent configuration and a diagnostic USART CLI.

- [bldc_driver_v2_stm](https://github.com/marek-czelen/bldc_driver_v2_stm) - CMSIS-based BLDC firmware for STM32F411CEU6 without the STM32 HAL. Covers TIM1 PWM, Hall interpolation, sinusoidal DPWM, hardware BREAK shutdown, current and temperature supervision, safe output states, fault handling and modular low-level firmware architecture.

- [bldc_driver_esp32](https://github.com/marek-czelen/bldc_driver_esp32) - ESP32 motor controller built around MCPWM and an IR2103 three-phase bridge. Includes six-step, 12-step, sinusoidal and FOC-oriented control modes, Hall tracking, synchronized ISR-driven switching, current and voltage measurement, regenerative braking, PAS support, Wi-Fi configuration, REST endpoints and NVS configuration.

These projects are active engineering and hardware-validation work. Their documentation intentionally includes design decisions, limitations and next steps instead of presenting prototypes as finished production products.

### Applications and integration

- [mailing](https://github.com/marek-czelen/mailing) - Full-stack email campaign platform with a Node.js and Express REST backend, Vue 3 frontend, MySQL/MariaDB persistence, multi-tenant contact databases, SMTP delivery, IMAP reply and bounce monitoring, JWT/RBAC authentication, bilingual UI, AI-assisted content generation and heuristic spam analysis.

- [FamilySonar](https://github.com/marek-czelen/FamilySonar) - Native Android application written in Java for location sharing between trusted contacts. Uses foreground services, SMS-triggered workflows, GPS/network location, geocoding, permission handling, local storage and battery-aware background operation without requiring a backend.

- [node-red-contrib-crypto-js-fields](https://github.com/marek-czelen/node-red-contrib-crypto-js-fields) - Reusable Node-RED nodes for field-level encryption and decryption with configurable message paths, CryptoJS algorithms, editor-side configuration and example flows. The repository also documents the difference between integration convenience and production-grade key management.

## Professional engineering background

In my professional work at APTIV, I have designed and supported automotive engineering and validation systems used across geographically distributed operations, including Europe, the United States, Mexico and China.

Selected outcomes include:

- Architecting a laboratory asset-management platform used by more than **1,000 users**, managing approximately **100,000 equipment assets** and **1,000,000 related process instances**
- Contributing firmware for tools used in more than **2,000 measurement cards** for automotive test systems
- Designing distributed deployment infrastructure with automatic discovery, scheduling, non-disruptive updates, verification and rollback
- Designing communication and occupancy-detection mechanisms for distributed engineering stations
- Taking global technical responsibility for an engineering work-request platform used by validation operations

Earlier, at Wydawnictwo ZNAK, I delivered an ERP-integrated mobile sales and logistics platform used by the complete field-sales organization.

## Engineering perspective

I care about the parts of a system that are easy to overlook but decisive in practice:

- explicit ownership of state and failure handling
- deterministic timing in safety- and control-critical paths
- safe startup, shutdown and recovery behavior
- observability through diagnostics, status interfaces and traceable configuration
- deployment and maintenance as part of the architecture
- honest documentation of assumptions, measurements, limitations and open risks

## Research

My research on **Sequential Analysis of Medical Images Using Neural Networks** was published by Springer. The work combined medical imaging, pattern recognition and three cooperating neural networks, with reported recognition accuracy of approximately 80%.

## Current focus

I am interested in Senior, Staff, Principal and Lead roles involving embedded systems, firmware architecture, motor control, hardware/software integration, automotive engineering platforms, industrial communication and embedded AI.

The best conversations usually start with a real system constraint: a timing budget, a noisy measurement, a difficult power stage, an unreliable deployment path or a product that needs to remain understandable after it leaves the lab.

## Contact

- GitHub: [github.com/marek-czelen](https://github.com/marek-czelen)
- Location: Krakow, Poland
- English: B2
