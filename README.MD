# Kanban Board App with JWT Authentication

## About This Project

This is a simple Kanban board application where users can log in securely using JSON Web Tokens (JWT). I built this to learn more about authentication and how to manage user sessions. The goal is to make sure only logged-in users can see and manage tasks.

## Features

- **Login Page**: Users enter a username and password to log in.
- **JWT Authentication**: The app uses tokens to verify users.
- **Session Management**: If a user is inactive for too long, they will need to log in again.
- **Error Messages**: Shows messages when login details are wrong.
- **Logout**: Users can log out and their session is cleared.

## Why I Built This

I am learning full-stack development, and I wanted to understand how authentication works in real-world applications. This project helps me practice using Node.js, Express, PostgreSQL, and JWTs.

## How It Works

### User Flow

1. Go to the login page and enter your username and password.
2. If your login is correct, you are taken to the Kanban board.
3. If the login is wrong, you will see an error message.
4. Once logged in, you can manage your tasks.
5. If you log out, you will need to log in again to see your tasks.
6. If you stay inactive for too long, the app will log you out.

## Getting Started

### What You Need

- Node.js (v14 or later)
- PostgreSQL database
- Basic knowledge of how JWTs work

### How to Set Up

1. **Clone the repository**:

   ```bash
   git clone git@github.com:heliamosa/mode14.git
   ```

2. **Go to the project folder**:

   ```bash
   cd mode14
   ```

3. **Install server dependencies**:

   ```bash
   cd server
   npm install
   ```

4. **Install client dependencies**:

   ```bash
   cd ../client
   npm install
   ```

### Setting Up Environment Variables

You need to create a `.env` file in the `server` folder. Add the following:

```env
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
JWT_SECRET=your_secret_key
```

Replace `your_database_username`, `your_database_password`, and `your_secret_key` with actual values.

## Running the App

1. **Start the server**:

   ```bash
   cd server
   npm start
   ```

2. **Start the client**:

   ```bash
   cd ../client
   npm start
   ```

3. **Open the app in your browser**:

   Go to `http://localhost:3000`.

## License

This project is free to use under the MIT License.

## Links

- **GitHub Repository**: [https://github.com/heliamosa/mode14]
- **Deployment**: 