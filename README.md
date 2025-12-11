<div align="center">

# 🐾 Shop.Co - Pet Products E-Commerce Platform

**Everything your pet needs, all under one roof!**

[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![PHPMailer](https://img.shields.io/badge/PHPMailer-6.7-FF6B6B?style=for-the-badge)](https://github.com/PHPMailer/PHPMailer)

</div>

---

## 📋 Table of Contents

- [✨ Features](#-features)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🛠️ Technologies Used](#️-technologies-used)
- [📸 Screenshots](#-screenshots)
- [🔧 Installation](#-installation)
- [📝 Usage](#-usage)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ✨ Features

<div align="center">

| Feature | Description |
|---------|-------------|
| 🏠 **Homepage** | Beautiful landing page with featured products and categories |
| 🛍️ **Product Catalog** | Browse products with ratings, prices, and descriptions |
| 🔐 **User Authentication** | Secure login and registration system |
| 📧 **Email Integration** | PHPMailer integration for email functionality |
| 📱 **Responsive Design** | Mobile-friendly interface |
| ⭐ **Product Ratings** | Visual star ratings for products |
| 🎨 **Modern UI** | Clean and attractive user interface |

</div>

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **PHP** (version 7.4 or higher)
- **Composer** (for dependency management)
- **Web Server** (Apache/Nginx) or PHP built-in server
- **MySQL/MariaDB** (if database integration is needed)

---

## 📁 Project Structure

```
websystem/
│
├── 📄 index.php              # Main homepage
├── 📄 login_form.php         # User login page
├── 📄 register_form.php      # User registration page
├── 📄 design.css             # Main stylesheet
├── 📄 login.css              # Login page styles
├── 📄 style.css              # Registration page styles
│
├── 📁 inc/
│   └── nav.php               # Navigation component
│
├── 📁 img/                   # Image assets
│   ├── logo.png
│   ├── product*.jpg          # Product images
│   ├── category*.png         # Category images
│   └── ...
│
├── 📁 vendor/                # Composer dependencies
│   └── phpmailer/            # PHPMailer library
│
├── 📄 composer.json          # PHP dependencies
└── 📄 README.md              # This file
```

---

## 🛠️ Technologies Used

<div align="center">

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=flat-square&logo=font-awesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat-square&logo=google-fonts&logoColor=white)

### Backend
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![PHPMailer](https://img.shields.io/badge/PHPMailer-6.7-FF6B6B?style=flat-square)

### Tools
![Composer](https://img.shields.io/badge/Composer-885630?style=flat-square&logo=composer&logoColor=white)

</div>

---

## 🔧 Installation

### Step 1: Clone the Repository

```bash
git clone <repository-url>
cd websystem
```

### Step 2: Install Dependencies

```bash
composer install
```

This will install PHPMailer and other required dependencies.

### Step 3: Configure Your Environment

1. Set up your web server to point to the project directory
2. Configure database connection (if applicable)
3. Set up email settings for PHPMailer (if using email features)

### Step 4: Run the Application

**Using PHP Built-in Server:**
```bash
php -S localhost:8000
```

**Using Apache/Nginx:**
- Configure your virtual host to point to the project directory
- Access via `http://localhost` or your configured domain

---

## 📝 Usage

### Homepage
- Navigate to `index.php` to view the main homepage
- Browse featured products and categories
- View product details, ratings, and prices

### User Registration
1. Click on "Register" or navigate to `register_form.php`
2. Fill in the registration form:
   - First Name & Last Name
   - Username
   - Email Address
   - Phone Number
   - Address
   - Password & Confirm Password
3. Submit the form

### User Login
1. Navigate to `login_form.php`
2. Enter your email and password
3. Click "Login Now"

---

## 🎨 Product Categories

<div align="center">

| Category | Description |
|----------|-------------|
| 🍖 **Food** | Premium pet food and treats |
| 🎾 **Accessories** | Leashes, bowls, and pet accessories |
| 🛁 **Bath** | Shampoos and grooming products |
| 💊 **Health** | Health and wellness products |

</div>

---

## 📸 Screenshots

> **Note:** Add screenshots of your application here to showcase the UI/UX

### Homepage
![Homepage](img/headerbg.jpg)

### Product Listings
Products are displayed with:
- ⭐ Star ratings
- 💰 Pricing information
- 📝 Detailed descriptions

---

## 🔐 Security Considerations

- ⚠️ **Important:** Ensure proper input validation and sanitization
- 🔒 Implement password hashing (e.g., `password_hash()`)
- 🛡️ Use prepared statements for database queries
- 🔑 Protect sensitive configuration files
- 🚫 Validate and sanitize all user inputs

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. 🍴 Fork the repository
2. 🌿 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🔀 Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👥 Authors

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/yourusername)

---

## 🙏 Acknowledgments

- [PHPMailer](https://github.com/PHPMailer/PHPMailer) for email functionality
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography

---

<div align="center">

### ⭐ Star this repo if you find it helpful!

**Made with ❤️ for pet lovers**

[⬆ Back to Top](#-shopco---pet-products-e-commerce-platform)

</div>

