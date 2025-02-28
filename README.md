# AlmanaFund

A Laravel-based web application for managing funds and donations.

## About

AlmanaFund is built with Laravel, leveraging modern PHP practices and a robust tech stack to provide a reliable and scalable platform.

## Tech Stack

- PHP 8.x
- Laravel Framework
- MySQL/MariaDB
- Node.js & NPM (for frontend assets)
- Vite (for asset bundling)

## Prerequisites

- PHP >= 8.0
- Composer
- Node.js & NPM
- MySQL/MariaDB

## Installation

1. Clone the repository
```bash
git clone git@github.com:alqahtani/almanafund.git
```

2. Install PHP dependencies
```bash
composer install
```

3. Install Node.js dependencies
```bash
npm install
```

4. Configure environment
```bash
cp .env.example .env
php artisan key:generate
```

5. Set up your database credentials in `.env`

6. Run migrations
```bash
php artisan migrate
```

7. Build assets
```bash
npm run dev
```

## Development

- Run development server: `php artisan serve`
- Watch assets: `npm run dev`
- Build for production: `npm run build`

## License

This project is proprietary software. All rights reserved.

## Contact

For any inquiries about this project, please reach out to the development team.
