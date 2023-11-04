# Wordpress Template
This repository contains a WordPress template that you can use as a foundation for your projects. Before you get started, please make sure you have the following prerequisites in place:

### PREREQUISITES

- A web server with PHP support. For Windows development, we recommend using XAMPP.
- MySQL 8 or MariaDB 10.5. The code has been tested to work with MariaDB 10.5 or later, but it should work with MySQL 8 or later as well.
- PHP 8.2. The code has been tested to work with PHP 8.2, but it should work with PHP 7.4 as well.

## Getting Started

Follow this step-by-step guide to set up the project for development:

1. **Download and Install XAMPP:**
   - Go to the [XAMPP download page](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/).
   - Download the latest version of XAMPP with PHP 8.2, and make sure to select the 64-bit version.
   - During the installation, you can specify a distinct installation path, e.g., `c:\xampp82`, to differentiate it from any existing XAMPP installations. When selecting components, only choose MySQL.

2. **Start XAMPP:**
   - After installing XAMPP, run the application.
   - Activate the Apache and MySQL services within XAMPP.

3. **Clone the Repository:**
   - Navigate to `C:\xampp82\htdocs\` (or your chosen installation path) and clone this repository into that directory.

4. **Import Database Dump:**
   - Import the database dump from the `./database.sql` file into your MySQL server.

5. **Access the Application:**
   - Open your web browser and go to [http://localhost/wordpress_template/wordpress](http://localhost/wordpress_template/wordpress) to access and use the application.

Now you have successfully set up the WordPress template for development. You can customize and build upon this foundation to create your own WordPress projects.