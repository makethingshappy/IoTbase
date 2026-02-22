# IoTbase — Professional Base Boards for IoT & Automation

The **IoTbase** series by **makethingshappy** provides a robust hardware foundation for industrial and home automation projects. These base boards bridge the gap between popular microcontroller ecosystems and professional-grade peripherals, featuring high-voltage power stages, industrial communication interfaces, and support for the **IoTextra** mezzanine system.

## Supported Modules

The series currently includes three versatile professional-grade carrier boards:

- **IoTbase PICO**: Optimized for the Raspberry Pi Pico / Pico 2 and compatible modules (e.g., Waveshare ESP32-S3-PICO).
- **IoTbase Nano**: Designed for the Arduino Nano form factor, supporting classic Nano, Nano Every, Waveshare ESP32-S3-Nano, and STM32 NUCLEO-L412KB.
- **IoTbase Feather** (Coming Soon): Compatible with the Adafruit Feather ecosystem, bringing industrial connectivity to a wide range of Feather-format MCUs. 

---

## Key Features

### Power & Reliability

- **Wide Input Voltage**: Supports non-isolated 9VDC to 36VDC via a 2-pin 3.5mm terminal block.
- **Flexible Power Options**: Optional high-efficiency DC-DC converters (5W, 10W, or 15W) providing up to 3A at 5V.
- **Alternative Powering**: Can be powered via USB or a JST 5VDC input for debugging and low-power setups.

### Expansion & Interconnectivity

- **IoTextra** Mezzanine Slots: Integrated HOST-P12 and HOST-S12 connectors for 47x56mm IoTextra modules.
- **mikroBUS™** Support: M1 Connector and Two slots for Click-boards (M2 and M3, are accessible when no mezzanine is installed).
- Dual **Qwiic** Connectors: Two I2C ports for rapid sensor integration with switchable pull-up resistors.

### Communication & Data

- Industrial **RS-485**: Optional half-duplex RS-485 interface for long-distance communication.
- **1-Wire** Interface: Dedicated connector for DS18B20 and other 1-Wire sensors.
- Onboard Memory: Integrated EEPROM (8 Kbit or 64 Kbit) for configuration storage.

### The IoTextra Ecosystem

IoTbase boards serve as the carrier for the **IoTextra** mezzanine series (47x56 mm), allowing you to customize your device's I/O:

- **IoTextra Input**: 8-channel isolated digital inputs (up to 36V).
- **IoTextra Relay2**: 4-channel SPDT relay module.
- **IoTextra SSR Small**: 8-channel solid-state relay module.
- **IoTextra Octal2**: 4 isolated inputs + 4 high-power NPN outputs.
- **IoTextra Analog**: 4-channel 16-bit ADC (ADS1115) for 4-20mA/voltage signals.
- **IoTextra Combo**: 2 relays + 2 precision analog inputs.
Coming Soon — IoTextra Octal: A hybrid module featuring 4 isolated digital inputs and 4 relays.

---

## Getting Started

- Choose your carrier board based on your preferred SoM (PICO, Nano, or Feather).
- Install your SoM and optional **IoTextra** mezzanine.
- Connect power (9-36VDC) and start developing.

---

## Hardware Specifications

Full hardware specifications — including pinouts, voltage ratings, PCB layouts, and electrical characteristics — are located inside the module folders:

- **[IoTbase PICO](./PICO/)**  
- **[IoTbase NANO](./NANO/)**  
- **IoTbase Feather** (Coming Soon)

Each module directory includes its own documentation.  
Versioned subfolders (e.g., `v1.xx`) will be added by the development team in future updates.

---

## Ordering Information

### 📦 SKU Information  
The full SKU list is available in the repository root:

---

### 🛒 Purchase Links  
Order IoTsmart modules directly from the official store:

- **IoTbase PICO:**  
  https://makethingshappy.io/collections/iotbase/products/iotbase-pico

- **IoTbase NANO**  
  https://makethingshappy.io/collections/iotbase/products/iotbase-nano

---

## Licensing

This repository uses separate licenses per asset type:

- **Code:** [`LICENSE_CODE.md`](./LICENSE_CODE.md) — MIT License  
- **Schematics & Documentation:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) — CC BY-SA 4.0  
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)  
- **Media:** [`LICENSE_MEDIA.md`](./LICENSE_MEDIA.md)
