# POS (Point of Sale)

## Introduction

This project is a Point of Sale (POS) system designed to manage sales, inventory, and transactions efficiently. These instructions will guide you through setting up the project on your local development environment.

### Prerequisites
- [Composer](https://getcomposer.org/)
- [Node.js](https://nodejs.org/)
- [XAMPP](https://www.apachefriends.org/index.html) or any other local server environment
- [PHP 8.2](https://www.php.net/) or a compatible version
- [GitHub CLI](https://cli.github.com/) (optional)
- [NVM (Node Version Manager)](https://github.com/nvm-sh/nvm) (optional)

## Features

 - [**Laravel 11**](https://laravel.com/docs/11.x) and [**Nuxt 3**](https://nuxt.com/)
 - [**Laravel Octane**](https://laravel.com/docs/11.x/octane) supercharges your application's performance by serving your application using high-powered application servers.
 - [**Laravel Telescope**](https://laravel.com/docs/11.x/telescope) provides insight into the requests coming into your application, exceptions, log entries, database queries, queued jobs, mail, notifications, cache operations, scheduled tasks, variable dumps, and more.
 - [**Laravel Sanctum**](https://laravel.com/docs/11.x/sanctum) Token-based authorization is compatible with **SSR** and **CSR**
 - [**Laravel Socialite**](https://laravel.com/docs/11.x/socialite) OAuth providers
 - [**Spatie Laravel Permissions**](https://spatie.be/docs/laravel-permission/v6/introduction) This package allows you to manage user permissions and roles in a database.
 - UI library [**Nuxt UI**](https://ui.nuxt.com/) based on [**TailwindCSS**](https://tailwindui.com/) and [**HeadlessUI**](https://headlessui.com/).
 - [**Pinia**](https://pinia.vuejs.org/ssr/nuxt.html) The intuitive store for Vue.js
 - Integrated pages: login, registration, password recovery, email confirmation, account information update, password change.
 - Temporary uploads with cropping and optimization of images.
 - Device management
 - [**ofetch**](https://github.com/unjs/ofetch) preset for working with Laravel API, which makes it possible
use $**fetch** without having to resort to custom $**fetch** wrappers.

## Requirements

 - PHP 8.2 / Node 20+
 - **Redis** is required for the [**Throttling with Redis**](https://laravel.com/docs/11.x/routing#throttling-with-redis) feature
 - [**Laravel Octane**](https://laravel.com/docs/11.x/octane) supports 2 operating modes: Swoole (php extension) or Roadrunner

## Installation
1. `clone repository`
2. `composer install`
3. `mkdir -p tools/php-cs-fixer`
4. `composer require --working-dir=tools/php-cs-fixer friendsofphp/php-cs-fixer`
5. `cp .env.example .env && php artisan key:generate && php artisan storage:link`
6. `php artisan migrate`
7. `php artisan db:seed`
8. `php artisan octane:install`
9. `php artisan octane:start --watch --port=8000 --host=127.0.0.1`
10. `yarn install`
11. `yarn install --save-dev concurrently`
12. `yarn serve`

## Upgrade
1. `npx nuxi upgrade`
2. `composer update`

## Contributing
Thank you for considering contributing to this project! Please refer to the [CONTRIBUTING.MD](CONTRIBUTING.md) guidelines for details on how to get started and the code of conduct for contributors.

## Style Guide
When contributing to this project, please follow the [STYLE GUIDE](STYLE_GUIDE.md) to ensure consistency and maintainability of the codebase.
