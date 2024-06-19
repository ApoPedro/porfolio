---
title: Shared Shopping List
publishDate: 2023-06-17 00:00:00
img: /assets/shared-shopping-list.jpg
img_alt: A minimalist shopping list interface inspired by Obsidian.
description: |
  A minimalist, user-friendly shared shopping list application inspired by Obsidian, featuring authentication, statistics, and role-based access control.
tags:
  - Dev
  - FullStack
  - Backend
---

## Project Overview

The Shared Shopping List project draws graphical inspiration from Obsidian, focusing on a minimalist design to enhance user experience. The application allows users to manage their shopping lists, share them with others, and view statistics, all within a clean and intuitive interface.

## Features

### Authentication

- **User Registration and Login**: Users can sign up, log in, and log out securely.
- **Role-Based Access Control**: Utilizes ORM roles to differentiate user capabilities, ensuring secure access management.

### Shopping Lists

- **Create, Modify, and Delete Lists**: Users can easily create, edit, and delete shopping lists.
- **Shared Lists**: Users can share and manage shopping lists with others, facilitating collaborative shopping.
- **Statistics**: Users can view detailed statistics about their shopping lists, helping them track their shopping habits.

### Admin CRUD

- **Manage Items and Item Types**: Administrators have the ability to manage the items and item types available in the application.

### Access Control

- **Voter LISTE**: Lists are protected by a Symfony voter to manage access rights, ensuring only authorized users can modify or view certain lists.

## Setup

### Prerequisites

- Ensure you have Symfony and Composer installed on your system.
- PHP 7.4 or higher.

### Installation Steps

1. **Clone the Repository**:

    ```bash
    git clone https://forge.univ-lyon1.fr/p2203838/liste2courses.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd liste2courses
    ```

3. **Install Dependencies**:

    ```bash
    composer install
    ```

4. **Apply Migrations**:

    Apply the migrations to configure your database. This will also create an admin account with the username "Minh" and the password "admin".

    ```bash
    php bin/console doctrine:migrations:migrate
    ```

5. **Install NPM Dependencies**:

    ```bash
    npm install
    ```

6. **Compile CSS Files**:

    Start the watch process to compile the CSS files.

    ```bash
    npm run watch
    ```

7. **Start the Symfony Server**:

    ```bash
    symfony server:start
    ```

## Usage

Access the project at [http://localhost:8000](http://localhost:8000).

- **Admin Account**:
  - **Username**: Minh
  - **Password**: admin

Log in using the admin account or create a new user to start managing your shared shopping lists.

## Conclusion

This project demonstrates a robust implementation of a shared shopping list application with a focus on minimalist design, user experience, and secure access management. The use of Symfony, Composer, and various frontend tools ensures a scalable and maintainable application.
