<!-- OVERVIEW_START -->
> **IoTbase RPi**
>
> Carrier board for Raspberry Pi (40-pin, HAT-compatible) · IoTextra mezzanine · mikroBUS™
>
> Power: 9–36 VDC or USB · RS485 · Qwiic · GPIO and I²C · Open Hardware
>
> Part of the IoTbase series · compatible with IoTextra mezzanine modules · Make Things Happy!
<!-- OVERVIEW_END -->

## Examples

Python code examples for each on-board subsystem (EEPROM, Watchdog, GPIO, HOST-P12 I/O, RS-485) are available in the hardware validation test suite:

👉 [IoTbase-RPi-Test](https://github.com/makethingshappy/IoTbase-RPi-Test)

| Subsystem | Script |
|---|---|
| EEPROM (8 Kbit / 64 Kbit) | `iotbase_eeprom_report.py` |
| Hardware Watchdog | `iotbase_watchdog_report.py` |
| GPIO (single pair) | `iotbase_gpio_report.py` |
| GPIO (all pairs, bidirectional) | `iotbase_gpio_pair_report.py` |
| HOST-P12 Digital I/O | `hostp12_io.py` |
| RS-485 Communication | `iotbase_rs485_echo_test.py` |

## SKU

See [SKU.md](SKU.md)

## Version history

| Version | Notes |
|---|---|
| 3.04 | Initial GitHub release |
