# E-Commerce Web Application - Frontend (MVP)

This repository contains the **frontend** of the E-commerce web application built with **React (MERN stack)**.  
The frontend provides **customer and merchant views**, with a focus on clean UI/UX and responsive design.

---

## 🚀 MVP Scope

### Core Features
- Product Listing Page (browse all products)
- Product Search & Filters (category, price, rating, etc.)
- Shopping Cart (add/remove/update items)
- Checkout Flow (with Stripe integration for payments)
- Coupon Codes & Discounts
- User Authentication (JWT-based login/signup)
- Customer Dashboard (orders, profile management)
- Merchant Dashboard (basic product management)
- Analytics (basic event logging for admin insights)

---

## 🛠️ Tech Stack
- **React (JSX only, no TS)**
- **React Router** (navigation)
- **CSS Modules / Material UI** (styling)
- **Axios / Fetch API** (API integration with backend)
- **Stripe.js** (payment integration)

---

## 📁 Project Structure (Planned)
```
ecom-frontend-1/
│── public/ # Static assets
│── src/
│ ├── components/ # Reusable components
│ ├── pages/ # Page-level components (Home, Cart, Checkout, Dashboard)
│ ├── hooks/ # Custom hooks
│ ├── context/ # State management (Auth, Cart, etc.)
│ ├── services/ # API calls
│ ├── styles/ # CSS Modules
│ └── App.jsx
│── package.json
│── README.md
```

---

## 📌 Roadmap (Frontend)
- [ ] Set up React project with Vite/CRA
- [ ] Implement routing & layout
- [ ] Build product listing & details page
- [ ] Add cart & checkout flow
- [ ] Integrate Stripe checkout
- [ ] Implement auth (JWT with backend)
- [ ] Build customer/merchant dashboards
- [ ] Add basic analytics events

---

## 🤝 Contribution Guidelines
1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a pull request
