# SVG Color Analyzer 🎨 (SVG Farb-Analysator)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-success?style=for-the-badge)

*Bilingual Web Application (German / English) to analyze the exact pixel-by-pixel color distribution of SVG vector graphics.*

---

## 🇺🇸 English Info

This repository contains a high-performance, single-file Web Application that allows you to upload any `.svg` file and calculates exactly which colors are present and in what proportions.

### ✨ Features
* **Zero Dependencies:** The entire logic (including the image parsing and mathematical analysis), styling (Tailwind via CDN), and PWA config is housed in a single `index.html` file. No build step required!
* **Exact Pixel Math:** Parses the SVG onto a hidden canvas and loops through the image data to ensure mathematically exact results. Uses the *Hare-Niemeyer* method to ensure percentages sum up to exactly 100.00%.
* **Color Grouping Tolerance:** Features a slider to group similar colors (anti-aliasing shades) based on euclidean distance in the RGB color space.
* **Bilingual:** Instantly switch between English and German.
* **PWA / Installable:** Contains an inline manifest and service worker. You can "Add to Home Screen" on iOS/Android or install it on your Desktop. 

### 🚀 Usage
1. Clone the repository or simply download `index.html`.
2. Open `index.html` in any modern web browser.
3. *Alternatively:* Host it directly via GitHub Pages!

---

## 🇩🇪 Deutsche Info

Dieses Repository enthält eine extrem performante Single-File Web-App. Du kannst jede beliebige `.svg` Datei hochladen und die App berechnet dir pixelgenau, welche Farben zu welchem Anteil darin enthalten sind.

### ✨ Funktionen
* **Keine Abhängigkeiten:** Die gesamte Logik, das Styling (Tailwind via CDN) und die PWA-Konfiguration befinden sich in einer einzigen `index.html`. Kein Build-Prozess nötig!
* **Exakte Mathematik:** Die SVG wird auf ein verstecktes Canvas-Element gerendert und pixel für pixel ausgelesen. Nutzt das *Hare-Niemeyer-Verfahren*, um sicherzustellen, dass die Anteile exakt 100,00% ergeben.
* **Toleranz-Regler:** Bietet die Möglichkeit, ähnliche Farbtöne (z.B. durch Kantenglättung/Anti-Aliasing) basierend auf euklidischer Distanz im RGB-Raum zusammenzufassen.
* **Zweisprachig:** Direkter Wechsel zwischen Deutsch und Englisch möglich.
* **PWA / Installierbar:** Dank Inline-Manifest und Service Worker kann die Seite über "Zum Startbildschirm hinzufügen" als App installiert werden.

### 🚀 Nutzung
1. Repository klonen oder die `index.html` herunterladen.
2. Die `index.html` im Browser öffnen.
3. *Alternativ:* Kostenlos über GitHub Pages hosten!

---
### License
MIT License - feel free to use and modify!
