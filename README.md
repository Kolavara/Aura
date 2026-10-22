# AURA // By Women, For Women 🛡️✏️

**AURA** is an open-source, crowd-verified women's street safety platform powered by the **R-Algorithm** for safe routing, real-time risk heatmaps, emergency tools, and an authentic **Hand-Drawn Paper & Sketch Design System**.

Unlike standard navigation apps that route women down unlit, dangerous alleys to shave 2 minutes off travel time, AURA prioritizes physical safety, well-lit commercial boulevards, active foot traffic, and verified 24/7 safe havens.

---

## 🌟 Key Features

### 1. 🧭 R-Algorithm Safe Routing Engine
- **Dynamic Cost Function**: Calculates routes balancing physical distance against hyper-local risk weights:
  $$\text{Cost}(e) = \text{Dist}(e) \times [1 + \alpha \cdot \text{Risk}(e, t) - \beta \cdot \text{Haven}(e)]$$
- **Time-Aware Risk ($\alpha$)**: Automatically escalates penalties during night and late-evening hours.
- **Corridor Options**:
  - **R-Algorithm Safe Corridor**: Stays on well-lit avenues and verified safe havens.
  - **Balanced Main Road**: Moderate commercial corridors.
  - **GPS Shortcut (Risky)**: Demonstrates the hazard shortcuts typical navigation algorithms produce.
- **Walk Simulation**: Real-time guided escort simulation with live waypoint progress tracking.

### 2. 🗺️ Interactive Crowd-Verified Map
- Built with **Leaflet.js** and **OpenStreetMap** tiles styled with a warm parchment aesthetic.
- **Heatmap Pins**: High-risk unlit areas, caution blind turns, and audited safe spots.
- **Interactive Reporting**: Tap any location to submit crowd-verified hazard warnings with tags (`Broken Lights`, `Catcalling`, `No CCTV`, `Bar Spillover`, `Deserted`).
- **Global & Local Auto-Zoom**: Automatically focuses on your neighborhood via browser Geolocation or searchable global presets (Bengaluru, Mumbai, Delhi, London, NYC, Tokyo, etc.).

### 3. 📞 Realistic Native Smartphone Fake Call (Decoy)
- Looks 100% like a native smartphone phone call (OLED black screen, San Francisco/Roboto typography, circular action buttons).
- **Ringing State**: Incoming call screen from "Dad", "Roommate", or "Police Desk (112)" with synthetic ringtone audio.
- **Connected State**: Interactive 6-button audio matrix (`mute`, `keypad`, `speaker`, `add call`, `FaceTime`, `contacts`), incrementing timer, and discreet spoken prompter script.

### 4. 🚨 Emergency Safety Shield (SOS)
- **3-Second Auto-Dispatch Countdown**: Alerts emergency contacts and nearby verified women with live GPS coordinates.
- **Synthesized Acoustic Siren**: Piercing alarm via the HTML5 Web Audio API to draw immediate crowd attention.
- **Emergency Ride Voucher**: One-tap copy for subsidized night cab pickups (`SISTER-SAFE-100`).

### 5. ⚡ Safety Toolkit
- **🚕 Cab Plate Lock**: Enters plate number and alerts contacts if the driver deviates >150m from the safe corridor.
- **⏱️ Auto-Escalation Check-In Timer**: Countdown timer triggering emergency escalation unless the user confirms "I'm Safe".
- **👭 Walk With A Sister**: Match with nearby verified women traveling along the same corridor.
- **🕶️ Stealth Grocery Note Decoy**: Disguises the app as a realistic recipe & grocery notepad.

---

## 🎨 Design Philosophy: Hand-Drawn Paper & Sketch

The interface embraces organic, human imperfection:
- **No Straight Lines**: Wobbly, multi-radius elliptical borders for every card, button, and input.
- **Paper Textures**: Warm `#fdfbf7` paper canvas layered with a subtle dot grid.
- **Cut-Paper Shadows**: Hard, solid offset shadows (`4px 4px 0px #2d2d2d`) with zero blur.
- **Handwritten Typography**: Google Fonts **Kalam** (felt-tip marker headings) and **Patrick Hand** (legible body script).
- **Physical Details**: Translucent kraft masking tape strips, red thumbtacks, and post-it note callouts.

---

## 🚀 Getting Started

AURA is zero-build and completely client-side:

```bash
# Clone the repository
git clone https://github.com/Kolavara/Aura.git

# Navigate into project directory
cd Aura

# Open with any static web server (e.g., Python)
python -m http.server 8000
```

Open [http://localhost:8000/aura_by_women_for_women_crowd_verified_safety_map_r_algorithm_safe_router.html](http://localhost:8000/aura_by_women_for_women_crowd_verified_safety_map_r_algorithm_safe_router.html) in your browser or smartphone.

---

## 📄 License
MIT License. Built for women's safety worldwide.
