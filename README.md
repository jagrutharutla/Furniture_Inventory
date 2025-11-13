

***

# Furniture Inventory Management System

## Purpose
This project is a web-based inventory management system designed to help users efficiently manage furniture stock. It provides a user-friendly interface to view all inventory items, add new furniture products, update stock quantities, and remove products as needed.

## Tech Stack
- **Backend Framework:** Node.js with Express - provides a robust server and routing capabilities.
- **Database:** MongoDB - stores all furniture inventory data.
- **View Engine:** EJS (Embedded JavaScript) - renders dynamic HTML pages.
- **Middleware:** body-parser - processes incoming request bodies for POST operations.
- **Static Assets:** Served via Express static middleware.

## Features
- View all furniture inventory items on the homepage.
- Add new furniture products through a dedicated form.
- Update the stock quantities of existing furniture items.
- Remove furniture products from the inventory.
- Dynamic and responsive UI rendered with EJS templates.

## Installation and Running
1. Clone the repository.
2. Ensure MongoDB is installed and running locally (`mongodb://localhost:27017`).
3. Install dependencies with:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   node server.js
   ```
5. Access the app at `http://localhost:5000`.

## Project Structure
- `server.js`: Main server file handling routes and database operations.
- `views/`: Contains EJS templates for different views (homepage, add, update, remove).
- `public/`: Static assets like CSS, JS, images.
- `package.json`: Project dependencies.

***
