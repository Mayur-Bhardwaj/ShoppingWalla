# E-commerce Website

A full-featured E-commerce web application built using **HTML, CSS, JavaScript, ReactJS, ReduxJS, NodeJS, ExpressJS, and MongoDB**.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This E-commerce website allows users to browse, search, and purchase products online. It provides a modern user experience with secure user authentication and order management.

## Features

- User Authentication (Sign up/in, JWT, sessions)
- Product Listing, Search, and Filter
- Product Details Page
- Shopping Cart & Checkout Process
- Order Placement & History
- Admin Panel for Product Management
- Responsive UI
- RESTful API backend integration

## Tech Stack

**Frontend:**
- HTML, CSS, JavaScript
- ReactJS (UI Library)
- ReduxJS (State Management)

**Backend:**
- NodeJS
- ExpressJS

**Database:**
- MongoDB

## Getting Started

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/ecommerce-website.git
    cd ecommerce-website
    ```

2. **Install dependencies for frontend and backend:**
    ```sh
    cd client
    npm install
    cd ../server
    npm install
    ```

3. **Set up environment variables:**

   Create a `.env` file in the `server/` directory. Example:
    ```
    MONGO_URI=<Your MongoDB URI>
    JWT_SECRET=<Your Secret>
    ```

4. **Run the application:**
    - Start backend server:
        ```sh
        cd server
        npm start
        ```
    - Start frontend:
        ```sh
        cd client
        npm start
        ```

5. **Visit the app**
    - Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
ecommerce-website/
├── client/                # ReactJS frontend
│   ├── src/
│   ├── public/
├── server/                # NodeJS backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
├── README.md
├── package.json
```

## Usage

- Browse or search products.
- Add items to cart.
- Signup/Login to place orders.
- View order history.
- Admin users can manage products via the dashboard.

## Contributing

Contributions, issues and feature requests are welcome!

1. Fork the repository
2. Submit a Pull Request

## License

This project is licensed under the MIT License.
