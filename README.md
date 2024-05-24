# KTGK2
# Laravel Application Skeleton
**Build Status** | **Total Downloads** | **PHPStan**

This is a skeleton for creating applications with Laravel 9.x.

The framework source code can be found here: [laravel/laravel](https://github.com/laravel/laravel).

## Installation
- **Download Composer** or update Composer to the latest version using `composer self-update`.
- **Create a new Laravel project**:
  - If Composer is installed globally, run:
    ```
    composer create-project --prefer-dist laravel/laravel [app_name]
    ```
  - If you want to use a custom app directory name (e.g., `/myapp/`), run:
    ```
    composer create-project --prefer-dist laravel/laravel myapp
    ```
- **Webserver setup**:
  - You can either configure your machine's webserver to serve the Laravel application or use Laravel's built-in web server by running:
    ```
    php artisan serve
    ```
  - Then visit `http://localhost:8000` to see the welcome page.

## Update
- Since this skeleton is the starting point for your application and various files would have been modified as per your needs, there isn't a way to provide automated upgrades. Updates must be managed manually.

## Configuration
- **Environment Configuration**:
  - Read and edit the `.env` file in the root directory to set up your environment-specific settings such as database configurations.
  - More detailed environment configurations can be adjusted in `config/database.php` and other configuration files located in the `config` folder.
- **Application Settings**:
  - General settings that are not environment-specific can be adjusted in `config/app.php`.

## Layout
- **Frontend Framework**:
  - The Laravel application skeleton uses [Bootstrap](https://getbootstrap.com/) by default for its frontend framework. However, you can replace it with any other library or custom styles as per your preference.

