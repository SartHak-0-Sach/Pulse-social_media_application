# Pulse Social Media Application 🚀📱

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Key Features](#features)
  - [File Structure](#file-structure)
  - [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Future Improvements](#future-improvements)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The **Pulse Social Media Application** is a modern, feature-rich social media platform built using the **MERN stack** (MongoDB, Express.js, React, and Node.js). It provides a complete social media experience where users can create accounts, post content, like, comment, and follow others. The app is designed to deliver a seamless user experience with real-time notifications and responsive design for both mobile and desktop.

### The challenge
The challenge of building this application was to create a fully functional social media platform that:
- Supports **user authentication** (login, registration).
- Allows users to **post content** (text, images).
- Provides **social interaction** features such as likes, comments, and following users.
- Uses **MongoDB** for storing user data, posts, comments, etc.
- Implements a **real-time notification system** to notify users of activities (likes, comments, follows).
- Is fully responsive, providing a great user experience across devices.

### Features
- **User Authentication:** Sign up, log in, and manage profiles with JWT-based authentication.
- **Post Creation:** Users can create posts, including text and images.
- **Like & Comment:** Users can like and comment on posts.
- **Follow/Unfollow:** Users can follow and unfollow other users.
- **Real-time Notifications:** Users receive notifications for activities like likes, comments, and follows.
- **Responsive Design:** The app adapts to mobile, tablet, and desktop screens for a smooth experience.
- **Dashboard:** A user dashboard to view posts, followers, and notifications.

### File Structure
```
/root-directory
|-- backend/                     # Backend server (Node.js, Express, MongoDB)
|   |-- controllers/              # Handles API logic (user authentication, posts, etc.)
|   |-- models/                   # MongoDB models (User, Post, Comment, etc.)
|   |-- routes/                   # API routes for different features (auth, posts, etc.)
|   |-- config/                   # Configuration files (MongoDB connection, JWT secret)
|   |-- server.js                 # Main backend entry point
|
|-- frontend/                     # Frontend client (React)
|   |-- components/               # Reusable React components (Post, Navbar, etc.)
|   |-- pages/                    # React pages (Home, Profile, Login, etc.)
|   |-- services/                 # Functions to make API calls (auth, posts, etc.)
|   |-- App.js                    # Main React component with routing
|   |-- index.js                  # React app entry point
|
|-- .env                          # Environment variables (MongoDB URI, JWT secret)
|-- package.json                  # Project dependencies and scripts
|-- README.md                     # Project description and instructions
```

### Technologies Used
- **MongoDB** for database management (storing users, posts, comments).
- **Express.js** for backend API development.
- **React** for building a dynamic frontend.
- **Node.js** as the runtime environment for backend development.
- **JWT** for user authentication (JSON Web Tokens).
- **Socket.io** for real-time notifications (new likes, comments, follows).
- **Mongoose** for interacting with MongoDB.
- **Axios** for making HTTP requests from the frontend.

## Setup Instructions

### Prerequisites
- Node.js and npm installed (for backend and frontend development).
- MongoDB instance (either locally or through a service like MongoDB Atlas).
- Basic understanding of JavaScript, Node.js, React, and MongoDB.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pulse-social-media-application.git
   ```

2. Navigate to the project directory:
   ```bash
   cd pulse-social-media-application
   ```

3. Set up the **backend**:
   - Navigate to the `backend/` directory:
     ```bash
     cd backend
     ```
   - Install backend dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file with the following content:
     ```
     MONGODB_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret_key
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

4. Set up the **frontend**:
   - Navigate to the `frontend/` directory:
     ```bash
     cd frontend
     ```
   - Install frontend dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

5. The app should now be running locally at `http://localhost:3000` for the frontend and `http://localhost:5000` for the backend API.

### Usage
1. **User Authentication:** Sign up or log in to the app. The JWT token will be used for authentication and authorization.
2. **Post Creation:** After logging in, you can create posts by adding text and images.
3. **Likes & Comments:** Interact with posts by liking and commenting on them.
4. **Following:** Follow or unfollow other users to see their posts in your feed.
5. **Notifications:** Get real-time notifications whenever someone interacts with your posts.

### Future Improvements
- **Direct Messaging:** Implement private messaging between users.
- **Post Editing/Deletion:** Allow users to edit or delete their posts.
- **Advanced Search:** Add the ability to search for users, posts, or comments.
- **Profile Customization:** Let users update their profile information and avatar.
- **Post Media:** Add support for video uploads along with images.
- **Dark Mode:** Add a toggle to switch between light and dark modes for better UX.
- **User Verification:** Implement email verification for new users.

### Useful resources

- [React Documentation](https://reactjs.org/docs/getting-started.html) - The official guide to learning React.
- [Node.js Documentation](https://nodejs.org/en/docs/) - Learn more about Node.js and its capabilities.
- [MongoDB Documentation](https://www.mongodb.com/docs/) - Comprehensive guide to MongoDB usage.
- [Express.js Documentation](https://expressjs.com/) - Documentation for building web apps with Express.js.
- [JWT Documentation](https://jwt.io/introduction/) - Learn how JSON Web Tokens work for secure authentication.
- [Socket.io Documentation](https://socket.io/docs/) - Real-time bidirectional event-based communication library.

## Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LinkedIn - [Sarthak Sachdev](https://www.linkedin.com/in/sarthak2004/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## Acknowledgments

Special thanks to the open-source community and the authors of the tools and libraries used in this project, including **MongoDB**, **Express.js**, **React**, **Node.js**, and **Socket.io**.

## Got feedback for me?

Feel free to reach out via email at saarsaach30[at]gmail[dot]com with any feedback or suggestions!

## Contributing
Contributions are welcome! Fork the repository, make changes, and submit a pull request.

## License📃
This project is licensed under the MIT License.

Copyright (c) 2024, Sarthak Sachdev

**Happy coding!** 😊🚀
