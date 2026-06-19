# 🎨 Pixel Art Generator

A dynamic, responsive, and interactive web-based **Pixel Art Generator** built from scratch using clean **HTML5, CSS3, and Vanilla JavaScript**. This application allows users to create custom grids, pick colors, and paint or erase pixels fluidly on both desktop and mobile devices.

---

## 🚀 Features

* **Customizable Grid Dimensions:** Dynamically adjust the grid width and height (up to 35x35) using intuitive sliders.
* **Real-Time Drawing Mechanics:** Seamlessly click/tap and drag to paint or erase multiple pixels continuously.
* **Color Picker:** Integrated color palette selection using native HTML5 color elements.
* **Cross-Device Compatibility:** Built-in automatic device type detection handles both `mouse` and `touch` events for smooth mobile functionality.
* **Responsive Design:** Styled using viewport relative units (`vmin`) and CSS media queries to ensure the grid fits beautifully on all screen sizes.

---

## 🛠️ Tech Stack

* **HTML5:** Structured semantic layout.
* **CSS3:** Styled with custom color swatches, flexbox layouts, and fully responsive media queries.
* **JavaScript (ES6+):** Pure Vanilla JS handling dynamic DOM manipulation, real-time coordinate checking (`elementFromPoint`), and multi-device event listeners.

---

## 📂 Project Structure

```text
├── index.html     # Application layout & UI structure
├── style.css      # Custom styling, themes, and responsiveness
└── index.js       # Main logic, grid generation, and event handlers
