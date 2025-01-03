# Pure Glow - Face Serum Landing Page

Welcome to the **Pure Glow** project! This WordPress website serves as a landing page for a face serum product, designed specifically for a company interview. The site showcases the product's benefits and encourages visitors to engage with the brand.

## Features

- **Responsive Design**: The website is fully responsive, ensuring a seamless experience on both desktop and mobile devices.
- **Navigation Bar**: A user-friendly navigation bar that allows easy access to different sections of the landing page.
- **AI-Generated Images**: All images used on the site are created using an AI image generator, providing a unique visual appeal.
- **Seven Sections**:
  1. **Reveal Your Natural Glow**: An engaging introduction with an overlapping design.
  2. **Why Choose Your Glow**: Highlights the benefits of the face serum.
  3. **Transform Your Skin Routine**: Encourages users to integrate the product into their daily routine.
  4. **Join the Pure Glow Revolution**: A call to action for visitors to become part of the brand community.
  5. **Sign Up Now to Claim Your Offer**: A form created using the Contact Form 7 plugin for lead generation.
  6. **Testimonials**: A section showcasing customer feedback and experiences.
  7. **Footer**: Contains social media icons, quick links, and contact information.

 ## Plugins and Theme

This project utilizes two essential plugins to enhance the website's functionality and design:

- **Elementor**: A powerful page builder that allows for intuitive drag-and-drop design, enabling the creation of visually stunning layouts without any coding knowledge. It ensures that the landing page is both aesthetically pleasing and mobile-responsive.

- **Contact Form 7**: This plugin is used to create the sign-up form in the fifth section of the landing page. It provides a simple way to manage contact forms and integrates seamlessly with Elementor for a smooth user experience.

### Theme

The website is built using the **Astra** theme, known for its lightweight and customizable nature. Astra is perfect for creating fast-loading websites and offers a variety of pre-built templates and design options, making it an excellent choice for this landing page project.

### Video Showcase

To see the design and functionality of the Pure Glow landing page in action, please watch the following video:

https://github.com/user-attachments/assets/d68f197b-407d-469e-a3a5-79d345cc5c99

This video will provide a comprehensive overview of the layout, features, and user interactions on the site.

### Installation

To install WordPress on your localhost using provided WordPress files and a database, follow these steps:

1. *Set Up Your Local Server Environment*:
   - Ensure you have a local server environment installed, such as *XAMPP, **WAMP, or **MAMP*. This software will allow you to run PHP and MySQL on your machine.

2. *Copy WordPress Files*:
   - Extract the WordPress files you have and copy them into the appropriate directory:
     - For *XAMPP*, this is usually C:\xampp\htdocs\your-folder-name.
     - For *WAMP*, it’s typically C:\wamp\www\your-folder-name.
     - For *MAMP*, it’s usually Applications/MAMP/htdocs/your-folder-name.

3. *Import the Database*:
   - Open your local server's database management tool (like *phpMyAdmin*).
   - Create a new database for your WordPress installation.
   - Import the provided database file (usually a .sql file) into this newly created database. You can do this by selecting the database and using the "Import" tab in phpMyAdmin.

4. **Configure wp-config.php**:
   - In the WordPress files you copied, locate the wp-config-sample.php file and rename it to wp-config.php.
   - Open wp-config.php in a text editor and fill in the database details:
     php
     define('DB_NAME', 'your_database_name');
     define('DB_USER', 'root'); // Default for XAMPP/WAMP
     define('DB_PASSWORD', ''); // Default is empty for XAMPP/WAMP
     define('DB_HOST', 'localhost');
     
   - Save the changes.

5. *Run the Installation*:
   - Open your web browser and go to http://localhost/your-folder-name.
   - If everything is set up correctly, you should see the WordPress installation page. 
Follow the prompts to complete the installation, including setting up your site title, username, password, and email.

6. *Access Your Local WordPress Site*:
   - Once the installation is complete, you can log in to your WordPress dashboard by navigating to http://localhost/your-folder-name/wp-admin.


## Contributing

Feel free to fork the repository and submit pull requests for any improvements or features you would like to add!







