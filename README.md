# ESP32 WiFi Jammer

This project is designed for the ESP32 microcontroller and creates a basic WiFi jammer by generating noise on a specified WiFi channel. It’s intended to be copied into the Arduino IDE and used strictly for educational purposes only.

---

## Project Overview

The code allows users to:

- **Scan for Available Networks**: Identify WiFi networks, channels, and signal strengths.
- **Select a Target Network**: Choose a network to interfere with based on its SSID and channel.
- **Generate Noise Packets**: Send packets on the target channel, potentially disrupting connectivity.

> **Disclaimer**: This project is strictly for educational purposes only. Unauthorized use in real environments may violate laws and disrupt networks.

---

## Getting Started

### Requirements

- **ESP32**: The code is specifically for the ESP32 microcontroller.
- **Arduino IDE**: Copy the code into the Arduino IDE for uploading to the ESP32.

### Setup

1. **Clone this repository**:
   ```bash
   git clone <repo-url>
   ```
2. **Upload Code to ESP32**:
   - Copy the code from `Wifi Jammer.txt` into the Arduino IDE.
   - Select the correct board and port for the ESP32.
   - Upload the code.

3. **Select Target Network**:
   - Once running, the program will scan for nearby networks.
   - Enter the number corresponding to the target network you wish to interfere with.

---

## Limitations

Since the ESP32 is a low-power device, it can overheat and may stop functioning if run continuously for extended periods. This code can be easily modified to run on more powerful hardware, like a desktop or Raspberry Pi, in a different language to improve performance and stability.

> **Note**: Using a more capable device can yield better results and reduce the risk of overheating.
