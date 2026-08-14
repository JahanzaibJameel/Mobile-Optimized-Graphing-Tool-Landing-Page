# SuperGraph Pro 2026

**Advanced Calculator & Data Visualization Tool**

A modern, all-in-one web application for scientific computation and interactive data visualization — built with pure HTML5, CSS3, and JavaScript.

![Version](https://img.shields.io/badge/version-2026.1-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Dependencies](https://img.shields.io/badge/dependencies-Chart.js%20%2B%20Math.js-orange.svg)

---

## 📖 Overview

SuperGraph Pro 2026 is a sophisticated single-page web application designed for scientists, engineers, students, and data analysts. It combines a full-featured scientific calculator with a dynamic data graphing tool, all wrapped in a sleek glassmorphism UI with dark/light theme support.

No installation or build process is required — simply open the HTML file in any modern browser and start computing.

---

## ✨ Features

### 🧮 Scientific Calculator

* **Three modes:** Basic, Scientific, and Programmer
* Full expression evaluation powered by **Math.js**
* Support for trigonometric, logarithmic, and exponential functions
* Mathematical constants including **π** and **e**
* Bitwise operations for Programmer mode:

  * AND
  * OR
  * XOR
  * NOT
  * Bit shifts
* Decimal, binary, octal, and hexadecimal base conversion
* Calculation history with the last **50 entries** stored locally
* Keyboard support for:

  * Digits
  * Enter
  * Backspace
  * Escape

### 📈 Data Grapher & Visualizer

* **Four chart types:**

  * Line
  * Bar
  * Area
  * Doughnut
* Interactive and responsive charts powered by **Chart.js**
* Customizable number of data points from **2–50**
* Real-time graph generation
* Beautiful color palettes
* Interactive tooltips

### 🌗 User Experience

* Dark/Light theme toggle
* Persistent theme preference using `localStorage`
* Fully responsive design
* Orientation detection with landscape recommendations for mobile
* Smooth page transitions
* Micro-interactions
* Glassmorphism cards with backdrop blur
* Error and success notifications with automatic dismissal

### ⚙️ Technical Highlights

* Single-file architecture
* No external CSS or JavaScript files except CDN libraries
* State management through a dedicated `AppState` class
* Local persistence
* Custom CSS animations and gradients
* Cross-browser compatibility
* No build tools or frameworks
* Pure vanilla JavaScript

---

---



## 🛠️ Technologies Used

| Technology            | Purpose                                |
| --------------------- | -------------------------------------- |
| **HTML5**             | Structure and semantic markup          |
| **CSS3**              | Styling, animations, responsive design |
| **JavaScript (ES6+)** | Application logic and state management |
| **Chart.js v4.4.0**   | Interactive chart rendering            |
| **Math.js v12.0.0**   | Mathematical expression evaluation     |

Both Chart.js and Math.js are loaded through CDN, so an internet connection is required for full functionality.

---

## 📦 Installation & Usage

### Option 1: Open Directly

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Start using SuperGraph Pro 2026.

No installation or build process is required.

### Option 2: Use a Local Server

For the best development experience, serve the project through a local HTTP server.

#### Using Python

```bash
# Python 3
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

#### Using Node.js

If you have `http-server` available:

```bash
npx http-server
```

#### Using VS Code

Install the **Live Server** extension, open the project in VS Code, and click **Go Live**.

---

## 🗂️ Project Structure

```text
supergraph-pro-2026/
├── index.html          # Main application containing HTML, CSS, and JavaScript
├── screenshots/        # Optional application screenshots
└── README.md           # Project documentation
```

---

## 🕹️ How to Use

### Calculator

1. Click **Scientific Calculator** on the home page.
2. Use the on-screen calculator buttons or your keyboard.
3. Switch between **Basic**, **Scientific**, and **Programmer** modes.
4. Enter and evaluate mathematical expressions.
5. View previous calculations in the history section.

### Grapher

1. Click **Data Grapher & Visualizer** on the home page.
2. Select your preferred chart type.
3. Choose the number of data points between **2 and 50**.
4. Click **Continue**.
5. Enter the values for each data point.
6. Click **Generate Graph**.
7. View the generated chart.
8. Modify the values and regenerate the graph whenever needed.

---

## 🌐 Browser Support

| Browser           | Supported |
| ----------------- | --------- |
| Chrome 80+        | ✅         |
| Firefox 75+       | ✅         |
| Safari 13+        | ✅         |
| Edge 80+          | ✅         |
| Internet Explorer | ❌         |

> JavaScript must be enabled. An internet connection is required to load the Chart.js and Math.js CDN libraries.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve SuperGraph Pro 2026:

1. Fork the repository.
2. Create a new feature branch:

```bash
git checkout -b feature/YourFeature
```

3. Make your changes.
4. Commit your changes:

```bash
git commit -m "Add some feature"
```

5. Push the branch:

```bash
git push origin feature/YourFeature
```

6. Open a Pull Request.

Please ensure your code follows the existing project conventions and is well documented.

---

## 📄 License

This project is licensed under the **MIT License**.

See the `LICENSE` file for complete license details.

---

## 🙏 Acknowledgements

* **Chart.js** — for powerful and interactive chart rendering.
* **Math.js** — for robust mathematical expression evaluation.
* **Open-source community** — for inspiration, tools, and resources.

---

## ❤️ Built With

Built with **HTML5, CSS3, and JavaScript** for the scientific and data-driven community.

**SuperGraph Pro 2026 — Precision Meets Visualization.**
