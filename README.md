# Sole Purpose: Footwear E-commerce Platform 👟

**Step Smart. Step Sustainably.**

🌐 **Live Demo:** [ssolepurposee.infinityfreeapp.com](https://ssolepurposee.infinityfreeapp.com/)

Sole Purpose is a community-focused e-commerce platform that promotes sustainable footwear and supports local Indian artisans. Beyond standard e-commerce features, it includes tools for foot health and inclusive sizing.

## 👥 Team

This was a Semester IV team project.

| Member | Contribution |
|---|---|
| [Ketan Suresh Shelke](https://github.com/ketanshelke97) | Backend development (PHP), MySQL database design and setup, user authentication (login, signup, sessions, password hashing), shop filtering logic, foot quiz recommendation logic, cart operations and checkout flow, and deployment to InfinityFree |
| [Nicole Lourdes Pereira](https://github.com/Nico2184-star) | UI design, category page, smart size converter |
| [Sharon Louis](https://github.com/SharonLouis) | Foot quiz UI, UI design, AJAX wishlist operations, security fixes (SQL injection prevention in login and signup using prepared statements) |

**Repositories:**
- This repository: https://github.com/SharonLouis/sole_purposeSemIV
- Original repository: https://github.com/ketanshelke97/sole_purposeSemIV

## ✨ Key Features

- 👟 **Dynamic Shop:** filtering by gender, category, budget, orthopedic comfort type and brand
- 🦶 **Foot Quiz Engine:** recommends footwear based on foot health needs
- 📏 **Smart Size Converter:** converts foot measurements (cm) to US/UK/EU sizes
- 🛒 **AJAX Cart and Wishlist:** real-time updates without page reloads
- 🔐 **User Authentication:** login, registration and session management with hashed passwords
- 🎨 **Responsive UI:** dark-themed design built with vanilla HTML, CSS and JS

## 🔒 Security Improvements

Added by [Sharon Louis](https://github.com/SharonLouis) in this repository:

- Replaced raw SQL queries in `auth/signup.php` and `auth/login.php` with prepared statements to prevent SQL injection

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Environment:** XAMPP (Windows)

## 📂 Project Structure

```
sole_purposeSemIV/
├── api/        # AJAX endpoints (cart/wishlist)
├── auth/       # Login, signup, profile
├── pages/      # Cart, checkout, quiz, health guides
├── partials/   # Reusable components and DB connection
├── products/   # Category views
├── index.php   # Landing page
├── shop.php    # Storefront
├── style.css   # Design system
└── script.js   # Frontend logic
```

## 🚀 Local Setup

1. Install XAMPP and place this folder in `C:\xampp\htdocs\` (keep the folder name `sole_purposeSemIV`).
2. Start **Apache** and **MySQL** in the XAMPP Control Panel.
3. Open `http://localhost/phpmyadmin/`, create a database, and import `sole_purpose_upgrade.sql`.
4. Open `partials/_dbconnect.php` and make sure the database name and credentials match your setup.
5. Visit `http://localhost/sole_purposeSemIV/`.

## 📝 Acknowledgements

Developed as an academic project for Semester IV.
