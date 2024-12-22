# Inven BS

Aplikasi inventaris barang sekolah menggunakan Framework Laravel 5.8. Aplikasi ini cocok untuk digunakan untuk disekolah atau umum. Aplikasi ini memiliki 3 role, yaitu _Administrator Perpustakaan_, _Operator Perpustakaan_ dan _Anggota Perpustakaan_. Beberapa CRUD menggunakan AJAX untuk pengambilan data agar mengurangi penggunaan pindah halaman.

### Prasyarat

Berikut beberapa hal yang perlu diinstal terlebih dahulu:

-   Composer (https://getcomposer.org/)
-   PHP 7.2.x
-   MySQL 14.5.x
-   XAMPP

Jika Anda menggunakan XAMPP, untuk PHP dan MySQL sudah menjadi 1 (bundle) didalam aplikasi XAMPP.

### Fitur

-   CRUD Pengguna
-   CRUD Kategori Buku
-   CRUD Buku
-   Informasi peminjaman dari pengguna



### Langkah-langkah instalasi

-   Clone repository ini

```
https://github.com/amirsaleh.github.io/perpusweb.git
```

```
github.com:amirsaleh.github.io/perpusweb.git
```

-   Install seluruh packages yang dibutuhkan

```
composer install
```

-   Siapkan database dan atur file .env sesuai dengan konfigurasi Anda
-   Ubah value APP_NAME= pada file .env menjadi nama aplikasi yang anda inginkan
-   Jika sudah, migrate seluruh migrasi dan seeding data

```
php artisan migrate --seed
```

-   Jalankan local server

```
php artisan serve
```

-   User default aplikasi untuk login

##### Administrator Perpustakaan

```
Email       : admin@mail.com
Password    : secret
```

##### Operator Perpustakaan

```
Email       : operator@mail.com
Password    : secret
```

##### Anggota Perpustakaan

```
Email       : anggota@mail.com
Password    : secret
```

### Dibuat dengan

-   [Laravel](https://laravel.com) - Web Framework

### Kontribusi

Silahkan request melalui kolom `Pull Requests` jika ingin melakukan kontribusi

### Pembuat

-   **Amirudin Saleh** - _Programmer_ -https://github.com/19amirsaleh/amirsaleh.github.io/

### Lisensi

Aplikasi ini boleh untuk dibagi dan diubah. Mohon tidak untuk diperjualbelikan!

### Ucapan terima kasih

-   Stackoverflow
-   Google

