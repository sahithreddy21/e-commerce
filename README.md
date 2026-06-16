# 🛒 BazaarX — Native E-Commerce & Management Platform

BazaarX is a high-performance, single-file e-commerce web application engineered entirely with **semantic HTML5**, **modern CSS3 (Custom Properties & Flexbox/Grid)**, and **Vanilla JavaScript (ES6+)**. It features an isolated, client-side data store layer that simulates a live database architecture. The platform delivers a dual-role user experience, shifting seamlessly between a fully functional customer shopping front-end and a secure, analytical Administrator Dashboard.

🔗 **Live Preview:** [https://taskmaster-lyart-one.vercel.app](https://taskmaster-lyart-one.vercel.app)

---

## ✨ Key System Features

### 👤 Customer Experience
* **Dynamic Catalog & Search Engine:** Multi-category navigation matching product categories (Electronics, Fashion, Food & Grocery, Ayurveda, etc.) coupled with an instant search filter query.
* **Smart Catalog Sorting:** Advanced sorting mechanics enabling users to filter products by lowest/highest price, community rating metrics, or the deepest percentage discounts.
* **Persistent State Cart & Wishlist:** Active micro-data tracking for items added to the cart or wishlist. It automatically calculates quantities, custom regional taxes (**18% GST**), and tags items with low stock warning banners (**fewer than 10 units left**).
* **Multi-Stage Checkout Workflow:** A responsive delivery address registry and native billing options setup simulating popular Indian options (UPI, Credit/Debit Card, Net Banking, and COD) with a complete transactional landing modal.

### ⚙️ Executive Admin Portal (Protected Route)
* **Live Operational Analytics:** Centralized calculation system compiling gross revenue metrics, total real-time transactional volumes, registered store accounts, and live active skus.
* **Category Revenue Matrix:** Data-parsing aggregations mapping overall store revenue performance down to individual categories.
* **Granular SKU Management:** A built-in Create, Read, Update, Delete (`CRUD`) product dashboard to instantly add new products, edit stock, assign descriptions/emojis, or remove active entries.
* **Order & Access Control:** Real-time lookup arrays allowing admins to change specific customer order statuses along delivery pipelines (*Processing, Packed, Shipped, Out for Delivery, Delivered*) and elevate or revoke administrative access across user accounts.

---

## 🛠️ Technical Built-With Stack

* **Structure Layer:** Semantic HTML5 (`Document Object Model` node API management)
* **Styling Layer:** Native CSS3 (Custom property theme tokens, full responsive layouts via Flexbox and Grid, customized standard scrollbars, and keyframe animations).
* **Logical Layer:** Vanilla ECMAScript (JavaScript ES6+) utilizing native array processing methods (`.map()`, `.filter()`, `.reduce()`), deep template literals, conditional page-routing views, and isolated functional mutations.

---

## ⚡ Quick Start Instructions

Because BazaarX is built entirely on web standards with zero package dependencies or build/bundling compilation steps, local initialization is instantaneous.

### 1. Setup the Code Locally
```bash
# Clone the repository
git clone [https://github.com/sahithready21/taskmaster.git](https://github.com/sahithready21/taskmaster.git)

# Move into the folder root
cd taskmaster
