User Auth
A complete authentication system which can be used as a starter code for creating any new application.

Setup the Project
Clone or Download the Repo.
cd user-auth goto the Repo using Terminal.
Put the Gmail Account Details in ./config/nodemailer.js for Email Services.
Run mongod to start the MongoDB Database.
Run npm start to ignite the project.
Routes
Homepage: http://localhost:8000/
Sign Up: http://localhost:8000/users/sign-up
Sign In: http://localhost:8000/users/sign-in
Forgot Password: http://localhost:8000/users/forgot-password
Reset Password: http://localhost:8000/users/reset/:emailed-token-id
Dashboard: http://localhost:8000/users/dashboard
