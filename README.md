# 🍽️ Recipe Sharing App

This project is a full-stack web application that allows users to share and discover recipes. Users can create accounts, log in, add their own recipes, save recipes they find interesting, and view detailed information about each recipe. The application provides a platform for users to connect with each other through their shared love of cooking.

## 🚀 Key Features

- **User Authentication:** Secure user registration and login functionality.
- **Recipe Creation:** Users can add their own recipes with details like ingredients, quantities, and images.
- **Recipe Discovery:** Browse and search for recipes shared by other users.
- **Save Recipes:** Save favorite recipes to a personal collection.
- **Detailed Recipe View:** View comprehensive information about each recipe, including ingredients and instructions.
- **User Profiles:** View and manage personal profile information.
- **Protected Routes:** Authenticated users only can access certain routes.

## 🛠️ Tech Stack

- **Frontend:**
    - React
    - React Router DOM
    - Vite
    - react-toastify
    - CSS (Bootstrap classes and inline styles)
- **Backend:**
    - Node.js
    - Express
    - Mongoose
    - jsonwebtoken
    - bcryptjs
    - cors
    - body-parser
- **Database:**
    - MongoDB Atlas
- **Build Tool:**
    - Vite

## 📦 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- MongoDB Atlas account

### Installation

1.  **Clone the repository:**

    ```bash
    git clone <repository_url>
    cd <repository_name>
    ```

2.  **Install backend dependencies:**

    ```bash
    cd Api
    npm install
    ```

3.  **Configure backend environment variables:**

    - Create a `.env` file in the `Api` directory.
    - Add the following environment variables:

    ```
    MONGODB_URI=<your_mongodb_connection_string>
    JWT_SECRET=!@#$%^&*()
    PORT=3000
    ```

    Replace `<your_mongodb_connection_string>` with your MongoDB Atlas connection string.

4.  **Install frontend dependencies:**

    ```bash
    cd ../Client
    npm install
    ```

### Running Locally

1.  **Start the backend server:**

    ```bash
    cd Api
    npm start
    ```

    The server will start on port 3000 (or the port specified in your `.env` file).

2.  **Start the frontend development server:**

    ```bash
    cd ../Client
    npm run dev
    ```

    The frontend will be accessible at `http://localhost:5173` (or the port specified by Vite).

## 📂 Project Structure

```
├── Api/
│   ├── Models/
│   │   ├── Recipe.js
│   │   ├── SavedRecipe.js
│   │   ├── User.js
│   ├── controllers/
│   │   ├── recipe.js
│   │   ├── user.js
│   ├── middlewares/
│   │   ├── auth.js
│   ├── routes/
│   │   ├── recipe.js
│   │   ├── user.js
│   ├── server.js
│   ├── package.json
│   └── ...
├── Client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── AddRecipe.jsx
│   │   │   ├── Detail.jsx
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── Navbar.jsx
│   │   │   ├── Profile.jsx
│   │   │   ├── Register.jsx
│   │   │   └── Saved.jsx
│   │   ├── context/
│   │   │   ├── App_State.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   ├── index.css
│   │   └── ...
│   ├── public/
│   │   └── vite.svg
│   ├── vite.config.js
│   ├── package.json
│   └── ...
├── .gitignore
├── README.md
└── ...
```



## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Submit a pull request to the main repository.



## 📬 Contact

If you have any questions or suggestions, feel free to contact me at [Your Email].


