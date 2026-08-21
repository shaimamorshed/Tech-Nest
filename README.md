# TechNest 🛒

A fully responsive e-commerce front-end for a premium technology retailer, built with **HTML5** and **Tailwind CSS v4**. TechNest showcases a complete shopping experience — from product discovery to checkout — with pixel-perfect designs translated from Figma across mobile, tablet, and desktop breakpoints.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)




---

## 📖 Overview

TechNest is a modern, multi-page e-commerce website built to demonstrate best practices in responsive web design using utility-first CSS. Every page is designed mobile-first and scales seamlessly across three breakpoints, with reusable Tailwind components, custom utility classes, and consistent design tokens throughout.

---

## ✨ Features

- **Fully Responsive Design** — Optimized layouts for Mobile (< 768px), Tablet (768px–1023px), and Desktop (1024px+)
- **Complete Shopping Flow** — Home → Product Listing → Product Details → Cart → Checkout
- **User Authentication** — Login / Sign Up pages with social auth UI
- **User Profile Dashboard** — Personal details, security settings, order history
- **Interactive Product Filtering** — Category, brand, price range, and rating filters
- **Custom Design System** — Reusable Tailwind `@utility` classes and `@layer components` for consistent styling
- **Accessible Markup** — Semantic HTML with proper `alt` attributes and ARIA-friendly structure
- **Micro-interactions** — Hover states, active states, and smooth transitions throughout

---

## 📄 Pages

| Page | Description |
|---|---|
| `index.html` | Home page — hero banner, categories, featured products, deals, testimonials |
| `products.html` | All Products — filterable, sortable product grid |
| `product-details.html` | Single product view — gallery, variants, specs, recommendations |
| `cart.html` | Shopping cart — item management, order summary, promo codes |
| `login.html` | Login / Sign Up |
| `profile.html` | User profile — personal info, security, order history |
| `contact.html` | Contact page — inquiry form, location, FAQ |

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **Tailwind CSS v4** — Utility-first styling with custom `@utility` and `@layer components`
- **Google Fonts** — Inter, Quicksand, Raleway, Roboto
- **Vanilla JavaScript** — Lightweight interactivity (filter sheets, accordions)

---

## 📁 Project Structure

```
TechNest/
├── index.html
├── products.html
├── product-details.html
├── cart.html
├── login.html
├── profile.html
├── contact.html
├── src/
│   ├── input.css          # Tailwind source (custom utilities & components)
│   ├── output.css         # Compiled Tailwind CSS
│   └── imgs/               # Product photos, icons, and illustrations
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed
- Tailwind CSS CLI (`npm install -D tailwindcss`)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/shaimamorshed/Tech-Nest.git
   cd Tech-Nest
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Build Tailwind CSS (with live watch)
   ```bash
 npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
   ```

4. Open `index.html` in your browser (or use a Live Server extension)

---

## 📱 Responsive Breakpoints

| Breakpoint | Range | Prefix |
|---|---|---|
| Mobile | < 768px | default |
| Tablet | 768px – 1023px | `md:` |
| Desktop | ≥ 1024px | `lg:` |

---

## 🎨 Design

UI/UX designed in **Figma**, translated pixel-by-pixel into responsive, production-ready HTML and Tailwind CSS.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to check the [issues page](https://github.com/shaimamorshed/Tech-Nest/issues).

---

## 📜 License

This project is open source and shared for educational and portfolio purposes. Feel free to explore the code for learning, but please don't redistribute it as your own work.

---

## 👤 Author

**Shaimaa Morshed**
GitHub: [@shaimamorshed](https://github.com/shaimamorshed)
