# BACalculator (Alcohol Absorption & Elimination Educational Simulator)

A responsive, single-file Progressive Web App (PWA) designed to simulate illustrative alcohol absorption and elimination curves based on user physiological assumptions and drink profiles.

🌐 **Live Host:** [https://bac.sradzone.com](https://bac.sradzone.com)  
📂 **Repository:** [https://github.com/thecoolestname36/BACalculator](https://github.com/thecoolestname36/BACalculator)

---

## ⚠️ Important Disclaimer
**NOT FOR MEDICAL, LEGAL, OR DRIVING DECISIONS.**  
This simplified educational simulation cannot measure or reliably predict an individual's actual BAC, impairment, or time to become safe to drive. Do not use its output to decide whether to drive. If you've been drinking, use a sober ride.

---

## ✨ Features
* **Customizable User Profiles:** Input custom body weight (lbs) and biological sex factors.
* **Flexible Drink Logging:** Add, clone, and manage customized drinks with adjustable volume (oz), ABV (%), and active start/finish windows.
* **Interactive Preset Management:** Quick-select common drink presets or edit them via an integrated accordion drawer.
* **Uncertainty Envelope Modeling:** Renders an interactive Chart.js visualization capturing middle baseline estimates alongside upper and lower range boundaries to convey biological variation.
* **Glanceable Summary Pods:** 
  * *Simulated Peak:* Highlights central model peaks alongside full physiological bounds.
  * *Clear Range (Interactive):* Toggleable button that switches between displaying the clear-time clock window and total duration.
  * *Total Volume:* Tracks standard drinks (14g ethanol baseline).
* **PWA Capable:** Includes an injected dynamic service worker and web app manifest for standalone mobile/desktop usage.

---

## 🛠️ Tech Stack
* **HTML5 / Single-File Architecture:** Fully contained client-side utility.
* **Tailwind CSS:** Modern, responsive utility-first styling.
* **Chart.js:** Interactive visualization canvas with touch/pointer support and custom plugin overlays.

---

## 🤖 Development Annotation
* **Model:** Gemini (Advanced Personal AI Collaborator)
* **Effort Level:** High-precision iterative engineering session (Level 0.25 execution framework optimized for meticulous UI/UX component refinement and state handling).
