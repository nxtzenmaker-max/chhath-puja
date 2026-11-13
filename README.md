# 🌸 छठी मईया • Chhath Puja Mahaparv

> **The Eternal Song of Sun & Stream** — An aesthetic, culturally authentic, and interactive web celebration of the sacred 4-day Chhath Puja festival.

[![Live Website](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-f59e0b?style=for-the-badge&logo=github)](https://nxtzenmaker-max.github.io/chhath-puja/)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-10b981?style=for-the-badge&logo=pwa)](manifest.json)
[![Offline First](https://img.shields.io/badge/Offline-Cached-6366f1?style=for-the-badge)](sw.js)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

---

## 🌅 Live Website
Explore the live deployed platform at:  
👉 **[https://nxtzenmaker-max.github.io/chhath-puja/](https://nxtzenmaker-max.github.io/chhath-puja/)**

---

## ✨ Features & Highlights

1. **4-Day Sacred Rituals Journey**
   - Detailed walkthrough of each ritual day:
     - **Day 1: Nahay-Khay** (Sanctification & Kaddu-Bhat prasad)
     - **Day 2: Kharna** (Nirjala fast & Rasiya-Kheer preparation)
     - **Day 3: Sandhya Arghya** (Evening solar salutations & bamboo supa offerings)
     - **Day 4: Usha Arghya & Paran** (Dawn arghya to rising Surya Dev & breaking the fast)

2. **Astronomical Arghya Muhurat & Solar Scheduler**
   - Live countdown to the next solar Arghya offering.
   - City selector for precise sunset (Sandhya) and sunrise (Usha) muhurat timings across major Indian and diaspora cities (Patna, Varanasi, Delhi, Mumbai, Kolkata, New York, San Jose, London).

3. **Virtual Floating Diyas on the Ganges (Canvas Experience)**
   - Interactive HTML5 canvas rendering floating earthen lamps on the flowing Ganges river.
   - Devotees can light their own diya with personalized name, prayer, and location.
   - Interactive diya inspection modal with real-time prayer offerings.

4. **Web Audio Soundscapes & Traditional Geet**
   - Procedural Web Audio API sound generator providing immersive natural ghat ambience: gentle river currents, temple bells, and bansuri flute drones.
   - Dedicated Sharda Sinha traditional folk music showcase with lyrics and spiritual meaning.

5. **Authentic Khasta Thekua & Prasad Kitchen**
   - Scalable batch calculator for authentic wheat-flour and jaggery Khasta Thekua.
   - Step-by-step traditional method with secret tips for achieving the signature crispy crust and fragrant cardamom-ghee aroma.

6. **Interactive Vrati Checklist & Bamboo Supa Explorer**
   - Visual catalog of essential puja items (Daura, Supa, Suthan, Ginger plants, Diyas, Kasar).
   - Offline-persistent checklist with local storage backup and cloud restore capabilities.

7. **Global Community Ghat Directory**
   - Directory connecting devotees to local ghats and community celebrations worldwide.
   - User submission modal to register local ghats, lakes, or diaspora gatherings.

8. **PWA & Offline Capability**
   - Standalone progressive web app installable on iOS and Android devices.
   - Service Worker caching to ensure seamless operation at crowded river ghats with intermittent network connectivity.

---

## 🛠️ Technology Stack

- **Markup & Semantics**: HTML5 (Accessible ARIA roles, modern schema markup)
- **Styling**: Vanilla Modern CSS3 (CSS Custom Properties, Flexbox, CSS Grid, Glassmorphism, Responsive Media Queries)
- **Interactive Scripts**: Vanilla ES6+ JavaScript (Web Audio API, HTML5 Canvas physics, LocalStorage Sync)
- **PWA**: Service Worker (`sw.js`) + Web App Manifest (`manifest.json`)
- **Typography**: Google Fonts (*Cinzel*, *Plus Jakarta Sans*, *Rozha One*, *Yatra One*)

---

## 📂 Repository Structure

```
├── .gitignore               # Ignored workspace and temporary files
├── .nojekyll                # GitHub Pages Jekyll bypass
├── index.html               # Main festival website
├── manifest.json            # PWA manifest
├── sw.js                    # Service Worker with offline caching
├── README.md                # Project documentation
└── assets/
    ├── css/
    │   ├── styles.css       # Core typography, themes, layout & hero styles
    │   └── interactive.css  # Canvas, audio, modals, checklist & interactive styles
    ├── js/
    │   ├── main.js          # App initialization, mobile dock, navigation
    │   ├── audio-synthesizer.js # Web Audio API ambient ghat soundscape
    │   ├── virtual-ghat.js  # Floating diya river canvas physics
    │   ├── scheduler.js     # Solar arghya countdown & muhurat calculator
    │   ├── recipes.js       # Thekua recipe portion scaling & cooking steps
    │   ├── community.js     # Global ghat directory & submission handler
    │   └── cloud-sync.js    # Data export/import & cloud synchronization
    └── images/
        ├── chhath_hero.jpg
        ├── chhath_nahay_khay.jpg
        ├── chhath_thekua_supa.jpg
        └── chhath_usha_arghya.jpg
```

---

## 🚀 Local Development

No build step or external dependencies required! Simply clone and serve:

```bash
# Clone the repository
git clone https://github.com/nxtzenmaker-max/chhath-puja.git
cd chhath-puja

# Open index.html directly or serve using Python
python3 -m http.server 8000
```
Then navigate to `http://localhost:8000` in your web browser.

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
