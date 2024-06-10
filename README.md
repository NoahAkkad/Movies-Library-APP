# Movies Library App

The Movies Library App is a web application built with React for the frontend and a RESTful API for the backend. It allows users to browse movies, manage their favorites, and perform authentication operations.

## Program Specifications

### Technologies Used

#### Frontend
- **React**: JavaScript library for building user interfaces.
- **React Router**: Library for routing in React applications.
- **Context API**: For managing global state within the application.
- **CSS**: For styling the user interface.

#### Backend
- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database used for storing movie data and user information.
- **JWT (JSON Web Tokens)**: For user authentication and authorization.
- **Mongoose**: MongoDB object modeling for Node.js.

### Features

1. **User Authentication**
   - Users can register for an account.
   - Registered users can log in to their accounts securely.
   - Sessions are managed using JWT tokens for authentication.

2. **Movie Browsing**
   - Users can browse through a collection of movies.
   - Search functionality allows users to find specific movies by title.
   - Movie details are displayed, including title, poster, and trailer link.

3. **Favorites Management**
   - Users can add movies to their favorites list.
   - Favorites are stored locally for each user.
   - Users can remove movies from their favorites list.

4. **Admin Features**
   - Admin users have access to additional functionalities.
   - Admins can add new movies to the library.
   - Adding movies requires filling in details like title, poster URL, and trailer link.

## Frontend Operation

1. **Installation**
   - Clone the repository: `git clone <repository-url>`
   - Navigate to the project directory: `cd Movies-Library-APP`
   - Install dependencies: `npm install`

2. **Running the Application**
   - Open another terminal.
   - Navigate to the frontend directory: `cd Movies-Library-APP`
   - Install dependencies: `npm install`
   - Start the frontend server: `npm start`
   - Open your browser and go to `http://localhost:3000`

## Backend Operation

1. **Installation**
   - Clone the project: `git clone <repository-url>`
   - Navigate to the backend directory: `cd movie-fetcher/backend`
   - Install dependencies: `npm install`

2. **Running the Server**
   - Start the backend server: `npm start`
   - The server will run on `http://localhost:8080`

## Credits
This project was created by [NoahAkkad].
