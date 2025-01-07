# Multi-User Authentication with Role-Based Access (Laravel Breeze)
This project demonstrates how to implement multi-user authentication with role-based access (User and Admin) in a Laravel application using the Breeze Starter Kit.

![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)

## Features

- Authentication System using Laravel Breeze.
- Role-Based Access Control: Admin and User roles with different permissions.
- Middleware Protection to secure routes based on roles.
- Responsive UI for a better user experience.
- Easy to Extend for additional features.

## Installation
Follow these steps to run the project locally :

## 1. Clone the Repository
```
git clone https://github.com/rhmats/multi-role-laravel.git
cd multi-role-laravel
```
## 2. Install Dependencies
```
composer install
npm install
```
## 3. Set Up Environment
```
cp .env.example .env
php artisan key:generate
```
## 4. Update the .env file with your database configuration.
Use the following database name :
```
DB_DATABASE=multi-auth
```
## 5. Run Migrations
Create the necessary tables in your database:
```
php artisan migrate
```
## 6. Install Frontend Assets
Compile the frontend assets :
```
npm run dev
```
## 7. Serve the Application
Start the Laravel development server :
```
php artisan serve
```
Your application will be accessible at http://127.0.0.1:8000.

## Usage
- Admin Role: Access the admin dashboard to manage users.
- User Role: Access the standard user interface with limited features.

## Project Structure
This project uses the following technologies :
- Laravel: Backend framework.
- Laravel Breeze: Authentication starter kit.
- Tailwind CSS: For styling.
- MySQL: Database.

## Contributing
Contributions are welcome! Feel free to submit a pull request or create an issue if you find a bug or have a feature request.

## License
This project is open-source and available under the MIT License.

## 📞 Contact
If you have any questions, feel free to reach out via https://www.linkedin.com/in/rahmat-syafriyani/ or rahmatsyafriyani809@gmail.com
Let's Connect!
