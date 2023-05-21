# Node/Express JWT Authentication Project

This is a simple project built with Node.js and Express.js to demonstrate JWT (JSON Web Token) authentication.

## Features
- User registration: Allows users to create an account by providing a unique username and password.
- User login: Authenticates users by verifying their credentials and issuing a JWT.

## Installation
1. Clone the repository:
 ```git clone https://github.com/your-username/node-express-jwt-authentication.git```

2. Navigate to the project directory:
```cd final```

3. Install the dependencies:
```npm install```

4. Set up environment variables:
    - Create a new file named .env in the project root.
    - Add the following variables to the .env file:
        ```JWT_SECRET=your-secret-key```
        Replace your-secret-key with your own secret key for JWT token generation.

5. Start the application:
```nodemon app.js```

The server will start running on http://localhost:3000.

