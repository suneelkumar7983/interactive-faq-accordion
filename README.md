# Interactive FAQ Accordion Component

A responsive, lightweight FAQ dropdown module designed to improve landing page user experience (UX) and save screen space on mobile devices.

## 🚀 Business Features
- **Auto-Closing State Management:** Automatically closes any previously opened question when a user selects a new one, preventing page clutter.
- **Scalable Architecture:** Built using dynamic DOM traversal so clients can add unlimited questions without modifying the JavaScript logic.
- **Mobile-First Design:** Clean flexbox alignment and touch-friendly tap targets.

## 🛠️ Tech Stack & Concepts Used
- **Semantic HTML5 & CSS3:** Clean card UI with smooth state transitions.
- **Vanilla JavaScript:**
  - `querySelectorAll()` and `.forEach()` loops for scalable event handling.
  - DOM Traversal using `nextElementSibling` to target specific answers dynamically.
  - CSS class manipulation using `classList.contains()`, `remove()`, and `add()`.
