# Spotify Homepage Clone 🎵

A pixel-perfect, responsive frontend replica of the Spotify Web Player desktop homepage built from scratch using only semantic HTML5 and custom CSS3. 

This project was built to master structural layouts, axis alignments, and responsive interface design without relying on external UI libraries or Bootstrap.

---

## ✨ Features

* **3-Panel Dashboard Layout:** Implements a rigid desktop window layout featuring a fixed-width sidebar, a scrollable primary content feed, and an absolute-bottom media playback controller.
* **Custom Scrollbar Styling:** Overrides the generic default browser scrollbars with Spotify's sleek, thin, dark-themed indicator tracks.
* **Micro-interactions:** Smooth transition parameters tied to anchor hovers, opacity modifications on standard svg buttons, and interactive card scaling transformations.
* **Pure CSS Responsiveness:** Uses fluid breakpoints via media queries to alter layout spacing gracefully across various desktop and laptop monitor sizes.

---

## 🛠️ Tech Stack

* **HTML5:** Structured using semantic layout tags (`<aside>`, `<main>`, `<nav>`, `<section>`, `<footer>`) rather than generic nested generic divs.
* **CSS3:** Custom native properties (variables) for consistent color palettes, multi-directional Flexbox alignments, CSS Grid areas, and explicit viewport media queries.

---

## 🧠 Key Development Challenges Addressed

1. **Independent Container Scrolling:** Forcing the navigation sidebar and the music controller to stay locked on screen while allowing the main middle content area to scroll independently.
2. **Text Truncation Handling:** Using `text-overflow: ellipsis` along with explicit container limits to smoothly cut off exceptionally long song and artist text strings without breaking card parameters.
3. **Perfect Grid Uniformity:** Preserving identical, responsive square aspect proportions across all album cards within the grid container structure.

---
