# 🌴 ESCAPE - Travel Booking System

> A complete web-based travel booking platform with admin dashboard, contact management, and seamless booking experience.

---

## 📌 Project Overview

**ESCAPE** is a fully functional travel booking website that allows users to browse and book travel packages without needing to log in. The system includes a powerful admin panel where administrators can manage bookings, users, packages, and contact messages.

This project was built as a comprehensive solution for travel agencies to digitize their booking process.

---

## 🚀 Features

### 👤 User Side
- Browse all available travel packages
- View package details (price, duration, hotels, amenities)
- Book trips without login (guest booking allowed)
- Live price calculation based on number of travelers
- Unique booking ID generated for each booking
- Booking confirmation modal with all details
- View all bookings in dashboard
- Contact form to reach out to admin

### 👑 Admin Side
- Secret admin access (triple-click on ESCAPE logo)
- View all bookings from all users
- Confirm or cancel pending bookings
- Delete bookings if needed
- View all registered users
- Activate or deactivate user accounts
- Add new travel packages
- Delete existing packages
- View all contact form messages
- Mark messages as read

---

## 🛠️ Technologies Used

| Area | Technology |
|------|------------|
| Frontend | HTML5, CSS3, JavaScript, Bootstrap 5, Font Awesome |
| Backend | Python, Flask Framework |
| Database | SQLite with SQLAlchemy ORM |
| Authentication | JWT (JSON Web Tokens) |
| Security | Bcrypt for password hashing |

---

## 📂 Project Structure
hotels-and-rooms/
│
├── app.py # Main backend application
├── travel_booking.db # SQLite database (auto-created)
│
├── index.html # Homepage
├── login.html # Login page
├── signup.html # Registration page
├── unified-dashboard.html # Main dashboard (User + Admin)
├── packages.html # Browse packages
├── booking.html # Booking form
├── contact.html # Contact us page
├── about_us.html # About page
├── destinations.html # Destinations page
│
├── images/ # All images used in the project
│ ├── image1.jpg
│ ├── goa.jpg
│ ├── ooty.jpg
│ ├── coorg.jpg
│ ├── manali.jpg
│ ├── mysore.jpg
│ └── kerala.jpg
│
└── README.md # This file