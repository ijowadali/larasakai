# About
This project is an initial template for building applications.
Built using using laravel 11, inertia, vue 3 and Sakai admin template.

# Screenshots
<p align="center">  
  <img alt="Login" src="https://i.postimg.cc/QCCcQ9gX/login.png" width="45%">&nbsp;
  <img alt="Dashboard" src="https://i.postimg.cc/wMr4ZBD5/dashboard.png" width="45%">&nbsp;
  <img alt="User" src="https://i.postimg.cc/bY56zs2k/user.png" width="45%">
  <img alt="Add User" src="https://i.postimg.cc/7YTKbwgc/add-user.png" width="45%">&nbsp;
  <img alt="Add User" src="https://i.postimg.cc/vDRL5xWK/delete-user.png" width="45%">&nbsp; 
  <img alt="Role" src="https://i.postimg.cc/tgRfs8Rx/permission.png" width="45%">
  <img alt="Permission" src="https://i.postimg.cc/VNNGfM49/list-permission.png" width="45%">
</p>

# Features
- Reusable Component base on Primevue
- SPA (Single Page Application)
- Role Based Access Control
- Responsive Design
- Modal Form
- Light/Dark Mode
- Toast Notification
- Datatable Serverside
# Requirements
- PHP 8.2
- Composer
- Node.js 18 or Above
- Mysql / Postgree SQL

# Installation
``` bash
git clone https://github.com/ijowadali/larasakai.git
cd larasakai
composer install
npm install
cp .env.example .env
php artisan key:generate

SETTING UP DB CONNECTION IN .env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=larasakai
DB_USERNAME=root
DB_PASSWORD=

php artisan migrate:fresh --seed

START THE SERVER
npm run dev
php artisan serve
```
## Login With
### Superadmin
``` bash
email : superadmin@superadmin.com
password : superadmin
```
### Admin
``` bash
email : admin@admin.com
password : admin
```
### Operator
``` bash
email : operator@operator.com
password : operator
```
# Note
If you find some bug please create the issue or contact me on gmail: ijowadali@gmail.com
