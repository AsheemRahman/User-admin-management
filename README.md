# CRUD Application with User Authentication and Admin Management
This project is a basic CRUD application where users can sign up, log in, and manage their profiles. Admin users have additional permissions to add, edit, and delete other users.

## Features
* User Authentication: Users can sign up, log in.
* Admin Management: Admin users can view, add, edit, and delete any user.
* Frontend: Built with HTML and CSS.
* Backend: Powered by Node.js and Express.js.
* Database: MongoDB for data storage.

## Technologies Used
* Frontend: HTML, CSS
* Backend: Node.js, Express.js
* Database: MongoDB (using Mongoose for database modeling)

## Installation and Setup
### Prerequisites
Make sure you have the following installed on your local machine:

* Node.js
* MongoDB

## Steps to Run Locally

1.Clone the repository:

     git clone https://github.com/AsheemRahman/User-admin-management.git
2.Navigate into the project directory:

    cd User-admin-management
3.Install the dependencies:

    npm install
4.Create a .env file in the root directory and add the following environment variables:

    PORT = 8080
    MONGODB_CONNECTION_STRING='please enter your mongodb connection string'
    ADMIN_USERNAME = "admin username"
    ADMIN_PASSWORD = "admin password"

5.Start the application:

    npm start
6.Open your browser and access the app.

    http://localhost:8080/
   
## Contact

For questions or feedback, feel free to contact me at: Asheem Rahman
