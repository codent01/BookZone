<h1 align="center">📚 BookZone</h1>
<p align="center">
  <strong>Full-Stack E-Commerce Bookstore</strong><br/>
  Browse, wishlist, cart, and purchase books — built with the MERN stack and deployed on AWS S3.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS_S3-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>

<p align="center">
  <a href="http://bookzone-store-web.s3-website.eu-north-1.amazonaws.com/">🌐 Live Demo</a>
</p>

---

## Features

### 🔐 User Authentication
Secure sign-up, login, and logout with session management.

### 📖 Product Catalog
Browse a curated collection of books with a proper landing page, categories, and new arrivals section.

### 🔍 Sort & Filter
- Sort by price (low to high / high to low)
- Filter by price range, genre, rating
- Filter by stock availability and fast delivery
- Clear all filters with one click

### ❤️ Wishlist
Save books for later. Move items between wishlist and cart seamlessly.

### 🛒 Cart Management
Add to cart, change quantities, remove items, move to wishlist, and apply coupon codes.

### 💳 Razorpay Payments
Integrated Razorpay payment gateway for secure checkout with order summary.

### 🔎 Search
Find books by title or author name with instant search.

### 📄 Pagination
Smooth browsing with paginated product listings.

### 🔔 Custom Toast Notifications
4 toast types — Success, Error, Warning, and Information — for clear user feedback.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | React, JavaScript, CSS3, HTML5 |
| **Backend** | Node.js, Express.js (deployed on Vercel) |
| **Database** | MongoDB |
| **Payments** | Razorpay |
| **Hosting** | AWS S3 (Static Hosting) |

---

## Project Structure

```
BookZone/
├── public/                # Static assets & index.html
├── src/
│   ├── components/        # React UI components
│   ├── pages/             # Page-level components
│   ├── context/           # State management
│   └── App.js             # Root component
├── build/                 # Production build
├── package.json
└── README.md
```

---

## Getting Started

### Prerequisites
- Node.js 16+
- npm

### Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/codent01/BookZone.git
   cd BookZone
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

4. **Build for production**
   ```bash
   npm run build
   ```

---

## Roadmap

- [x] User authentication
- [x] Product catalog with categories
- [x] Sort, filter, and search
- [x] Wishlist & cart management
- [x] Coupon system
- [x] Razorpay payment integration
- [x] Order summary & orders page
- [x] AWS S3 deployment
- [ ] Admin dashboard for inventory
- [ ] Order tracking and history
- [ ] Book reviews and ratings

---

<p align="center">
  <i>Your next favorite book is just a click away.</i><br/>
  <strong>Browse. Wishlist. Read.</strong>
</p>
