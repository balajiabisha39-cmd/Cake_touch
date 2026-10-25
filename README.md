# Cake_touch
cake bakery
# 🎂 Cake Touch — Boutique Bakery Web Application

> *"Sweeten Your Day with our Treat"*

**Cake Touch** is a responsive, single-page web application (SPA) designed for an artisanal bakery located in Tondiarpet, Chennai. It showcases celebration cakes, daily oven-baked puffs, savory rolls, cupcakes, and donuts, complete with real-time bill calculation, an item inventory manager, and instant UPI payments with dynamic QR scanning.

---

## 🌟 Key Features

- **Multi-Category Catalog:**
  - **Fresh Celebration Cakes:** ½ kg (₹450) and 1 kg (₹850) featuring Dark Chocolate Truffle, Royal Rasmalai, Fruit Jelly, Fresh Cream, and Custom Photo/Design cakes.
  - **Hot Evening Savories:** Egg Puff (Signature), Veg Puff, Chicken Puff, Veg Roll, and Chicken Roll.
  - **Desserts & Treats:** Chocolate and Vanilla Cupcakes, and Classic Glazed Donuts.
- **Perks & Highlights:** Automatic display for free birthday candles and sturdy cake box packaging.
- **Owner Admin Portal ("Add New Item"):**
  - Add new bakery items with custom pricing, categories, tags, descriptions, and images.
  - Changes instantly update the catalog and order dropdowns.
  - Persistent state saved to the browser using `localStorage`.
- **UPI Instant Checkout & Dynamic QR Generator:**
  - Real-time bill recalculation based on item selection and quantity.
  - Dynamically generated UPI payment QR code for `sasiraji142019-1@okhdfcbank`.
  - One-tap deep link for mobile users to open Google Pay, PhonePe, or Paytm directly.
  - Integrated 1-tap WhatsApp button to forward payment screenshots and order summaries.
- **Responsive Classic Theme:** Styled with a custom color palette consisting of Noir Deep (`#111215`), Forest/Sage Green (`#1E5A38`, `#2E9B62`), and Sweet Blush Pink (`#E65C83`, `#F47298`).

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (Modern Flexbox, CSS Grid, Custom CSS Variables)
- **Scripting:** Vanilla JavaScript (ES6+)
- **Storage:** Web Storage API (`localStorage`) for custom item persistence
- **APIs Used:** 
  - [QR Server API](https://goqr.me/api/) for real-time UPI QR code generation
  - WhatsApp Click-to-Chat API for direct order dispatch

---

## 📂 Project Structure

```text
cake-touch/
├── index.html       # Complete single-file application (HTML, CSS, JS)
└── README.md        # Project documentation
