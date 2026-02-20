# PWA Temperature Converter

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A lightweight Progressive Web App that converts temperatures between Celsius, Fahrenheit, and Kelvin in real time. Installable on any device and fully functional offline.

## Overview

This temperature converter demonstrates core PWA concepts including service worker registration, offline caching, and a web app manifest for installability. The app provides instant conversions as you type, with a clean and responsive card-based UI.

## Features

- Real-time temperature conversion between Celsius, Fahrenheit, and Kelvin
- Installable as a standalone app on desktop and mobile devices
- Fully functional offline via service worker caching
- Clean, responsive card-style interface using CSS Grid
- Lightweight with zero external dependencies

## Prerequisites

- A modern web browser (Chrome, Edge, Firefox, or Safari)
- A local web server for development (e.g., `python -m http.server` or VS Code Live Server)
- HTTPS for service worker registration in production

## Getting Started

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/pwa-temp-converter.git
   cd pwa-temp-converter
   ```

2. Serve the files using any static web server:
   ```bash
   python3 -m http.server 8000
   ```

### Usage

1. Open `http://localhost:8000` in your browser.
2. Enter a temperature value, select the source unit, and choose the target unit.
3. The converted result updates automatically as you type.
4. To install as a standalone app, click the install prompt in your browser's address bar.

## Tech Stack

- **HTML5** -- Semantic form structure with accessible labels
- **CSS3** -- Responsive layout with CSS Grid and modern styling
- **JavaScript** -- Temperature conversion logic and service worker registration
- **Service Worker** -- Cache-first strategy for offline support
- **Web App Manifest** -- PWA metadata for installability

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
