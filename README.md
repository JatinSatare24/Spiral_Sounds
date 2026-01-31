# Spiral Sounds 🎸

**Spiral Sounds** is a full-stack e-commerce platform for an indie rock vinyl store. Developed as part of the Scrimba Express.js curriculum, 
this project focuses on building a professional-grade REST API and server-side logic to manage inventory, user authentication, and real-time logistics tracking.

## 🚀 Key Features

* **Vinyl Inventory Management**: A modular system for browsing and managing a diverse collection of indie rock records using Express routing.
* **User Authentication & Security**: Implements secure, protected routes to ensure that sensitive operations—like order processing—are restricted to authorized users.
* **CORS & Web Security**: Configured with Cross-Origin Resource Sharing (CORS) policies to manage secure data exchange between the backend API and diverse frontend clients.

## 🛠️ Tech Stack

* **Runtime**: Node.js
* **Framework**: Express.js (Modular routing with `express.Router`)
* **Security**: Authentication middleware and CORS configuration
* **Architecture**: RESTful API design with clean Separation of Concerns (SoC)

## 📂 Project Structure

```text
├── routes/             # Modular Express routers for auth, products, and orders
├── middleware/         # Custom authentication and error-handling logic
├── data/               # Persistent store for vinyl inventory and user records
├── public/             # Frontend assets for the vinyl store dashboard
├── utils/              # Helper workers for task queues and notification streams
└── server.js           # Main entry point and Express application configuration
