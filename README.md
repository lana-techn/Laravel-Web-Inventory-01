# Maulana Inventory Management System

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<strong>A comprehensive inventory management system built with Laravel</strong>
</p>

---

## 📋 About This Project

Maulana Inventory Management System is a web-based application designed to manage inventory, track borrowed items, and monitor users. Built with Laravel, this system provides an intuitive interface for inventory control and borrowing management.

### Features
- **Inventory Management**: Track and manage barang (items) in the system
- **Borrowing System**: Monitor peminjaman (borrowings) and track borrowed items
- **User Management**: Manage users and their roles
- **Dashboard**: Real-time overview of inventory status
- **Responsive Design**: Works seamlessly across devices

---

## 📸 Screenshots

### Dashboard
![Screenshot 1](./assets/Screenshot%202025-12-01%20at%2009.03.18.png)

### Inventory Management
![Screenshot 2](./assets/Screenshot%202025-12-01%20at%2009.03.59.png)

### Borrowing Records
![Screenshot 3](./assets/Screenshot%202025-12-01%20at%2009.04.19.png)

### Item Details
![Screenshot 4](./assets/Screenshot%202025-12-01%20at%2009.04.34.png)

### User Management
![Screenshot 5](./assets/Screenshot%202025-12-01%20at%2009.04.42.png)

---

## 🛠️ Tech Stack

- **Backend**: Laravel Framework
- **Database**: MySQL
- **Frontend**: Blade Templates, Tailwind CSS
- **Build Tools**: Vite
- **Package Manager**: Composer, NPM

---

## 📦 Installation

### Prerequisites
- PHP >= 8.1
- Composer
- Node.js & NPM
- MySQL

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/lana-techn/Laravel-Web-Inventory-01.git
   cd maulana-inventory
   ```

2. **Install dependencies**
   ```bash
   composer install
   npm install
   ```

3. **Environment Configuration**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Database Setup**
   ```bash
   php artisan migrate
   php artisan db:seed
   ```

5. **Build Assets**
   ```bash
   npm run dev
   ```

6. **Start the Server**
   ```bash
   php artisan serve
   ```

Visit `http://localhost:8000` in your browser.

---

## 📁 Project Structure

- `app/` - Application logic (Controllers, Models, Middleware)
- `database/` - Migrations, Seeders, and Factories
- `resources/` - Blade templates and assets
- `routes/` - Application routes
- `config/` - Configuration files
- `storage/` - File storage and logs

---

## 🗄️ Database Models

- **User** - User accounts and authentication
- **Barang** - Inventory items
- **Peminjaman** - Borrowing records
- **Borrow** - Borrow details and tracking
- **Item** - Individual item management

---

## 🔒 License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

---

## 👨‍💻 Author

Built by [lana-techn](https://github.com/lana-techn)
