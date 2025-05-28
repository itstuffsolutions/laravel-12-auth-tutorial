# Laravel 12 Custom Login and Registration Tutorial for Beginners

This repository contains the complete source code for the **Laravel 12 Custom Login and Registration Tutorial** published on my blog. It is tailored for **beginners** who want to learn how to build a secure and fully functional authentication system in Laravel without using Laravel Breeze or Jetstream.

📘 **Read the full tutorial:**  
👉 [Complete Laravel 12 Login & Registration Guide](https://itstuffsolutiotions.io/complete-laravel-12-custom-login-and-registration-tutorial-for-beginners/)

---

## 🔧 Features

- Laravel 12 Setup
- Custom Login and Registration Forms
- Validation and Error Handling
- Password Hashing and Authentication
- User Dashboard with Logout
- Fully Responsive Design using Bootstrap 5

---

## 🚀 Getting Started

Follow the steps below to run this project on your local machine:

### Prerequisites

- PHP >= 8.1
- Composer
- MySQL / SQLite
- Node.js & NPM (optional, for frontend assets)

### Installation

```bash
git clone https://github.com/itstuffsolutions/laravel-12-auth-tutorial.git
cd laravel-12-authentication-tutorial
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
