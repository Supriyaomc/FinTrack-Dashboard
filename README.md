# 📊 FinTrack - Personal Finance & Analytics Dashboard

A lightweight, secure, and privacy-first web-based analytics client designed to monitor transactional categories and render real-time mathematical visualizations with zero framework dependencies.

---

## 🛠️ Tech Stack

This project is built from scratch utilizing standard browser-native environments to maximize load speed and enforce modern layout patterns:

- **HTML5:** Semantic workspace formatting for screen readers and layout definition.
- **CSS3:** Built with **CSS Grid** architecture and dynamic design variables for a seamless dark-mode configuration.
- **Vanilla JavaScript (ES6+):** Programmed with an event-driven loop structure to manage data state pipelines, cache storage lifecycle, and dynamic object arrays.
- **HTML5 Canvas API:** Custom vector painting implementation used to convert application memory data structures directly into visual canvas representations without heavy downstream libraries (e.g., Chart.js).

---

## 💡 The Problem

Modern web platforms have become increasingly resource-heavy. Standard web platforms frequently load multi-megabyte third-party chart dependencies just to display static arithmetic summaries. 

Simultaneously, users are increasingly sensitive about data ownership. Linking private personal banking ledgers to insecure remote servers raises serious tracking, telemetry, and vulnerability profile concerns.

---

## 🚀 The Solution

**FinTrack** fixes these issues by processing data client-side inside the user's secure browser sandbox. 

1. **State Persistence:** Reads and writes transaction objects directly to a clean local storage profile (`localStorage`).
2. **Zero Overhead:** Features a sub-millisecond execution start loop by stripping out redundant framework abstract bundles.
3. **Custom Graphic Matrix:** Uses direct trigonometric translations mapped onto a native graphic canvas element to visually communicate real-time categorical variations instantly.

---

## 🧠 The Technical Challenge & Complexities

### 1. Vector Graph Mathematics (The Challenge)
The browser's built-in `<canvas>` surface lacks context for objects like grids, pies, or layout legends. To translate an unpredictable array of standard currency inputs into a correct circular breakdown:
- Every individual categorization is totaled against the runtime global transaction summary array.
- Sector proportions are programmatically translated into matching angular radians using the formula:
  \[\text{Radian Slice} = \left(\frac{\text{Category Total}}{\text{Grand Total}}\right) \times 2\pi\]
- Slices are sequentially painted onto coordinates using progressive trigonometric coordinate offsets (`Math.PI * 2`).

### 2. Synchronization Loop Maintenance
Without layout abstraction platforms like React tracking the DOM elements, maintaining data harmony can become unstable. This app relies on a strict single source of truth pipeline (`transactions` data array). Every user event triggers a deterministic downstream synchronization cycle that simultaneously redraws the historical list records, updates metric displays, updates values in persistent cache storage, and triggers a full pixel cleanup/redraw execution thread within the layout canvas context.

---

## 🏎️ Future Scope & Scale Upgrades

- **Web Workers Multi-threading:** Move analytical processing logic completely off the browser's primary execution timeline. This guarantees that importing records with thousands of historical inputs won't result in interface stutters, UI blocking, or frame drops during heavy sorting computations.
- **Data Export Utilities:** Implement localized data format encoders (`.csv` / `.json`) to let users easily back up or transition their encrypted files securely without utilizing server endpoints.

---

## 📦 Local Installation & Setup

1. Clone or download the repository files:
   ```bash
   ├── index.html
   ├── style.css
   └── app.js
   ```
2. Launch `index.html` inside any standard browser window to load the tracking console instantly.
