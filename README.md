# 🎓 Laravel E-Learning Platform

A web-based learning management system built with Laravel. It connects teachers and students in an interactive environment where lessons, exams, and feedback are seamlessly managed.

## 📚 Features

- 🧑‍🏫 Teacher Dashboard  
  - Upload lesson materials (PDFs, etc.)  
  - Create quizzes and exams  
  - Evaluate students and assign grades  

- 🎓 Student Dashboard  
  - Access and download lesson content  
  - Take online quizzes and submit answers  
  - Comment and give feedback on lessons  

- 🛡️ Authentication & Roles  
  - Secure login system  
  - Role-based access for teachers and students  

- 📬 Notifications  
  - Email alerts for new lessons, grades, and deadlines

## 🛠️ Tech Stack

- Laravel 11  
- MySQL  
- Blade + Livewire  
- Spatie Roles & Permissions  
- Laravel Breeze / Sanctum (for auth)  
- Bootstrap & jQuery  
- Ajax & Real-time notifications

## 🚀 Setup Instructions

```bash
git clone https://github.com/yourusername/elearning-platform.git
cd elearning-platform
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
