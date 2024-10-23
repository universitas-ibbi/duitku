# Duitku

**Duitku** adalah aplikasi manajemen keuangan berbasis Laravel sebagai demo pembelajaran pemograman web menggunakan Laravel.

## Instalasi

Ikuti langkah-langkah di bawah ini untuk meng-clone dan menjalankan aplikasi secara lokal:

### 1. Clone Repository

Clone repository ini ke direktori lokal Anda dengan perintah berikut:

```bash
git clone https://github.com/universitas-ibbi/duitku
cd duitku
```

### 2. Instal Dependency PHP

Setelah berada di direktori proyek, jalankan perintah berikut untuk menginstal semua dependency PHP menggunakan Composer:

```bash
composer install
```

### 3. Konfigurasi Environment

Salin file `.env.example` menjadi `.env` untuk membuat file environment:

```bash
cp .env.example .env
```

### 4. Generate Key

Generate aplikasi key Laravel dengan perintah berikut:

```bash
php artisan key:generate
```

### 5. Siapkan Database

Buat file database SQLite dengan perintah berikut:

```bash
touch database/database.sqlite
```

Lalu jalankan migrasi database untuk membuat tabel-tabel yang diperlukan:

```bash
php artisan migrate
```

### 6. Instal Dependency Frontend

Instal semua dependency frontend dan lakukan build aset-aset frontend dengan perintah:

```bash
npm install && npm run build
```

### 7. Jalankan Aplikasi

Sekarang Anda bisa menjalankan aplikasi secara lokal dengan perintah:

```bash
php artisan serve
```

Buka aplikasi di browser di alamat [http://localhost:8000](http://localhost:8000).

---

Itu adalah instruksi lengkap untuk mengatur aplikasi **Duitku** di lingkungan lokal.
