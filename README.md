# HEMPZ Skin Care – Animated Landing Page

An animated, fully responsive landing page for a skin care brand, built with HTML and pure CSS.

**🔗 Live demo:** https://laurence421.github.io/Skin-Care-Landing-Page-Animated/

## ✨ Features

*   **Pure CSS Animations**: Smooth, high-performance visual effects built entirely with CSS (`@keyframes`, transitions, transforms and scroll-driven `animation-timeline`) without relying on JavaScript libraries.
*   **Infinite Product Carousel**: The "Signature Collections" cards loop seamlessly and pause when you hover over them.
*   **Desktop-First, Fully Responsive Layout**: Designed for large screens first, then scaled down with CSS Media Queries, Flexbox and Grid for laptops (≤1024px), tablets (≤900px) and phones (≤768px / ≤480px) with no horizontal scrolling.
*   **Mobile Navigation**: Below 768px the menu collapses into a hamburger button that opens a full-screen, touch-friendly menu (closes with the ✕ button, a link tap, or the Escape key).
*   **Accessibility**: Descriptive image alt text, labelled menu buttons, and animations turned off for visitors who enable "reduce motion" in their system settings.

## 🌐 Browser Support

| Browser | Layout & menu | Scroll animations |
| --- | --- | --- |
| Chrome / Edge / Opera | ✅ | ✅ |
| Safari 26+ | ✅ | ✅ |
| Firefox / older Safari | ✅ | Turned off – all content is shown without the scroll effects |

The scroll animations use `animation-timeline: view()`. Browsers that don't support it fall back to a static page through `@supports`, so nothing is ever left hidden.

## 🛠️ Tech Stack

*   **HTML5**: Semantic markup structuring.
*   **Pure CSS3**: Custom animations, styling, and structural layout.
*   **Vanilla JavaScript**: A few lines that open and close the mobile menu.

## 📁 Project Structure

```
├── index.html                 # page markup + mobile menu script
├── css/
│   ├── Skin_care.css          # base (desktop) layout and mobile menu styles
│   ├── skin_animation.css     # keyframes, scroll-driven animations, carousel
│   └── skin_responsive.css    # breakpoints for laptop, tablet and phone
└── images/                    # product photos, models and icons
```

## 🚀 Run Locally

No build step is needed:

```bash
git clone https://github.com/Laurence421/Skin-Care-Landing-Page-Animated.git
cd Skin-Care-Landing-Page-Animated
```

Then open `index.html` in your browser.

## ✅ Roadmap
- [x] Implement fully responsive design using CSS Media Queries or Flexbox/Grid.
- [x] Add mobile-friendly navigation and touch-responsive layouts.
- [x] Make the page usable in browsers without scroll-driven animation support.
- [x] Seamless, hover-pausable product carousel.

## 🎯 Credits & Inspiration
*   Layout design credit: [Figma – UI practice](https://www.figma.com/design/VjWAdYTBk3yvtmzs6K697y/UI-practice?node-id=0-1&p=f&t=KZuDJmmMrlPaMbuj-0)
*   *Note: This project is a front-end cloning practice to improve my HTML, CSS, and JavaScript skills.*
