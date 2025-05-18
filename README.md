# WiFiFish — Rogue Access Point Automation Suite

WiFiFish is a beginner-friendly tool for setting up a rogue access point with phishing capabilities. With a clean interface and powerful features, WiFiFish automates every step — from setting up hostapd and dnsmasq, to cloning networks, deauthing clients, and capturing credentials through custom portals.

## Features

- [x] Create rogue AP with `hostapd` and `dnsmasq`
- [x] Launch captive portals with Flask
- [x] Select from multiple phishing templates (e.g., Facebook, Netflix)
- [x] Clone existing ESSIDs via network scanner
- [x] Deauth original AP to kick connected users
- [x] Log all captured credentials

## Installation

```bash
git clone https://github.com/Matrix831/wififish.git
cd wififish
chmod +x install.sh
./install.sh

