# 🛍️ Kartly — An E-Commerce Website

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)

> **Shop smarter. Built faster.** — A modern front-end e-commerce web app built with vanilla HTML, CSS, and JavaScript.

---

## 📌 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Pages](#pages)
- [Getting Started](#getting-started)
- [Folder Structure](#folder-structure)
- [API Used](#api-used)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## 📖 About

**Kartly** is a front-end e-commerce web application that fetches real product data from the [DummyJSON API](https://dummyjson.com). Users can browse 190+ products, view product details, search in real-time, and manage their cart — all without a backend, using `localStorage` for cart persistence.

---

## ✨ Features

- 🛒 Browse 190+ real products fetched from API
- 🔍 Live search / filter products by name
- 📄 Product detail page with full description
- ➕ Add to cart from product page
- 🗑️ Remove items from cart
- 💰 Prices displayed in **Indian Rupees (₹)**
- 💾 Cart saved in `localStorage` (persists on refresh)
- 📱 Fully responsive design (Mobile, Tablet, Desktop)

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| **HTML5** | Page structure |
| **CSS3** | Styling & responsive layout |
| **JavaScript (Vanilla)** | Logic, API calls, DOM manipulation |
| **DummyJSON API** | Product data source |
| **localStorage** | Cart persistence |

---

## 📄 Pages

| File | Description |
|------|-------------|
| `index.html` + `app.js` | Home page — product listing with search |
| `product.html` + `product.js` | Product detail page — full info + Add to Cart |
| `cart.html` + `cart.js` | Cart page — view items, remove, see total bill |
| `style.css` | All styles for all pages |

---

## 🚀 Getting Started

No installation or setup needed — this is a pure front-end project!

**1. Clone the repository**
```bash
git clone https://github.com/Akanshashukla6393/Kartly-AnEcommerceWebsite.git
```

**2. Navigate into the folder**
```bash
cd Kartly-AnEcommerceWebsite
```

**3. Open in browser**
```bash
# Simply open index.html in your browser
# Or use Live Server in VS Code (recommended)
```

> 💡 **Tip:** Use the **Live Server** extension in VS Code for the best experience.

---

## 📁 Folder Structure

```
Kartly-AnEcommerceWebsite/
│
├── index.html        # Home page (product listing)
├── product.html      # Product details page
├── cart.html         # Shopping cart page
│
├── app.js            # Fetches & displays all products, search logic
├── product.js        # Fetches single product details, Add to Cart
├── cart.js           # Displays cart items, remove item, total bill
│
├── style.css         # All styles (navbar, cards, cart, responsive)
│
└── README.md
```

---

## 🌐 API Used

**[DummyJSON](https://dummyjson.com)** — Free fake product API

| Endpoint | Usage |
|----------|-------|
| `GET /products?limit=194` | Fetch all products for listing page |
| `GET /products/:id` | Fetch single product for detail page |

> Prices from the API (in USD) are converted to **INR** by multiplying by `85`.

---

## 🤝 Contributing

Contributions are welcome!

```bash
# 1. Fork the repo
# 2. Create a new branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "Add: your feature"

# 4. Push and open a Pull Request
git push origin feature/your-feature-name
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Akansha Shukla**

[![GitHub](https://img.shields.io/badge/GitHub-Akanshashukla6393-black?style=flat&logo=github)](https://github.com/Akanshashukla6393/Kartly-AnEcommerceWebsite)

---

⭐ **If you like Kartly, give it a star on GitHub!** ⭐
