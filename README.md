# 🎨 WonderCraft

> **Create. Paint. Smile.**

WonderCraft is a colorful, interactive e-commerce landing website for **DIY plaster painting kits for kids**. The platform is designed to make creative, screen-free activities accessible to children through affordable, ready-to-paint craft kits.

The website showcases WonderCraft products, explains the benefits of creative play, provides an interactive product experience, and includes an order flow for customers.

---

## ✨ Features

### 🛍️ Product Showcase

* Multiple DIY painting kits
* Product names, prices, descriptions and themes
* Quick-view product modal
* Dynamic product rendering using JavaScript
* Easy-to-update product data

Current product themes include:

* 🦁 Wonder Zoo Kit
* 🌊 Under The Sea Kit
* 🦖 Dino Discovery Kit
* 🏰 Fairy Tale Castle Kit
* 🚀 Space Explorer Kit
* 🪔 Festival Diya Special

Product information is maintained through a JavaScript `PRODUCTS` array, making the catalog relatively easy to update.

### 🎨 Interactive User Experience

The website includes:

* Animated loading screen
* Custom cursor
* Hover animations
* Scroll reveal animations
* Animated statistics counters
* Hero section animation
* Product hover effects
* Gallery lightbox
* Quick-view product modal
* Confetti animation after successful ordering
* Smooth scrolling
* Back-to-top button

### 🌙 Dark Mode

Users can switch between light and dark themes.

The selected theme is stored in `localStorage`, allowing the preference to persist when the user returns to the website.

### 📦 Order System

The website contains an interactive order modal where customers can provide:

* Customer details
* Address
* State
* Product
* Quantity
* Payment method

Available payment selections include:

* Cash on Delivery
* UPI
* Online Payment

After submission, the interface displays an order-success screen with an order ID.

### 💬 WhatsApp Integration

A floating WhatsApp/contact option allows customers to directly initiate a conversation for ordering or enquiries.

### 📱 Responsive Design

The website is designed to work across:

* Desktop
* Laptop
* Tablet
* Mobile

The navigation automatically changes to a mobile hamburger menu on smaller screens.

### 🖼️ Gallery

A dedicated gallery section showcases WonderCraft kits and artwork with an interactive lightbox experience.

### ⭐ Testimonials

The website includes a testimonial carousel with:

* Customer name
* Customer role/location
* Rating
* Customer feedback
* Previous/next navigation
* Carousel indicators

### ❓ FAQ

An expandable FAQ section answers common customer questions without requiring a separate page.

### ♿ Accessibility & UX

The project includes several accessibility-conscious features:

* Skip-to-content link
* Visible keyboard focus states
* ARIA labels for interactive controls
* Responsive navigation
* Reduced-motion support through `prefers-reduced-motion`

---

## 🧰 Tech Stack

| Technology         | Purpose                                   |
| ------------------ | ----------------------------------------- |
| HTML5              | Website structure                         |
| CSS3               | Styling, responsive layout and animations |
| Vanilla JavaScript | Interactions and dynamic functionality    |
| SVG                | Product illustrations and visual elements |
| LocalStorage       | Theme persistence                         |
| Google Fonts       | Poppins typography                        |

The project intentionally uses **vanilla HTML, CSS and JavaScript** and does not require React, Vite, Node.js or a build system.

---

## 📂 Project Structure

```text
WonderCraft/
│
├── index.html
└── README.md
```

The current implementation keeps the website inside a single `index.html` file, including:

* HTML structure
* CSS styles
* JavaScript logic
* Product data
* Testimonials
* FAQ data
* Interactive components

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/wondercraft.git
```

### 2. Open the project

```bash
cd wondercraft
```

### 3. Run the website

Because WonderCraft is a static website with no build step, you can simply open:

```text
index.html
```

in your browser.

For a better development experience, you can also use **VS Code Live Server** or another local static server.

---

## 🛠️ Customizing Products

Products can be modified from the JavaScript `PRODUCTS` array.

Example:

```javascript
const PRODUCTS = [
  {
    id: 'zoo',
    name: 'Wonder Zoo Kit',
    price: 39,
    blurb: 'Lion, elephant & giraffe waiting to be painted.',
    c1: '#FFD93D',
    c2: '#FF6B6B'
  }
];
```

You can add, remove or modify products without rebuilding the application.

---

## 🎯 Target Audience

WonderCraft is designed primarily for:

* 👨‍👩‍👧 Parents
* 🏫 Schools
* 🎂 Birthday parties
* 🎁 Return gifts
* 🧒 Children looking for creative activities
* 🏡 Families looking for screen-free activities
* 🎉 Events and workshops

---

## 💡 Why WonderCraft?

WonderCraft focuses on turning passive screen time into hands-on creative activity.

The kits are designed around a simple experience:

```text
Create → Paint → Smile
```

Each kit combines painting, creativity and play in a simple activity that children can complete and display.

---

## 📋 What's Inside the Kits?

The website presents each WonderCraft kit as containing:

* 3 plaster models
* 3 paint colours
* 1 soft brush
* Premium packaging

The exact contents can be modified as the product line evolves.

---

## 🔮 Future Improvements

Potential improvements for the next version include:

* [ ] Backend order management
* [ ] Database integration
* [ ] Real payment gateway
* [ ] Admin dashboard
* [ ] Customer authentication
* [ ] Order tracking
* [ ] Inventory management
* [ ] Product image upload
* [ ] Customer reviews
* [ ] Coupon/discount system
* [ ] Automated order confirmation
* [ ] Email/SMS/WhatsApp order notifications
* [ ] Analytics dashboard
* [ ] SEO improvements
* [ ] Production-grade form validation
* [ ] Secure server-side order processing

---

## ⚠️ Current Project Scope

This repository currently represents the **frontend/static implementation** of the WonderCraft website.

The order interface provides the customer-facing experience, but a production e-commerce system should connect the order flow to a secure backend, database and payment provider before processing real transactions.

---

## 📸 Project Preview

Add screenshots of the website here:

```text
screenshots/
├── home.png
├── products.png
├── order-modal.png
├── dark-mode.png
└── mobile.png
```

Then add them to this README:

```markdown
![WonderCraft Homepage](screenshots/home.png)
```

---

## 👨‍💻 Developer

**Zayan**

Built as a product/business website for **WonderCraft**, a DIY creative activity kit brand for kids.

---

## 📄 License

This project is currently intended for WonderCraft's website and business use.

If you plan to make the repository open-source, add an appropriate open-source license such as MIT after confirming that the project's assets, branding and content can legally be distributed.

---

<p align="center">

### 🎨 WonderCraft

**Create. Paint. Smile.**

</p>
