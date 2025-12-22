# Frontend Assignment - Simplotel

This is a responsive webpage built using plain HTML5 and CSS3, as per the assignment requirements. It features a responsive navigation bar, a hero section, and an image gallery grid.

## 🚀 How to Run
1. Download or clone the repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge).
3. No installation (`npm install`) is required as this uses vanilla HTML/CSS.

## 🛠 Tech Stack
* **HTML5:** Used for semantic structure (`<nav>`, `<header>`, `<section>`).
* **CSS3:** Used for styling, including Flexbox for the navbar and Grid for the gallery layout.
* **Vanilla JavaScript:** A minimal script (5 lines) to toggle the mobile hamburger menu.

## 📱 Features
* **Fully Responsive:** Adapts to Desktop, Tablet, and Mobile screens.
* **Mobile Menu:** Converts the navbar into a hamburger menu on smaller screens.
* **Clean Design:** matches the provided design mockups and color scheme.

## ⚖️ Trade-offs & Decisions
* **Images:** I used `object-fit: cover` to ensure images fill their containers without stretching, even if the aspect ratio changes on different devices.
* **CSS Variables:** I avoided pre-processors (SASS/LESS) to stick strictly to the "plain CSS" requirement, but kept the code modular.