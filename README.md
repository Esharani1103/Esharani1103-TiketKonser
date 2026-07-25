# Website Tiket Konser Berbasis Web

Sistem pemesanan tiket konser berbasis website yang dikembangkan menggunakan Laravel untuk memudahkan pengguna melihat informasi konser dan melakukan pemesanan tiket secara online.

---

## Struktur Folder

```text
Esharani1103-TiketKonser/
│
├── app/
│   ├── Http/
│   │   ├── Controllers/
│   │   └── Middleware/
│   └── Models/
│
├── bootstrap/
├── config/
├── database/
│   ├── migrations/
│   └── seeders/
│
├── public/
│
├── resources/
│   ├── views/
│   ├── css/
│   └── js/
│
├── routes/
│   └── web.php
│
├── storage/
├── tests/
│
├── artisan
├── composer.json
├── package.json
├── vite.config.js
└── README.md
```

---

## Frontend

### Teknologi

- Blade Template
- HTML5
- CSS3
- Bootstrap
- JavaScript
- Vite

### Halaman

| Halaman | Keterangan |
|----------|------------|
| Beranda | Menampilkan informasi konser |
| Login | Halaman autentikasi pengguna |
| Register | Pendaftaran akun baru |
| Daftar Konser | Menampilkan daftar konser |
| Detail Konser | Informasi detail konser |
| Pemesanan Tiket | Form pemesanan tiket |

### Fitur Frontend

- Tampilan responsif
- Login dan Register
- Informasi konser
- Detail konser
- Pemesanan tiket
- Navigasi yang mudah digunakan

---

## Backend

### Teknologi

- Laravel
- PHP
- MySQL

### Database

| Tabel | Fungsi |
|--------|--------|
| users | Data pengguna |
| concerts | Data konser |
| bookings | Data pemesanan tiket |

### Panel Admin

| Menu | Fungsi |
|------|--------|
| Dashboard | Ringkasan data |
| Data Konser | CRUD konser |
| Data Pengguna | Kelola pengguna |
| Data Pemesanan | Kelola pemesanan tiket |

---

## Instalasi

### Persyaratan

- PHP 8.x
- Composer
- Node.js
- MySQL / XAMPP

### Langkah Instalasi

```bash
# Clone repository
git clone https://github.com/Esharani1103/Esharani1103-TiketKonser.git

# Masuk ke folder project
cd Esharani1103-TiketKonser

# Install dependency
composer install
npm install

# Copy file environment
cp .env.example .env

# Generate key
php artisan key:generate

# Jalankan migrasi
php artisan migrate

# Build asset
npm run build

# Jalankan aplikasi
php artisan serve
```

Akses aplikasi:

```
http://127.0.0.1:8000
```

---

## Tampilan Aplikasi

### Halaman Beranda

![Beranda](beranda.png)

---

## Tujuan Project

Project ini dikembangkan sebagai media pembelajaran untuk memahami pengembangan aplikasi web menggunakan framework Laravel, mulai dari proses autentikasi pengguna, pengelolaan data, hingga implementasi sistem pemesanan tiket konser.

---

## Tim Pengembang

Project ini dikembangkan secara berkelompok sebagai bagian dari tugas perkuliahan.

---

## Troubleshooting

| Error | Solusi |
|--------|--------|
| Composer error | Jalankan `composer install` |
| Database tidak terkoneksi | Periksa konfigurasi `.env` |
| CSS tidak tampil | Jalankan `npm run build` |
| Route tidak ditemukan | Jalankan `php artisan route:clear` |
| View tidak ditemukan | Jalankan `php artisan view:clear` |

---

## Author

**Esharani Janifitz**

GitHub : https://github.com/Esharani1103
