# Metrical Dissonance Simulator

A lightweight, web-based audiovisual simulator for **Metrical Dissonance**, inspired by Harald Krebs's music theory. 

## Features

* **Audiovisual Feedback:** Distinct visual nodes and audio frequencies (440Hz vs 660Hz) clearly differentiate the Primary Metrical Layer from the Interpretive Layer.
* **Real-time Formulas:** Dynamically calculates and displays Krebs's formulas — $G(x/y)$ for Grouping Dissonance and $D(x+y)$ for Displacement Dissonance.
* **Mobile Friendly:** Includes a native audio-unlock sequence that successfully bypasses the iOS hardware mute switch, ensuring reliable playback on iPhones and iPads.
* **Zero Dependencies:** Built entirely with vanilla HTML, CSS, and JavaScript. Simply open the file in any modern browser to run.

## How to Use

1. Open `index.html` in your web browser.
2. Select the type of dissonance (Grouping or Displacement).
3. Adjust the base meter (Primary) and conflict meter (Interpretive) parameters.
4. Set your desired BPM and click Play.

## 📂 Project Structure & Deployment

* `index.html`: A single file containing all UI layouts, styles, and core interactive logic.
* This project is statically hosted and deployed via **GitHub Pages**.

## 📄 Academic Declaration & Citation

This program serves as a digital appendix to the author's degree thesis. 
If you utilize this tool in academic research, teaching demonstrations, or thesis writing, please cite it using the following format:

> **[Suggested Citation]**
> Xingyu Zhu. Metrical Dissonance Simulator [OL]. GitHub Pages, 2026. `https://CodeMaestro-Z.github.io/metrical-theory-demo/`

## Changelog

### v1.1.0 (2026-07-15)
* **Localization:** Updated UI language to Japanese with standard music theory terminology.
* **Feature:** Added dynamic Krebs formula display.
* **Fix:** Implemented an audio unlock sequence (silent WAV buffer) to prevent the iOS physical mute switch from muting the Web Audio API.

### v1.0.0
* Initial release featuring core Grouping and Displacement dissonance simulations.
