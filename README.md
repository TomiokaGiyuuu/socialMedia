Social Media Application (YouMe)
This is a social media application built using the MERN stack (MongoDB, Express.js, React, and Node.js). The application allows users to create an account, log in, create and edit their profile, create and delete posts, and interact with other users by liking and commenting on their posts.

Getting Started
To get started with the application, you need to clone this repository and install the dependencies.

Prerequisites
Node.js (v14 or later)
MongoDB (v4 or later)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/TomiokaGiyuu/socialMedia.git
Navigate to the cloned repository:

bash
Copy code
cd socialMedia
Install the dependencies:

Copy code
npm install
Create a .env file in the root directory of the project and add the following variables:

makefile
Copy code
MONGO_URL=your-mongodb-uri
JWT_SECRET=your-jwt-secret
PORT=3001

MONGO_URL: MongoDB connection string.
JWT_SECRET: A secret string used to sign and verify JSON Web Tokens.
Running the Application
To run the application, you need to start both the server and the client.

Start the Server
Navigate to the server directory:

bash
Copy code
cd server
Start the server:

sql
Copy code
npm start
Start the Client
Navigate to the client directory:

bash
Copy code
cd client
Start the client:

sql
Copy code
npm start
The application should now be running at http://localhost:3000.

Features
Authorization
User registration with validation of email, password and unique username.
User login with JSON Web Tokens(JWT) based authentication.
User Profile
Each user can view and edit their own profile.
User profile includes name, email, bio and profile picture.
Posts
Users can create, edit and delete their own posts.
Posts include a title, description, and an optional image.
Users can view all posts created by all users.
Users can like and comment on other users' posts.
Technologies Used
MongoDB: A NoSQL database used to store user and post data.
Express.js: A Node.js framework used to build the server-side API.
React: A JavaScript library used to build the client-side user interface.
Node.js: A JavaScript runtime used to build the server-side API.
JSON Web Tokens(JWT): Used for user authentication and authorization.
bcrypt: Used for hashing passwords.
multer: Used for uploading images.
axios: Used for making HTTP requests from the client.
