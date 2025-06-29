# 📡 Awesome LoRa APRS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources, hardware, projects, and tools for **LoRa APRS** — the fusion of [LoRa](w) low-power wide-area radio and [APRS](w), the Automatic Packet Reporting System.

---

## 📁 Contents

* [Projects](#projects)
* [Firmware](#firmware)
* [Hardware](#hardware)
* [Gateways](#gateways)
* [Trackers](#trackers)
* [Software & Tools](#software--tools)
* [Protocols & Specs](#protocols--specs)
* [Communities](#communities)
* [Tutorials & Articles](#tutorials--articles)
* [Contributing](#contributing)

---

## 🚀 Projects

* [LoRa APRS iGate by OE1ACM](https://github.com/lora-aprs/LoRa_APRS_iGate) – A feature-rich iGate firmware with OLED and GPS support.
* [trackerjacker](https://github.com/merbanan/trackerjacker) – A powerful LoRa APRS tracker with custom configuration support.
* [LoRa-APRS-Gateway by OE5BPA](https://github.com/OE5BPA/LoRa-APRS-Gateway) – ESP32 iGate with display, web interface, and full-featured support.
* [dj0abr/LoRa-Modem](https://github.com/dj0abr/LoRa-modem) – Versatile modem supporting APRS digipeater, tracker, and RX iGate.
* [RNode by markqvist](https://github.com/markqvist/RNode_Firmware) – LoRa modem supporting APRS and Meshtastic compatibility.
* [LoRa\_APRS\_Tracker by OE1ACM](https://github.com/lora-aprs/LoRa_APRS_Tracker) – ESP32 tracker firmware with display and GPS.
* [TTGO-T-Beam-LoRa-APRS](https://github.com/OE5BPA/TTGO-T-Beam-LoRa-APRS) – Tracker firmware for TTGO T-Beam with multiple features.
* [OpenModem LoRa](https://github.com/armel/LoRa-APRS-OpenModem) – Lightweight open-source tracker firmware.
* [qdp/LoRa\_APRS\_iGate\_TTN](https://github.com/qdp/LoRa_APRS_iGate_TTN) – Gateway between The Things Network and APRS-IS.
* [OZ1EKD/openmodem](https://github.com/OZ1EKD/openmodem) – APRS modem firmware for Teensy, ESP32 and more.
* [LightAPRS](https://www.qrp-labs.com/lightaprs/lightaprsplus.html) – Commercial tracker with LoRa + GPS support.

---

## 🔧 Hardware

### TTGO Boards by LilyGO

* **TTGO T-Beam v1.2**
* **TTGO T-Beam v1.2 SX1262**
* **TTGO T-Beam SUPREME V3**
* **TTGO T-Beam v1.0 / v1.1**
* **TTGO T-Beam v1 SX1268**
* **TTGO T-DECK Plus**
* **TTGO T-DECK (LoRa + GPS)**
* **TTGO T-ECHO**
* **TTGO LoRa32 v2.1 (with GPS or TNC use)**
  Available from [LilyGO](https://www.lilygo.cc) and EU store: [LilyGO EU](https://lilygo.eu)

### RAK Wireless Modules

* **RAK4631** – Nordic nRF52840-based Arduino-compatible LoRa module (433MHz)
* **WisBlock RAK19007** – WisBlock base board
* **WisBlock RAK19003** – Alternate WisBlock base board
* **RAK12500** – u-blox ZOE-M8Q GPS module
  🔗 [RAK Wireless Store](https://store.rakwireless.com/) – Use discount code: `NGEQHU`

🧹 *Suggested stack:*
`RAK19007 or RAK19003` + `RAK4631` + `RAK12500`

### HELTEC Boards

* **HELTEC Wireless Tracker**
* **WiFi LoRa32 V3.2** – ESP32 with LoRa + GPS
* **WiFi LoRa32 V3** – Earlier revision with similar features

### GPS Modules

* **NEO6Mv2 GPS** – Inexpensive serial GPS module used in many DIY APRS setups

### Transceivers & Modules

* **LoRa SX1278** – Standard LoRa transceiver module (433/868MHz)
* **EBYTE E22-400M30S** – High-performance SX1268-based 433MHz module

### Other Boards

* **QRP Labs LightTracker Plus 1.0** – [QRP Labs LightTracker Plus](https://www.qrp-labs.com/lightaprs/lightaprsplus.html)
* **ESP32 Boards** – Generic boards for building LoRa APRS trackers
* **OE5HWN\_MeshCom** – Custom APRS + MeshCom hardware design

---

## 🌍 Gateways

* [LoRa APRS iGate](https://github.com/lora-aprs/LoRa_APRS_iGate) – Suitable for Raspberry Pi and ESP32-based devices
* [LoRa-APRS-Gateway by OE5BPA](https://github.com/OE5BPA/LoRa-APRS-Gateway)
* [dj0abr/LoRa-Modem](https://github.com/dj0abr/LoRa-modem)
* [qdp/LoRa\_APRS\_iGate\_TTN](https://github.com/qdp/LoRa_APRS_iGate_TTN)

---

## 🚁 Trackers

* [trackerjacker](https://github.com/merbanan/trackerjacker)
* [LightAPRS](https://www.qrp-labs.com/lightaprs/lightaprsplus.html)
* [OE1ACM LoRa Tracker](https://github.com/lora-aprs/LoRa_APRS_Tracker)
* [TTGO T-Beam Tracker](https://github.com/OE5BPA/TTGO-T-Beam-LoRa-APRS)
* [OpenModem LoRa](https://github.com/armel/LoRa-APRS-OpenModem)

---

## 🛠 Software & Tools

* [APRS.fi](https://aprs.fi) – Realtime APRS map viewer
* [Direwolf](https://github.com/wb2osz/direwolf) – APRS software TNC and digipeater
* [YAAC](http://www.ka2ddo.org/ka2ddo/YAAC.html) – APRS client and visualizer

---

## 📜 Protocols & Specs

* [APRS Protocol Reference](https://www.tapr.org/pub_ax25.html)
* [LoRa Modulation Basics](https://lora-developers.semtech.com/)

---

## 🛈 Communities

* [LoRa-APRS Telegram Group](https://t.me/LoRa_APRS)
* [r/amateurradio on Reddit](https://www.reddit.com/r/amateurradio/)

---

## 📚 Tutorials & Articles

* [Setting up LoRa APRS iGate](https://github.com/lora-aprs/LoRa_APRS_iGate/wiki)
* [Understanding LoRa Parameters](https://www.thethingsnetwork.org/docs/lorawan/)

---

## 🤝 Contributing

Your contributions are welcome! Please read the [contributing guide](CONTRIBUTING.md) before submitting a pull request. Help us grow this awesome list!

---

## ⚠️ Disclaimer

This list is provided for informational purposes only. Use at your own risk. No warranty is expressed or implied.
