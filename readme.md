# Dropdown Navigation Component

## 🧭 Overview
This project implements a reusable, responsive dropdown navigation bar built using **HTML, CSS, and JavaScript (ES Modules)**.  
It’s designed for clean scalability — suitable for multi-level menus, multiple dropdowns, and smooth animations using modern CSS features.

---

## ⚙️ Features
- Dynamic dropdown functionality with pure JavaScript (no frameworks).  
- Modern CSS using custom properties (`:root` variables) for easy theme customization.  
- Smooth open/close animation using transitions and transforms.  
- Backdrop blur and subtle scaling effects for modern UI polish.  
- Fully responsive layout using `clamp()` and relative units.  
- Accessibility-aware dropdown logic (only one active menu at a time).  

---

## 🧱 Structure
- **index.html** – Semantic layout containing navigation markup.  
- **style.css** – Handles variables, animations, transitions, and layout styling.  
- **script.js** – Controls dropdown behavior and manages open/close states.  

---

## 🎨 Customization
You can easily modify:
- **Colors** via `--bg-nav-bar` and `--bg-dropdown-menu`.  
- **Spacing** using `--padding-*` and `--gap-*` variables.  
- **Font and weight** through `--font-family` and `--font-weight-link`.  
- **Animation smoothness** via transition durations.  

---

## 🧩 How It Works
1. Each dropdown is wrapped in a `data-dropdown` container.  
2. Buttons use the `data-dropdown-button` attribute.  
3. JavaScript toggles the `active` class on the selected dropdown while closing others.  
4. CSS transitions smoothly animate visibility and position.  

---

## 🚀 Future Enhancements
- Add keyboard navigation for better accessibility.  
- Animate dropdown menu items individually.  
- Implement dark/light mode themes.  

---

## 🧠 Learning Focus
This project reinforces:
- CSS transitions, transforms, and variables.  
- Event delegation and state management in vanilla JS.  
- Responsive design using modern CSS units and techniques.  
