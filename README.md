# Little Lemon Project

## Overview

The Little Lemon project is a web application built using Django that serves as a restaurant management system. It provides features for users to view the restaurant's menu, make reservations, and check existing bookings. The application utilizes Django's powerful MVC (Model-View-Controller) framework to handle web requests and manage data seamlessly.

## Features

- **Home Page**: A welcoming landing page for users to navigate through the application.
- **About Page**: Information about the restaurant and its services.
- **Menu Page**: A dynamically generated menu displaying various food items.
- **Reservations**: Users can view available reservation slots and make bookings.
- **Bookings Management**: Display and manage existing reservations.

## Technologies Used

- **Django**: A high-level Python web framework that enables rapid development of secure and maintainable web applications.
- **HTML/CSS**: For front-end design and layout.
- **JavaScript**: For enhancing user interactivity.
- **SQLite**: As the database backend for storing menu items and booking information.

## API Endpoints

The application exposes several API endpoints for handling bookings and menu items. Below are the main functionalities:

| Endpoint               | Method  | Description                                                  |
|-----------------------|---------|--------------------------------------------------------------|
| `/`                   | GET     | Returns the home page of the application.                    |
| `/about/`            | GET     | Displays information about the restaurant.                   |
| `/reservations/`     | GET     | Retrieves all bookings for a specific date and displays them. |
| `/book/`             | GET/POST| Allows users to fill out a booking form and save their reservations. |
| `/menu/`             | GET     | Retrieves all menu items and renders them on the menu page. |
| `/menu/<pk>/`        | GET     | Displays a specific menu item based on its primary key (ID). |
| `/api/bookings/`     | GET/POST| API endpoint to create new bookings and retrieve bookings for a specific date. |

