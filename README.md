# LOST AND FOUND BACKEND

## Overview

This is the backend for lost and found app

## Folder Structure

```
/LOST-AND-FOUND__BACKEND
│── /src
│   ├── /config            # Configuration files (DB, environment, etc.)
│   ├── /controllers       # Route controllers
│   ├── /middlewares       # Custom middlewares
│   ├── /models            # Database models
│   ├── /routes            # Route definitions
│   ├── /utils             # Utility/helper functions
│   ├── app.js             # Main Express app
│── .env                   # Environment variables
│── .gitignore             # Git ignore file
│── package.json           # Project dependencies
│── README.md              # Project documentation
│── server.js              # Main server entry point
```

## Features

- **Modular Code Structure:** Organized for scalability and maintainability.
- **Environment Variables:** Managed via `.env`.
- **REST API Ready:** Can be extended to support full CRUD operations.

## Installation

### 1️⃣ Clone the Repository

```sh
$ git clone https://github.com/DEVELOPERS-STUDENTS-CLUB/LOST-AND-FOUND__BACKEND.git
$ cd LOST-AND-FOUND__BACKEND
```

### 2️⃣ Install Dependencies

```sh
$ npm install
```

### 3️⃣ Setup Environment Variables

Create a `.env` file:
refer to `.env.example`

### 4️⃣ Run the Server

```sh
$ npm start
```

## Best Practices

✅ **Use `.env` for sensitive data** (Avoid hardcoding credentials).  
✅ **Keep routes, controllers, and models separate** for better organization.  
✅ **Use Git for version control** and `.gitignore` for ignoring unnecessary files.
