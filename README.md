## 📐 Pixel & Aspect Ratio Calculator

An elegant, responsive web-based tool to convert between pixel dimensions and aspect ratios. This utility allows users to calculate:

* The **aspect ratio** of any resolution
* A **missing dimension** when an aspect ratio and one side (width or height) are known

Designed for photographers, video editors, UI designers, and developers working with responsive layouts or media content.

### 🔍 Features

* 🔄 **Pixels to Aspect Ratio**: Input width and height to get a simplified ratio and decimal equivalent
* ➕ **Calculate Missing Dimension**: Input one dimension and an aspect ratio to get the other side
* 🧠 Smart suggestions for the closest standard ratios (e.g., 16:9, 4:3)
* ✨ Interactive UI with modern design, animations, and rounded inputs
* 📱 Fully responsive for desktop and mobile devices
* 🎨 Clean aesthetic with CSS blur effects and gradient backgrounds

### 🚀 Getting Started

To use the tool:

1. Clone or download this repository
2. Open `index.html` in your web browser

No build steps or dependencies required — it's pure HTML, CSS, and JavaScript.

### 🔧 File Structure

* `index.html` – Main file containing the UI and logic
* Inline CSS for styling and layout
* Inline JavaScript for all functionality, including:

  * GCD-based ratio simplification
  * Nearest common ratio detection
  * Live DOM updates

### 🧪 Example Use Cases

* Calculate whether `2560×1440` is a 16:9 aspect ratio (yes)
* Determine the appropriate height for `1200px` width at a `4:3` ratio (900px)
* Spot if a non-standard resolution is close to any known formats

### 📜 License

MIT – Free to use, modify, and distribute.
