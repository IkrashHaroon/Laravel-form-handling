# Laravel Web Application

A simple Laravel web application featuring routes, form validation, and session handling. The project includes a user-friendly frontend using MDBootstrap and Font Awesome.

## Features

- Home, About, Contact, and Services pages
- User registration form with validation
- Session handling to display user data
- User-friendly UI with MDBootstrap and Font Awesome

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
2.Navigate to the project directory:
  cd your-repo-name
3.Install dependencies:
composer install
npm install
npm run dev
4.Create a copy of the .env file:
cp .env.example .env
5.php artisan key:generate
6.Set up your database configuration in the .env file.
7.Run the migrations:
php artisan migrate
8.Serve the application:
php artisan serve



**Usage**
Navigate to /home to view the home page.
Use the navigation bar to visit About, Contact, and Services pages.
Go to /form to access the registration form.
**Routes**
/home - Displays the home page.
/about - Displays the about page.
/contact - Displays the contact page.
/services - Displays the services page.
/form - Displays the user registration form.
**Controllers**
FrmikrashController
index - Displays the registration form.
register - Handles form submission, validates data, stores user information in session, and redirects to the home page.
**Views**
welcome.blade.php - Home page view.
about.blade.php - About page view.
contactus.blade.php - Contact page view.
sewa.blade.php - Services page view.
form.blade.php - User registration form view.
**Example**
To register a user, fill out the form at /form with the following fields:

Name
Email
Password
Confirm Password

Upon successful registration, you will be redirected to the home page with a success message and user information displayed.

**Contributing**
Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

**License**
MIT

**Developed by Ikrash Haroon**

**Linkedin**: https://www.linkedin.com/in/ikrashharoon/
**Instagram**: https://www.instagram.com/im_ikrashharoon/
**Facbook**:https://www.facebook.com/profile.php?id=61552023565629
**Github**:https://github.com/IkrashHaroon

