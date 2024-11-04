# JABU Fabric Hub E-commerce System

**JABU Fabric Hub** is a complete e-commerce platform designed for starting and managing your online fabric business. It provides an easy-to-use interface with extensive features, allowing you to manage product variants, secure transactions, and more. Built using the robust Laravel PHP framework, the platform ensures strong security against SQL injections, XSS, and CSRF attacks.

## Key Features

### General Features
- **Laravel 9** as PHP Framework
- User-friendly and easy to navigate
- Strong code security
- Product search by category, sub-category, child-category, brand, product variant, or custom name
- Email verification for user registration
- Product variants with variant-wise pricing
- Coupon management
- Wishlist functionality
- Flash Deals
- Courier area-wise shipping charge setup
- Integrated shipping module
- Address book management
- Order tracking
- Announcement system
- Maintenance mode
- Multi-vendor system
- Language change option

### Payment Methods
- **Paypal**
- **Stripe**
- **Flutterwave**
- **Paystack**
- **Instamojo**
- **SslCommerz**
- **Cash on Delivery**
- **Bank Payment**

### Admin Features
- Secure admin panel
- Management of categories, sub-categories, and child-categories
- Brand, product, and seller product management
- Flash deal and product review management
- Product reporting
- Country, state, and city management
- Area-wise shipping charge setup
- Shipping and coupon management
- Payment method and advertisement management
- Seller payment withdrawal management
- Customer, seller, and admin management
- SEO settings for all pages
- Slider, homepage, and service management
- Maintenance mode and announcement modal management
- Mega menu and dynamic website footer
- SMTP server mail setup
- Email configuration and template settings
- HTTP request error page management
- General settings and dynamic pagination options
- Multi-admin creation
- FAQ, Terms & Conditions, and Privacy Policy page management
- Custom dynamic pages
- Language options for mobile app and admin panel
- Email subscribers management
- Profile, photo, and password management
- Blog categories, posts, and comments management
- Contact message management

### User Features
- Comprehensive product search
- Email-verified registration system
- User login, password recovery, and reset options
- Profile management (including photo and password updates)
- Order tracking and dashboard
- Wishlist, address book, and quick cart addition
- Product quick view and social media sharing
- Print order invoices
- Product comparison and subscription options
- Banner ads and product review functionality
- Next SEO supported

### Seller Features
- Shop and user profile management
- Password management
- Order logs and product management
- Product variant, report, and review logs
- Withdrawal request management

## Requirements

Before installing, ensure that your server meets the following requirements:

- Apache, nginx, or another compatible web server
- PHP >= 8.1 or higher
- MySQL Database server
- PDO PHP extension
- OpenSSL PHP extension
- mbstring PHP extension
- exif PHP extension
- fileinfo PHP extension
- xml PHP extension
- Ctype PHP extension
- JSON PHP extension
- Tokenizer PHP extension
- cURL PHP extension
- zip PHP extension
- iconv PHP extension

Ensure the `mod_rewrite` Apache module is enabled.

## PHP Configuration

Open your PHP configuration file `php.ini` and change the following settings:


memory_limit = 256M
max_execution_time = 300

## Installation Steps

You can install manually by following these steps:

1. Upload all files into the root folder of your hosting (normally, it is `public_html`).
2. Create a database and import data from `database.sql` (it's located in the source code).
3. Update your database credentials and `APP_URL` in `.env`.

### Accessing the Admin Panel

- Go to `/admin` to access the admin panel.
- The default admin account is `admin` - `12345678`.

## Mockup

You can view the mockup of the JABU Fabric Hub E-commerce System [here](https://drive.google.com/drive/folders/1-Fd9zqbFy6rUtRgbNBAKoto8GraUt4_z?usp=sharing).

## Initial product video demostration

Veiw the initial software [here](https://www.youtube.com/watch?v=Cbh2fzgQOcI)

## Final product video demotration 

Veiw final demostration [here](https://www.youtube.com/watch?v=Lk_ORXo7AKk)

## GitHub Repository

You can access the GitHub repository for the JABU Fabric Hub E-commerce System [here](https://github.com/JABU-2022/jabu_fabric-hub).
