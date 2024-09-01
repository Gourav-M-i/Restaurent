# Restaurant Project

This is a full-stack restaurant web application built with a React frontend and a Node.js/Express backend. The application allows users to browse the menu, make reservations, and order food online.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Running the Application](#running-the-application)

## Features

- **User Authentication:** Sign up, log in, and log out only for restaurents.No login for user, item is stored in localstorage
- **Menu Management:** Browse through an interactive menu with categories and dishes.
- **Order Management:** Place, view, and manage orders.
- **Reservation System:** Book a table at the restaurant.
- **Admin Panel:** Manage menu items, orders, and reservations.

## Tech Stack

### Frontend

- **React.js**: JavaScript library for building user interfaces
- **React Router**: For navigation
- **Axios**: Promise-based HTTP client for the browser and Node.js
- **CSS/SASS**: Styling
- **Paymeny Gateway**: Stripe
- **Image upload**: Cloudinary

### Backend

- **Node.js**: JavaScript runtime environment
- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js
- **MongoDB**: NoSQL database for data storage
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB and Node.js
- **JWT**: JSON Web Tokens for user authentication

## Installation

- **Backend**
  - cd ./backend
  - npm install
  - npm run dev
  - NOTE: Mongodb is connected locally(must be installed in the syatem)
- **Frontend**
  - cd ./frontend
  - npm install
  - npm run dev
  - NOTE: First create Admin account then add some dishes, then logout and add to cart and place order

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (locally or use a MongoDB Atlas cluster)

### Backend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/restaurant-project.git
   cd restaurant-project
   ```
2. **Change directory:**
   ```bash
   cd ./backend
   ```
3. **Install dependency:**
   ```bash
   npm install --force
   ```
4. **Run the backend:(Make sure mongodb is installed locallly)**
   ```bash
   npm run dev
   ```

### Frontend Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/restaurant-project.git
   cd restaurant-project
   ```
2. **Change directory:**
   ```bash
   cd ./frontend
   ```
3. **Install dependency:**
   ```bash
   npm install
   ```
4. **Run the backend:(Make sure mongodb is installed locallly)**

   ```bash
   npm run dev
   ```

### Screenshots

![Getting Started](screenshots/home.jpg)
![Getting Started](screenshots/dish.jpg)
![Getting Started](screenshots/dishes.jpg)
![Getting Started](screenshots/add_dish.jpg)
