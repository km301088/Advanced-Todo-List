# Advanced Todo App

## Overview

This is a Laravel-based Todo application that uses AJAX for dynamic interactions. The application allows users to add, edit, mark tasks as complete/incomplete, and delete tasks without refreshing the page. It also includes functionalities to view all tasks and handle duplicates.

## Features

- **Add Tasks**: Add new tasks dynamically without page reload.
- **Edit Tasks**: Edit tasks inline with AJAX support.
- **Complete/Incomplete Tasks**: Mark tasks as completed or incomplete.
- **View All Tasks**: Show both completed and non-completed tasks.
- **Delete Tasks**: Delete tasks with confirmation.
- **No Duplicate Tasks**: Prevent duplicate task entries.
- **Dynamic Tabs**: Use Bootstrap tabs to switch between incomplete and all tasks.

## Technologies Used

- **Laravel**: PHP framework for backend.
- **AJAX**: For asynchronous operations.
- **Bootstrap 5**: For styling and responsive design.
- **jQuery**: For DOM manipulation and AJAX calls.
- **Vercel**: For deployment.

## Installation

### Prerequisites

- PHP 8.0 or higher
- Composer
- Node.js and npm

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/km301088/laravel-ajax-todo-app.git
   cd laravel-ajax-todo-app

2.**Install Dependencies**

    composer install
    npm install


**Set Up Environment**
Copy the .env.example file to .env and update your environment settings:

    cp .env.example .env

    php artisan key:generate

    php artisan migrate

    php artisan migrate
