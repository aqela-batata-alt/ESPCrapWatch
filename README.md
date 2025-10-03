# ESPCrapWatch
ESP-Based Smart Crap Watch

[![ESP-IDF](https://img.shields.io/badge/ESP--IDF-v5.0+-purple.svg)](https://docs.espressif.com/projects/esp-idf/en/stable/)
[![Documentation](https://img.shields.io/badge/docs-esp--rs-brightgreen)](https://esp-rs.github.io/esp-idf-sys/esp_idf_sys/index.html)


**The world's most unreliable smartwatch** - because i want

## Overview

The ESP-based Smart Crap Watch is a feature-packed (with mostly useless features) wearable device built on the ESP32 platform using ESP-IDF. It promises to deliver all the functionality you probably don't need in a smartwatch.

This repository contains everything you need to build your own questionable wearable technology, from the firmware to the hardware design.

## Features

- **Clock**: Displays time.
- **Binary Clock**: Displays time in binary, 'cause why not?.
- **Great Battery Life**: Very optimized battery usage.
- **Notification Support**: Get notified about notifications about notifications
- **Interactive and customizable UI**: support for custom UI.
- **Easy controlls**: Two and one buttons needed for navigation.
- **Bad Apple**: Native Bad Apple player with decoder.
- **Other**: To be added :3.

## Hardware Requirements

### Components
- ESP32 t-display ( like the one for ttgo or lilygo), TS-ESP32-S3 or you can get a default one and add your own screen if you want to.
- LiPo battery ( at least more than 500mAh for longer battery health).
- Vibrating motor ( optional).

## Getting Started

### Prerequisites
- Cargo
- Esp libraries for rust
- Low expectations

### Installation
0. Prerequisites:
```bash
#rustup install
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
restart your shell
```bash
#espup install
cargo install espup cargo-espflash --lockup
espup install
```
  
2. Clone this repository (you sure about this?):
```bash
git clone https://github.com/aqela-batata-alt/ESPCrapWatch.git
cd ESPCrapWatch
```

2. Set up the ESP environment:
```bash
source $HOME/export-esp.sh
```


3. Build the project:
```bash
cargo build
```

4. Flash and monitor your device:
```bash
cargo espflash --monitor
```


## Project Structure
To do :3

## Usage

1. Charge the watch.
2. Connect to WiFi.
3. Be happy.

## Configuration

Modify `sdkconfig` or use `menuconfig` to adjust settings:

To think about :3

## Contributing

We are not accepting external contributions at the moment, for this is just a small project.

## Contribuitors

| <img src="https://github.com/aqela-batata-alt.png" width="80" height="80"> | <img src="https://github.com/DiceRunner714.png" width="80" height="80"> |
|:-------:|:---------:|
| Víctor Moreira | Eduardo Sandes |

## License

To do :3

## Warning

- Make sure the battery is not contacting your skin directly to avoid slow skin burn.
- Make sure the battery is not contacting the processor of the board to avoid heat damage and explosions.
- Avoid **at all costs** the contact of the watch with water.

We are not responsible for any damage you or your hardware may have. **Build at your own risk!**

---

*If you actually find this useful, please check your expectations - they're probably too high.*
