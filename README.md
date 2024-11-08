# facebook
Facebook Login Page
This project is a simple mockup of a Facebook login and account creation interface built with HTML, CSS, and JavaScript. It provides a basic frontend-only simulation of a login and registration process.

Features
Login Form: Users can enter their email and password to "log in." The login validation is purely client-side, with a fixed example credential.
Create Account Form: Users can fill out a form to simulate account creation. This form doesn’t send data to a server but simply validates fields and shows a success message.
Responsive Design: The page is designed to be responsive and works well on both desktop and mobile devices.
Project Structure
HTML: The structure of the page, including containers for the login, registration, and home (post-login) views.
CSS: Styles for the layout, buttons, and form fields.
JavaScript: Basic interactivity for form validation, switching views, and logging in/out.
Usage
Clone or download the project files.
Open index.html in a web browser to view the page.
Demo Credentials
For demonstration, you can use the following login details:

Email: user@example.com
Password: password
JavaScript Functions
login(): Checks if the entered email and password match the demo credentials. If valid, the login form is hidden, and a welcome message is displayed.
logout(): Logs out the user by hiding the welcome message and returning to the login form.
showCreateAccount(): Switches the view to the "Create New Account" form.
createAccount(): Simulates account creation by checking if all fields are filled and displaying a success message.
showLogin(): Switches back to the login form from the account creation form.
Future Enhancements
Server-Side Validation: Integrate backend functionality for real authentication and account creation.
Error Handling: Improve error messages and validation for incorrect email formats, weak passwords, etc.

