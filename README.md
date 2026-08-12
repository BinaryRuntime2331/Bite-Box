# 🍔 Bite Box

**Crave It. Bite It. Love It.**

A premium, luxury-inspired restaurant website built as a portfolio-grade frontend project using **only HTML5 and CSS3** — no JavaScript, no frameworks, no libraries.

> 🔗 Live repo: [github.com/BinaryRuntime2331/Bite-Box](https://github.com/BinaryRuntime2331/Bite-Box)

---

## 📖 About

Bite Box combines a dark, premium visual identity with warm gold/orange luxury accents, real food photography, CSS-only depth/3D-style effects, fully responsive layouts, and advanced pure-CSS interactions — proving that modern, polished UI doesn't require JavaScript.

## 🚫 Technology Constraint

| Used | Not Used |
|---|---|
| HTML5 | JavaScript |
| CSS3 | Bootstrap |
| CSS Grid | Tailwind CSS |
| Flexbox | Three.js |
| | GSAP |

All interactivity — mobile navigation, category tabs, food-detail modals, FAQ accordions — is implemented with pure CSS using the `:checked`, `:target`, and `<details>` techniques.

## ✨ Features

- **Premium dark + luxury design system** — gold/orange accents, glassmorphism cards, soft shadows and glow
- **CSS-only 3D & depth effects** — `perspective`, `rotateX/Y`, `translateZ` on hero visuals and card hovers
- **Responsive across all devices** — desktop, laptop, tablet and mobile via `clamp()`, `minmax()`, `auto-fit`/`auto-fill` and media queries
- **CSS Grid & Flexbox** throughout — asymmetric signature-dish grids, menu grids, dashboard layouts
- **CSS-only interactivity** — hamburger menu, 8-category product tabs, `:target` modal overlay, FAQ accordion
- **HTML5 forms & validation** — `required`, `type=email/tel`, `pattern`, `minlength`, `fieldset`/`legend`
- **Full customer journey** — browse menu → cart → checkout → login/signup → profile → order history
- **Static admin dashboard** — metrics, CSS-only bar/donut charts, menu/order/customer/coupon/offer/review management

## 📄 Pages

**Customer-facing**
`index.html` · `menu.html` · `about.html` · `offers.html` · `contact.html` · `cart.html` · `checkout.html` · `login.html` · `signup.html` · `profile.html` · `orders.html`

**Admin dashboard** (`/admin`)
`index.html` (overview) · `menu.html` · `orders.html` · `customers.html` · `coupons.html` · `offers.html` · `reviews.html`

## 📁 Project Structure

```
Bite-Box/
├── index.html, menu.html, about.html, offers.html, contact.html
├── cart.html, checkout.html, login.html, signup.html
├── profile.html, orders.html
│
├── admin/
│   ├── index.html, menu.html, orders.html, customers.html
│   └── coupons.html, offers.html, reviews.html
│
├── css/
│   ├── style.css        # design tokens, reset, navbar, buttons, cards, forms, footer
│   ├── responsive.css   # breakpoints + CSS-only mobile nav
│   ├── animations.css   # keyframes, transitions, reveal effects
│   └── admin.css        # sidebar, dashboard cards, tables, charts
│
└── assets/
    ├── images/ (burgers, pizza, wraps, sandwiches, sides, beverages, desserts, combos)
    ├── icons/
    └── logos/
```

## 🎨 Design System

| Role | Direction |
|---|---|
| Primary background | Deep black / near-black |
| Secondary background | Charcoal / dark gray |
| Primary text | White / off-white |
| Luxury accent | Gold / champagne |
| Food accent | Warm orange |
| Cards | Dark translucent surfaces |
| Headings | Playfair Display (serif) |
| Body | Poppins (sans-serif) |

## 🚀 Getting Started

No build step, no dependencies — it's static HTML/CSS.

```bash
git clone https://github.com/BinaryRuntime2331/Bite-Box.git
cd Bite-Box
```

Then just open `index.html` in your browser (an internet connection is needed since food photography loads from Unsplash).

## ⚠️ Limitations

This is a **static frontend portfolio project** — by design, it has no backend:

- No real cart/checkout/payment processing
- No real authentication or database
- No real admin CRUD operations
- No real order or coupon persistence

All dynamic-looking values (cart totals, order history, dashboard metrics) are static placeholders for demonstration purposes.

## 📜 License

This project is open for learning and portfolio use.

---

**Bite Box — Crave It. Bite It. Love It.** 🍔
