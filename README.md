# Tallinn Real-Time Transport Map

A lightweight, real-time public transport map for Tallinn — showing live positions of buses, trams, and trolleybuses using Mapbox GL JS.  
The project automatically adapts to your system dark mode and updates vehicle locations every few seconds.

> 🚌 **Inspired and mostly ported from [teele.org](https://teele.org)** — a brilliant visualization of public transport in Tallinn.

---

## 🚀 Features

- **Real-time data** — Fetches live vehicle locations every 5 seconds  
- **Dynamic color themes** — Automatically switches between light and dark mode  
- **Mapbox integration** — Smooth vector rendering and rotation-aware symbols  
- **Minimal setup** — No backend required, pure client-side JavaScript  
- **Compact codebase** — Easy to customize or extend

---

## 🧩 Tech Stack

- **Mapbox GL JS**
- **Vanilla JavaScript (ES6)**
- **GeoJSON live data feed** from `https://gis.ee/tallinn/gps.php`

---

## 💻 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/tallinn-transport-map.git
cd tallinn-transport-map
