# Aminos E-commerce Laravel Web App

This project is a professional, full-featured e-commerce web application built with Laravel and the Aimeos e-commerce package. It is designed to provide a scalable, customizable, and high-performance online shopping platform.

## Features

- Multi-vendor, multi-channel, and multi-warehouse support
- Handles from a few to billions of products efficiently
- Supports bundles, vouchers, virtual, configurable, custom, and event products
- Subscription management with recurring payments
- Integration with 100+ payment gateways
- Full RTL support for frontend and backend
- Block and tier pricing out of the box
- Customer and group-based pricing extensions
- Discount and voucher system
- Flexible basket rule system
- Comprehensive admin backend with a beautiful dashboard
- Configurable product data sets
- JSON REST API and GraphQL API for administration
- Modular and extensible architecture
- SEO optimized with rich snippets
- Translated into 30+ languages
- Mobile optimized for smartphones and tablets
- Secure and reviewed implementation with high-quality source code

## Requirements

- PHP 8.1 or higher
- MySQL 5.7.8+, MariaDB 10.2.2+, PostgreSQL 9.6+, or SQL Server 2019+
- Web server such as Apache or Nginx
- Composer 2.1+ for dependency management

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YeasineDewan/Aminos-E-commerce-Laravel-web-app-.git
   cd aimeos-laravel-master
   ```

2. Install PHP dependencies using Composer:
   ```bash
   composer install
   ```

3. Configure your environment variables in the `.env` file, including database credentials and `APP_URL`.

4. Run database migrations and seed demo data:
   ```bash
   php artisan migrate
   php artisan aimeos:setup --option=setup/default/demo:1
   ```

5. Set up Laravel authentication (e.g., Laravel Breeze):
   ```bash
   composer require laravel/breeze
   php artisan breeze:install
   npm install && npm run build
   ```

6. Create an admin account:
   ```bash
   php artisan aimeos:account --super your-email@example.com
   ```

7. Serve the application locally:
   ```bash
   php artisan serve
   ```

## Usage

- Access the frontend shop at: `http://localhost:8000/shop/search`
- Access the admin backend at: `http://localhost:8000/admin`

## Configuration

- Ensure `SESSION_DRIVER=file` in your `.env` file for proper basket functionality.
- Adjust file permissions for `public/aimeos` and `public/vendor` directories as needed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please open an issue on the GitHub repository or contact the maintainer at your-email@example.com.
