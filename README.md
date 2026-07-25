# Website Tiket Konser (Hartix)

<p align="center">
  <strong>Sistem Pemesanan Tiket Konser Berbasis Web Menggunakan Laravel</strong>
</p>

<p align="center">
Project pembelajaran yang dikembangkan menggunakan framework Laravel dan database MySQL.
</p>

# Tampilan Aplikasi

## Halaman Beranda

![Halaman Beranda](screenshots/beranda.png)

# Deskripsi

Website Tiket Konser (Hartix) merupakan aplikasi berbasis web yang dirancang untuk memudahkan pengguna dalam memperoleh informasi konser dan melakukan pemesanan tiket secara online. Melalui aplikasi ini, pengguna dapat melihat daftar konser yang tersedia, memperoleh informasi mengenai jadwal konser, serta melakukan proses pemesanan tiket dengan lebih mudah.

Selain menyediakan layanan bagi pengguna, aplikasi ini juga dilengkapi dengan halaman administrator yang digunakan untuk mengelola data konser, data pengguna, serta informasi yang ditampilkan pada website.

Project ini dikembangkan sebagai media pembelajaran dalam pengembangan aplikasi web menggunakan framework Laravel.

# Fitur Utama

### User

- Login akun
- Registrasi akun
- Melihat halaman beranda
- Melihat informasi konser
- Melihat detail konser
- Melakukan pemesanan tiket
- Logout

### Administrator

- Login Admin
- Dashboard Admin
- Mengelola data konser
- Mengelola data pengguna
- Mengelola data pemesanan tiket
- Logout

# Teknologi yang Digunakan

| Teknologi | Keterangan |
|-----------|------------|
| Laravel | Framework Backend |
| PHP | Bahasa Pemrograman |
| MySQL | Database |
| HTML5 | Struktur Halaman |
| CSS3 | Tampilan Website |
| Bootstrap | User Interface |
| JavaScript | Interaksi Website |

---

# 📁 Struktur Project

```text
app/
bootstrap/
config/
database/
public/
resources/
routes/
storage/
tests/

artisan
composer.json
package.json
README.md
```
# Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/Esharani1103/Esharani1103-TiketKonser.git
```

### 2. Masuk ke Folder Project

```bash
cd Esharani1103-TiketKonser
```

### 3. Install Dependency

```bash
composer install
```

### 4. Copy File Environment

```bash
cp .env.example .env
```

### 5. Generate Application Key

```bash
php artisan key:generate
```

### 6. Konfigurasi Database

Atur koneksi database pada file `.env`.

### 7. Jalankan Migrasi

```bash
php artisan migrate
```

### 8. Jalankan Server

```bash
php artisan serve
```

Kemudian buka browser

```
http://127.0.0.1:8000
```

# Tujuan Project

Project ini dibuat sebagai media pembelajaran untuk memahami proses pengembangan aplikasi web menggunakan framework Laravel, mulai dari pengelolaan data, autentikasi pengguna, hingga implementasi sistem pemesanan tiket konser.

# Tim Pengembang

Project ini dikerjakan secara berkelompok sebagai bagian dari tugas perkuliahan.

# Lisensi

Project ini dibuat untuk keperluan pembelajaran dan portofolio. Seluruh source code hanya digunakan sebagai dokumentasi hasil pengembangan aplikasi.

# Author

**Esharani Janifitz**

GitHub : https://github.com/Esharani1103
