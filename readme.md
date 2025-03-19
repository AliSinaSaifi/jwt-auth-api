# JWT Authentication API

This project is a simple authentication API built with Node.js and Express.js, implementing JWT (JSON Web Token) authentication. The API includes:

User Login: Generates a JWT token upon successful authentication.
Protected Dashboard Route: Requires a valid JWT token to access.
Error Handling: Custom error handlers for authentication and validation errors.

## Technologies Used

Node.js (JavaScript runtime)
Express.js (Web framework)
jsonwebtoken (JWT) (Authentication)
dotenv (Environment variables)

## Project Structure
```
jwt-auth-api/
│── controllers/
│   └── main.js             # Contains login and dashboard logic
│── errors/
│   ├── bad-request.js       # Bad request error handler
│   ├── custom-error.js      # Custom API error handler
│   ├── index.js             # Centralized error exports
│   ├── unauthenticated.js   # Unauthenticated error handler
│── middleware/
│   ├── auth.js              # JWT authentication middleware
│   ├── error-handler.js     # General error handler
│   ├── not-found.js         # 404 not found middleware
│── public/                 # Static files (HTML, CSS, JS)
│── routes/
│   └── main.js              # Defines API routes
│── .env                     # Environment variables
│── .gitignore               # Files to be ignored by Git
│── app.js                   # Main entry point
│── package.json             # Dependencies and scripts
```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/AliSinaSaifi/jwt-auth-api.git
    ```
2. Navigate to the project directory:
    ```bash
    cd your-repo
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Create a .env file and define the following:
    ```bash
    PORT=3000
    JWT_SECRET=your_secret_key
    ```
## Usage

Provide instructions on how to use your project. For example:
```bash
npm start
```

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add feature-name"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request.

## Contact

For questions or feedback, please contact alisinsaifi789@gmail.com
