# 🚌 Rayong Tour Clone (Pure HTML & Tailwind CSS)

A responsive redesign of the **Rayong Tour** bus booking service website. This project focuses on pushing the boundaries of **HTML5** and **Tailwind CSS** to create a fully functional, interactive user interface **without writing a single line of JavaScript**.

🔗 **Live Demo:** [Click here to view](#) *(Add your Vercel/GitHub Pages link here)*

## 🎯 Project Goals

- **Zero JavaScript Challenge:** Implement interactive features like mobile navigation, hover states, and animations using only CSS/HTML techniques.
- **Responsive Design:** Ensure pixel-perfect rendering from mobile phones to desktop screens.
- **Modern UI/UX:** utilizing Glassmorphism, smooth transitions, and engaging animations.

## 🛠 Tech Stack

- **HTML5**: Semantic structure.
- **Tailwind CSS**: Utility-first CSS framework for styling and animations.
- **Lucide Icons**: Scalable vector icons.

## ✨ Key Features

### 1. CSS-Only Mobile Navigation (The "Checkbox Hack")
Instead of using JavaScript Event Listeners to toggle the mobile menu, this project utilizes the HTML `<input type="checkbox">` combined with Tailwind's `peer` and `peer-checked` modifiers.

```html
<input type="checkbox" id="mobile-menu" class="hidden peer">

<nav class="mobile-menu-dropdown hidden peer-checked:block ...">
   ...
</nav>
