# Website Tiket Konser

<p align="center">
Website pemesanan tiket konser berbasis web yang dikembangkan menggunakan Laravel.
</p>

---

## About Project

Website Tiket Konser merupakan aplikasi berbasis web yang bertujuan untuk memudahkan pengguna dalam melihat informasi konser serta melakukan pemesanan tiket secara online. Selain itu, aplikasi ini juga menyediakan halaman administrator untuk mengelola data konser dan data pengguna.

Project ini dikembangkan sebagai project pembelajaran menggunakan framework Laravel.

---

## Features

- User Authentication (Login & Logout)
- Manajemen Data Konser
- Menampilkan Informasi Konser
- Pemesanan Tiket
- Dashboard Administrator
- Pengelolaan Data Pengguna
- Database MySQL

---

## Technology Stack

- Laravel
- PHP
- MySQL
- HTML
- CSS
- JavaScript
- Bootstrap

---

## Project Structure

```
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/
```
---

## Installation

Clone repository

```bash
git clone https://github.com/Esharani1103/Esharani1103-TiketKonser.git
```

Masuk ke folder project

```bash
cd Esharani1103-TiketKonser
```

Install dependency

```bash
composer install
```

Copy file environment

```bash
cp .env.example .env
```

Generate application key

```bash
php artisan key:generate
```

Konfigurasi database pada file `.env`.

Kemudian jalankan

```bash
php artisan migrate
php artisan serve
```
Akses aplikasi melalui

```
http://127.0.0.1:8000
```
## Team

Project ini dikembangkan secara berkelompok sebagai media pembelajaran dalam pengembangan aplikasi web menggunakan Laravel.

## Notes

Repository ini digunakan sebagai dokumentasi source code project Website Tiket Konser.

## Author

**Esharani Janifitz**

GitHub : https://github.com/Esharani1103
