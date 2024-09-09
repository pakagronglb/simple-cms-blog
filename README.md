# 🚀 Simple CMS Website for Blog

This project is a simple Content Management System (CMS) for a blog website, built using **PHP** and **MySQL**. It allows users to create, update, delete, and display blog posts dynamically. The CMS was created following the [YouTube tutorial by CodingPassiveIncome](https://www.youtube.com/watch?v=TIyiuVaEXV4).

## Features

- Create, Read, Update, and Delete (CRUD) blog posts
- Simple and clean user interface
- Admin panel for managing blog posts
- MySQL database integration for storing blog posts
- Basic authentication (optional: Admin login)

## Technologies Used

- **PHP**: Server-side scripting language used for dynamic content and backend logic.
- **MySQL**: Database management system to store and retrieve blog posts.
- **HTML/CSS**: For creating the structure and design of the blog.
- **Bootstrap**: A frontend framework for responsive design (optional).
  
## Setup and Installation

To get the project up and running on your local machine, follow these steps:

### 1. Prerequisites

Make sure you have the following installed on your system:
- **XAMPP** or **WAMP** (For running PHP and MySQL locally)
- **Web browser** (Chrome, Firefox, etc.)

### 2. Clone the Repository

```bash
git clone https://github.com/your-username/cms-website.git
```

Or download the project files manually.

### 3. Setup the Database

1. Open **phpMyAdmin** and create a new database called `cms_blog`.
2. Import the SQL file provided in the `/db` folder to set up the tables. The SQL file contains the structure for the blog posts.

### 4. Configure the Database

In the `config.php` file, update the following database connection details:

```php
$host = 'localhost';
$user = 'root'; // Database username
$pass = ''; // Database password
$dbname = 'cms_blog'; // Your database name
```

### 5. Start the Local Server

If you are using XAMPP or WAMP, start the Apache and MySQL servers.

1. Place the project folder in your `htdocs` (for XAMPP) or `www` (for WAMP) directory.
2. Open your web browser and navigate to:

```
http://localhost/cms-website
```

### 6. Admin Panel

Access the admin panel to manage blog posts:

```
http://localhost/cms-website/admin
```

### 7. Creating and Managing Blog Posts

Once logged in to the admin panel, you can create, edit, and delete blog posts using the provided forms.

## Credits

This CMS website is based on a tutorial by **CodingPassiveIncome**. You can watch the full tutorial on YouTube [here](https://www.youtube.com/watch?v=TIyiuVaEXV4).

## License

This project is open-source and available under the [MIT License](LICENSE).

---

You can adapt this `README.md` as per your requirements. Make sure to include your GitHub repository link if you plan to share the project online. Good luck with building your portfolio!
