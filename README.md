# Task Management System (Laravel)

## Project Overview
This project is a Task Management System built using Laravel where users can register, login, and manage their own tasks.

## Tech Stack
- PHP 8.x
- Laravel 9+
- MySQL
- Blade
- GitHub

## Features
- User Authentication (Register, Login, Logout)
- Auth-protected Dashboard
- Task CRUD Operations
- Authorization (Users can manage only their own tasks)
- Validation and Clean MVC Architecture

## Setup Steps
1. composer install
2. cp .env.example .env
3. Configure database
4. php artisan key:generate
5. php artisan migrate
6. php artisan serve
