# Survey Penelitian App

Aplikasi survei penelitian berbasis **Laravel** dan **React** yang digunakan untuk membuat, mengelola, dan menganalisis data survei penelitian secara online.

## 📋 Persyaratan Sistem

Pastikan perangkat Anda telah terinstal:

* PHP 8.4 atau lebih baru
* Composer
* Node.js & NPM
* MySQL/MariaDB
* Git

## 🚀 Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/af133/survey-penelitian.git
cd survey-penelitian
```

### 2. Install Dependency

Install dependency backend dan frontend:

```bash
# Install dependency Laravel
composer install

# Install dependency React/Vite
npm install
```

### 3. Konfigurasi Environment

Salin file `.env.example` menjadi `.env`:

```bash
cp .env.example .env
```

Kemudian sesuaikan konfigurasi database pada file `.env`:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=survey_penelitian
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Generate Application Key

```bash
php artisan key:generate
```

### 5. Migrasi Database

```bash
php artisan migrate
```

Jika tersedia data awal (seed):

```bash
php artisan db:seed
```

---

## 🛠 Menjalankan Aplikasi

Jalankan backend Laravel:

```bash
php artisan serve
```

Buka terminal baru, kemudian jalankan frontend:

```bash
npm run dev
```

Aplikasi dapat diakses melalui:

```text
http://127.0.0.1:8000
```

---

## 📦 Build untuk Production

```bash
npm run build
```

Optimasi Laravel:

```bash
php artisan optimize
```

---

## 🔄 Update Proyek

Jika terdapat pembaruan dari repository:

```bash
git pull origin main

composer install

npm install

php artisan migrate

php artisan optimize
```

---

## 🧹 Membersihkan Cache

```bash
php artisan optimize:clear
```

Atau:

```bash
php artisan cache:clear
php artisan config:clear
php artisan route:clear
php artisan view:clear
```

---

## 📁 Struktur Proyek

```text
survey-penelitian/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
│   ├── js/
│   ├── css/
│   └── views/
├── routes/
├── storage/
├── tests/
├── .env
├── composer.json
├── package.json
└── README.md
```

---

## 👨‍💻 Developer

**Andre Firmansyah**

GitHub:
https://github.com/af133

---
