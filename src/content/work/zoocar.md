---
title: ZooCar
publishDate: 2019-12-01 00:00:00
img: /assets/zoocar.svg
img_alt: A modern car parked in front of a zoo entrance, with vibrant animal illustrations.
description: |
  Developed a comprehensive animal-friendly carpooling application, facilitating affordable and accessible pet transportation.
tags:
  - Dev
  - FullStack
  - Backend
---

## Project Overview

Nowadays, traveling as we wish is not always as easy as one might think. Price, accessibility, schedules, and travel durations are crucial criteria when deciding on the ideal trip. Pet owners often face expensive alternatives. ZooCar, an animal-friendly carpooling site, was born out of this need. The principle is simple: arrange carpooling for your pet at affordable prices, reasonable travel times, near-total availability, and great accessibility. Our team based the website on BlaBlaCar's fundamentals to create an easy-to-use and pleasant-to-navigate platform. In no time, you can book the trip of your choice for any of your pets, with the option to travel together. So, what are you waiting for? Try ZooCar!

## Technical Choices

In developing ZooCar, we selected the best-suited tools and technologies based on our experience and the specific project requirements. Here are the main technical choices we made:

### Frontend

- **HTML**: Used to define the structure and elements of each page.
- **TailwindCSS**: Chosen for its simplicity in layout design using CSS shorthand, providing a uniform style across the site.
- **JavaScript**: Utilized for adding dynamism and user interactions.

### Backend

- **WampServer**: A local server to interface between our application and the database.
- **PHP**: Server-side language used to interact with the database and efficiently process data.
- **PHPMyAdmin**: Provided by WampServer to link our database to the site locally.
- **MySQL**: Used for database creation and management.
- **Git**: For version control of the source code.
- **University Forge**: Used as the remote repository for our source code.

### Tools for Modeling and Collaboration

- **Draw.io, Eraser.io, Visual Paradigm Online**: For UML modeling of requirements and functionalities, and for database conceptualization.
- **Discord**: Online communication platform for seamless team collaboration.

### Design and Documentation

- **Figma**: Used for precise UI mockups.
- **Notion**: For sharing documents and project management tools like KANBAN boards.

### Deployment

- **Raspberry Pi with Apache server**: Hosting our application using Docker.

## Features

### Registration

- **Validation**: Each input field is checked to ensure proper completion. For example, the date of birth is verified to ensure users are over 18.
- **Security**: Passwords are hashed before storage to enhance data privacy and security.

### Login

- **Authentication**: Users provide their email and password. The password is hashed and compared to the stored hash for authentication.

### Trip Search

- **Criteria**: Users can search trips by departure and arrival locations and desired date.
- **Advanced Filters**: Users can sort results by criteria such as shortest or cheapest trip.

### Trip Creation

- **Form**: Users fill out a detailed form with trip details. Data is validated before saving.

### Profile Management

- **User Profile**: Users can view and edit their personal information and view ratings from other users.
- **Pet Profile**: Users can create profiles for their pets with details like name, species, size, and weight.

### Booking

- **Reservation**: After selecting a trip, users fill out a reservation form, choosing their pet profile. Data is validated for capacity and trip requirements.

### Reservation Validation

- **Driver Confirmation**: Drivers validate reservations from their booking page. Statuses are managed automatically by database triggers.

### Instant Messaging

- **Communication**: Users can communicate via integrated messaging. Contacts are added upon booking, facilitating communication before, during, and after the trip.

## Conclusion

These technical choices were made considering factors such as ease of development, performance, team collaboration, and long-term maintenance. ZooCar provides an innovative solution for pet owners, making travel easier and more affordable.
