# 🎬 CineBook — Movie Ticket Booking System

> A responsive movie ticket booking web application built with HTML, CSS and JavaScript.

## 🌟 Project Overview

CineBook is a front-end movie theater booking system designed to demonstrate practical web development, form validation, seat management, booking flow, billing calculations and browser-based data persistence.

## ✨ Features

- 🎬 Movie listing and show timings
- 💺 Silver, Gold and Diamond seat selection
- 🚫 Booked-seat handling
- 🍿 Snacks and drinks selection
- 👤 Customer registration with input validation
- 💳 Cash, UPI and Card payment selection
- 🧾 Ticket + snack billing
- 🎁 Discount calculation
- 🧮 GST calculation
- 🎟️ Automatic booking ID generation
- 🖨️ Printable movie ticket
- 📋 My Bookings section
- ❌ Booking cancellation
- 🔐 Admin login and dashboard
- 🎬 Admin movie management
- 🕐 Admin show management
- 💾 LocalStorage-based browser data persistence
- 📱 Responsive layout for desktop and mobile
- 🛡️ Basic client-side input sanitization and validation

## 🛠️ Technologies

| Technology | Usage |
|---|---|
| HTML5 | Application structure |
| CSS3 | Responsive UI and styling |
| JavaScript | Application logic and interactions |
| LocalStorage | Browser-side data persistence |
| Git | Version control |
| GitHub | Source code hosting |
| GitHub Pages | Static deployment |

## 📂 Project Structure

```text
repo07/
├── index.html       # Main CineBook application
├── README.md        # Project documentation
├── .nojekyll        # GitHub Pages helper
└── LICENSE          # Project license
```

## 🚀 How to Run Locally

1. Clone the repository.
2. Open `index.html` in a modern browser.
3. Use the navigation to explore Movies, Shows, Seats, Snacks, Payment and My Bookings.

No backend server is required for the current demo version because browser LocalStorage is used for persistence.

## 🌐 Live Demo

GitHub Pages is configured for this repository. If the deployment is still processing, the demo may temporarily show a 404 page.

**Expected URL:** `https://anuragchaurasiya.github.io/repo07/`

## 🔐 Demo Admin

For the current demo implementation:

```text
Username: admin
Password: admin123
```

> ⚠️ This is client-side demo authentication and is not suitable for production. A production release should use server-side authentication, hashed passwords, authorization and a database.

## 💰 Billing Logic

The application calculates:

```text
Ticket + Snacks
        ↓
Discount
        ↓
GST 18%
        ↓
Final Amount
```

The current implementation applies a 10% discount when the subtotal reaches the configured threshold and then calculates 18% GST on the discounted amount.

## 🔮 Future Improvements

- Java Spring Boot REST API
- MySQL database
- Real user authentication and authorization
- Secure server-side admin authentication
- Real payment gateway integration
- REST API for movies, shows, seats and bookings
- Persistent booking database
- Email/SMS ticket confirmation
- QR-code ticket generation
- Automated tests and CI/CD

## 🎯 Learning Outcomes

This project demonstrates practical understanding of:

- DOM manipulation
- JavaScript functions and events
- Form validation
- Arrays and objects
- LocalStorage
- CRUD-style UI operations
- Responsive CSS
- Basic security practices
- Git and GitHub workflow

## 👨‍💻 Developer

**Anurag Chaurasiya**

GitHub: https://github.com/anuragchaurasiya

---

⭐ If you find this project useful, consider giving the repository a star.
