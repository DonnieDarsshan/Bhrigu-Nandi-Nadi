# Bhrigu-Nandi-Nadi
Bhrigu Nandi Nadi Predictor 


# 🌌 BNN Predictor Engine

A powerful **browser-based astrology engine** that generates and visualizes Vedic charts, Vimshottari Dasha timelines, and divisional charts with an advanced UI.

---

## 🚀 Features

* 📊 Dynamic Kundali Charts (D1–D60)
* 🔁 Shifted Lagna Simulation
* 🧠 KP / Sign2Sign / KN Modes
* 🌙 Vimshottari Dasha Engine (Chandra & Lagna based)
* ☁️ Cloud Horoscope Fetcher (API-based)
* 💾 Save / Load Profiles (JSON)
* 🗺️ Built-in Location Search + Timezone Detection
* 📅 Date Difference Utility Tool
* 🎛️ Pivot-based Chart Rotation System

---

## 📁 File Structure

```
BNN Predictor/
│
├── BNN.html
└── README.md
```

---

## 🧑‍💻 How to Use

1. Download or clone the repository
2. Open the file in your browser:

```
BNN.html
```

No installation required.

---

## ☁️ Cloud Fetch (API)

This project uses:

```
https://donnie-astro-engine.onrender.com/calculate
```

### Required Inputs:

* Date (DD-MM-YYYY)
* Time (HH:MM:SS)
* Latitude & Longitude
* Timezone

---

## 💾 Profile System

### Save Profile

Stores:

* Date & Time
* Location
* Timezone
* Full chart data

### Load Profile

Supports:

* Saved profiles (`CloudHoroscopeProfile`)
* Raw API JSON

---

## ⚙️ Modes

| Mode          | Description                  |
| ------------- | ---------------------------- |
| KP            | Krishnamurti Paddhati system |
| Sign2Sign     | Direct sign-based mapping    |
| KN            | Kannada naming system        |
| Shifted Lagna | Time progression simulation  |

---

## 🧮 Supported Charts

D1, D2, D3, D4, D5, D6, D7, D8, D9, D10, D11, D12
D16, D20, D21, D24, D27, D30, D40, D45, D60

---

## 🧩 Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript

---

## 📌 Notes

* Runs fully in browser
* Internet needed only for cloud fetch
* Best on desktop

---

## ⚠️ Disclaimer

For educational purposes only. Astrology results may vary.

---

## ✨ Author

BNN Predictor Engine
