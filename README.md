# 🫘 Ndengu Project - Burial & Support Web App

Ndengu Project is a community-based web application designed to help members contribute towards funeral support, manage meeting logistics, and coordinate burial events in a transparent and efficient way.

---

## 📌 Key Features

### 👥 User Authentication
- ✅ Registration with email verification using SMTP
- 🔐 Secure login
- 🔁 Password reset via token-based email verification

### 🛠 Admin Dashboard
Accessible only to admins:
- 📧 Email notifications to users about upcoming meetings
- 👤 Manage user profiles (update/remove users)
- 🗓 Update `meetings` and `burials` tables
- 👥 View all registered users
- 💰 View contribution logs with:
  - Contributor name
  - Amount contributed
  - Total contributions displayed

### 📃 Event Page
- Displays all scheduled **meetings**.
- Lists **deceased individuals** with details for contributions and burial support.

### 🏠 Landing Page
- Welcomes users with an overview of the app's purpose
- Includes navigation links, "About Us", and contact/footer section

### 💳 Payment System *(In Progress)*
- Working on allowing users to make contributions directly through the platform.

---

## 📋 App Structure Overview

### 1. 🔐 **Registration**
- Fee → 300 KES
- Fields: First Name, Last Name, Mobile Number, Password

### 2. 🔑 **Login**
- Fields: Phone, Password

### 3. 🎯 **Purpose**
- Burial support and coordination

### 4. 📆 **Event Management**
- Individual contributions: 100 KES
- Seats (50) → 500 KES
- Contributions to be made **before 1PM a day before burial**
- Failure to contribute on time results in doubling of the amount

### 5. 🪦 **Burial Contributions**
- 90,000 KES must go to the deceased’s family, the rest to the office
- All seats provided to the deceased family a day before the burial
- Borrowed and broken seats are managed accordingly

---

## 📱 Pages in the App

- 📝 **Registration Page**
- 🔐 **Login Page**
- 🏠 **Landing Page**
- 🗂 **Admin Dashboard**
- 🗓 **Event Page**
- 💸 **Payment Page** *(Coming Soon)*

---

## 🔧 Technologies Used

- **PHP**
- **MySQL**
- **SMTP (for email and password reset)**
- **HTML, CSS, JS** for frontend
- **Bootstrap** (depending on your preference)

---

## 🚀 Getting Started

### Prerequisites
- PHP 8.x
- MySQL 5.7+
- Composer
- SMTP credentials (e.g., Gmail SMTP)

### Installation

```bash
git clone https://github.com/yourusername/ndengu-project.git
cd ndengu-project
