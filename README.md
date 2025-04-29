
---

## 🔹 Laravel – Task Manager API

**📁 `task-manager-api/README.md`**

```markdown
# Task Manager API

A RESTful API built with Laravel for managing user tasks with authentication using Laravel Sanctum.

## Features

- User registration and login (Sanctum)
- Create, update, delete, and list tasks
- Filter tasks by status and due date
- JSON API responses

## Tech Stack

- Laravel 10
- Sanctum
- MySQL

## API Endpoints

| Method | Endpoint            | Description             |
|--------|---------------------|-------------------------|
| POST   | /api/register       | Register a new user     |
| POST   | /api/login          | Login user              |
| GET    | /api/tasks          | List tasks              |
| POST   | /api/tasks          | Create new task         |
| PUT    | /api/tasks/{id}     | Update a task           |
| DELETE | /api/tasks/{id}     | Delete a task           |

## Setup Instructions

```bash
git clone https://github.com/your-username/task-manager-api.git
cd task-manager-api
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
