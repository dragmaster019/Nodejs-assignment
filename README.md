# Nodejs-assignment
Blooging application

Blog Management System is a full-stack web application with user authentication, including blog setup, login, logout, and password reset. Registered users can create and set up their own blogs and view all their content on the admin dashboard. Readers can comment on posts and reply to comments. Readers will receive email notifications for replies to their comments using Nodemailer. The web application enables users to perform CRUD operations on their blog content. It is implemented using the Model-View-Controller (MVC) architecture to separate concerns. The application utilizes the Socket.IO library to facilitate real-time updates on posts and comments.

I have added all CRUD functions. I have worked on this project and the assignment is matching with my project I am writing the connection guideline-

1.Make a config folder and add a config.js file in it.

2. Paste the following code in the config.js file:

   const session_secret = "";
const email_user = "";
const app_password = "";

module.exports = {
    session_secret,
    app_password,
    email_user
}

3. Open index.js file and locate the following line:
 mongoose.connect("mongodb://localhost:27017/db_name")

change db name according to you.


HOW TO RUN ->

Run the command npm install to install the required dependencies.

Start the server by running the command node index.js.

Open the following URL in a web browser: http://localhost:3000/



