# Laravel 12 + Inertia 2.0 + Vue 3 Starter Template

A modern, high-performance starter template for building Single Page Applications (SPAs) using the power of Laravel, the reactivity of Vue.js 3, and the seamless bridge of Inertia.js 2.0.

---

## 🚀 Features

- **Laravel 12**: Harness the latest features and performance improvements of the Laravel ecosystem.
- **Inertia.js 2.0**: Build SPAs without the complexity of a separate API layer or client-side routing.
- **Vue.js 3**: Premium frontend experience with Composition API and reactivity.
- **Laravel Breeze**: Full authentication suite pre-configured (Login, Register, Password Reset, etc.).
- **Tailwind CSS**: Modern utility-first styling integrated via the Vite plugin.
- **Vite 6**: Lightning-fast development server and optimized build pipeline.

---

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **PHP**: `^8.2`
- **Node.js**: `^18.x` or higher
- **Composer**: Latest version
- **Database**: MySQL, PostgreSQL, or SQLite

---

## 🛠️ Setup Instructions

Follow these steps to get your project up and running:

### 1. Clone the Repository
```bash
git clone https://github.com/Abenezerzewdu/template.git my-app
cd my-app
```

### 2. Install Dependencies
```bash
# Install backend dependencies
composer install

# Install frontend dependencies
npm install
```

### 3. Environment Configuration
```bash
# Create your local environment file
cp .env.example .env

# Generate the application key
php artisan key:generate
```

### 4. Database Setup
1. Create a new database on your local server.
2. Update the `DB_DATABASE`, `DB_USERNAME`, and `DB_PASSWORD` in your `.env` file.
3. Run the migrations:
```bash
php artisan migrate
```

### 5. Launch Development Servers
You will need to run both the Laravel server and the Vite dev server.

**Terminal 1 (Backend):**
```bash
php artisan serve
```

**Terminal 2 (Frontend):**
```bash
npm run dev
```

Your app will be available at: [http://localhost:8000](http://localhost:8000)

---

## 📂 Project Structure

- `app/`: Contains the core Laravel logic (Models, Controllers, Middleware).
- `resources/js/Pages/`: This is where your Vue.js page components live.
- `resources/js/Layouts/`: Persistent layouts for your application.
- `resources/js/Components/`: Reusable Vue components.
- `routes/web.php`: Define your web routes using `Inertia::render()`.

---

## 📜 License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

---

Made with ❤️ by [Abenezer Zewdu](https://github.com/Abenezerzewdu)
