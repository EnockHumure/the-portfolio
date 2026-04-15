# Enock Humure | Personal Portfolio 🚀

A high-performance, modern, and responsive personal portfolio website built with a focus on developer aesthetics and user experience. This project showcases my journey as a Software Engineering student at AUCA and an A2SV trainee.

---

## 🛠️ Recent Updates & Improvements

### 1. **Integrated Contact System (Formspree AJAX)**
The contact form is now fully functional. It uses the **Formspree Vanilla JS (Ajax) SDK** to handle email delivery without page reloads.
- **Direct Delivery:** Messages are sent straight to `humureenock@gmail.com`.
- **User Feedback:** Includes real-time "Sending..." states, success messages, and error handling.
- **Secure Handling:** Leverages the Formspree endpoint (`xjgjgbgz`) for reliable transport.

### 2. **Multi-Language Support (i18n)**
The portfolio now supports four languages with a "bulletproof" switching logic:
- **Languages:** English (EN), Kinyarwanda (RW), Swahili (SW), and French (FR).
- **Persistence:** Remembers the user's language preference using `localStorage`.
- **Dynamic Translation:** All sections (Hero, About, Skills, Projects, Contact) translate instantly without a refresh.

### 3. **Modern UI/UX Features**
- **Terminal Widget:** A Linux-style interactive terminal in the Hero section reflecting my Linux expertise.
- **Custom Cursor:** A sophisticated dual-layer (dot & ring) cursor with smooth "lerp" animation and interactive hover states.
- **Glassmorphism:** Advanced CSS effects using `backdrop-filter` for a sleek, frosted-glass look on cards and navigation.
- **Image Tilt Effect:** Interactive profile pictures that tilt based on mouse movement.
- **Theme Toggle:** Dark/Light mode support with persistence.

---

## 📂 Project Structure

- `index.html`: The core structure featuring a Bento Grid layout for projects and skills.
- `style.css`: Custom CSS with dynamic mesh backgrounds, scanline overlays, and responsive breakpoints.
- `script.js`: Contains the core logic for animations, theme switching, and language updates.
- `translations.js`: A dedicated module for managing multi-language content strings.

---

## 🚀 Deployment

The portfolio is optimized for static hosting:
- **Live Link:** [inockportfolio.netlify.app](https://inockportfolio.netlify.app/)
- **Hosting:** Successfully deployable on Netlify or GitHub Pages.

---

## 📌 Technical Stack
- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Tools:** Formspree AJAX SDK, Font Awesome, Google Fonts
- **Methodology:** Responsive Design, i18n, Glassmorphism UI

---

## 🙏 Acknowledgements
Special thanks to the **A2SV (Africa to Silicon Valley)** community and **AUCA** for the continuous inspiration and technical growth.
