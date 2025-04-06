# 🛍️ E-Commerce Modern Mart – Interview Fashion Store
- A modern, responsive e-commerce website built to help users find the perfect outfits and accessories for interviews. Features include user authentication, admin panel, shopping cart, wishlist, reviews, discount system, and JSON-based data storage. Built using HTML, CSS, and JavaScript.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This is an e-commerce website designed to help users purchase interview outfits and accessories. It includes features like user authentication, an admin panel, shopping cart functionality, wishlist support, and product reviews.

## Features
- **User Authentication** (Login, Register, Logout)
- **Admin Panel** (Manage Products & Users)
- **Shopping Cart** (Add, Remove, Update items)
- **Database Integration** (JSON-based storage)
- **Discounts & Coupons** (Apply discounts)
- **Wishlist** (Save favorite items)
- **Product Reviews & Ratings**
- **User Profiles** (View & Edit user details)

## Installation
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- A local server (e.g., [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VSCode)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/lr19-boy/E-Commerce-Modern-Mart-Interview-Fashion-Store.git
   ```
2. Navigate to the project directory:
   ```sh
   cd E-Commerce-Modern-Mart-Interview-Fashion-Store
   ```
3. Start the local server:
   ```sh
   npm start
   ```

## Usage
1. Open your browser and visit `http://127.0.0.1:3030/`
2. Register/Login to access features.
3. Browse products, add them to the cart, and proceed to checkout.
4. Admins can manage users and products through the admin panel.

## Project Structure
```
|-- index.html
|-- styles/
|   |-- style.css
|-- scripts/
|   |-- main.js
|-- data/
|   |-- products.json
|   |-- users.json
|-- images/
|-- README.md
```

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** JSON for data storage (future integration with a database possible)
- **Server:** Node.js (for running a local development server)

## Deployment
To deploy the project:
1. Upload all project files to a hosting service (e.g., Netlify, Vercel, or GitHub Pages for static sites).
2. If using a backend, configure the server and database accordingly.

## Contributing
Feel free to contribute by submitting issues or pull requests.

## License
This project is open-source and available under the [Apache](LICENSE).

## API Endpoints
For API-based interactions, the following endpoints are available:
- `GET /products` - Fetch all products
- `POST /cart` - Add a product to the cart
- `GET /cart` - Retrieve cart items
- `POST /login` - User authentication
- `POST /register` - Create a new account
- `GET /admin/products` - Manage products (Admin only)

## Contact
For any issues, contact us at [lazarusrolando399@gmail.com](mailto:lazarusrolando399@gmail.com).

