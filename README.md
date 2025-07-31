# 🚀 QuickHire – Laravel Job Portal

> A Laravel-powered job portal connecting jobseekers with employers. Built with PHP and MySQL for efficient job matching and user management.

![Tech](https://img.shields.io/badge/Built%20With-Laravel%2C%20MySQL-red)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📂 Features

- 🧑‍💼 **Employer Registration & Dashboard**: Post jobs, view applications, and manage listings.
- 🙋‍♂️ **Jobseeker Registration & Dashboard**: Apply for jobs, upload resumes, and track applications.
- 🔍 **Job Search Functionality**: Filter by category, location, and job type.
- 💬 **Notification System**: Alerts for new job posts and application statuses.
- 🔐 **Authentication & Authorization**: Role-based access control using Laravel Breeze or Jetstream.
- 📄 **Resume Upload & Profile Management**.

---

## 🔧 Technologies Used

- PHP 8+
- Laravel 10+
- MySQL / MariaDB
- Blade Templates
- Tailwind CSS / Bootstrap (optional UI framework)
- Git & GitHub
- GitHub Actions (for CI/CD)
- Docker (for development & production containerization)

---

## ⚙️ Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/quickhire.git

# Navigate into the project directory
cd quickhire

# Install dependencies
composer install

# Create .env file
cp .env.example .env

# Generate application key
php artisan key:generate

# Set up database and run migrations
php artisan migrate

# Serve the application
php artisan serve
