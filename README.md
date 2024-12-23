# Inven BS

Aplikasi inventaris barang sekolah menggunakan Framework Laravel 5.8. Aplikasi ini cocok untuk digunakan untuk disekolah atau umum. Aplikasi ini memiliki 3 role, yaitu _Administrator Perpustakaan_, _Operator Perpustakaan_ dan _Anggota Perpustakaan_. Beberapa CRUD menggunakan AJAX untuk pengambilan data agar mengurangi penggunaan pindah halaman.


### Fitur

-   CRUD Pengguna
-   CRUD Kategori Buku
-   CRUD Buku
-   Informasi peminjaman dari pengguna

### Preview Gambar

_Tampilan Login_
![Tampilan Login](https://github.com/19amirsaleh/amirsaleh.github.io/blob/main/public/assets/images/Tampilan_login.png?raw=true)

_Tampilan Home_
![Tampilan Home](https://github.com/19amirsaleh/amirsaleh.github.io/blob/main/public/assets/images/home.png?raw=true)

_Tampilan Kategori Buku_
![Tampilan Home](https://github.com/19amirsaleh/amirsaleh.github.io/blob/main/public/assets/images/Kategori_Buku.png?raw=true)

_Daftar Buku_
![Tampilan Daftar Buku](https://github.com/19amirsaleh/amirsaleh.github.io/blob/main/public/assets/images/Daftar_Buku.png?raw=true)

_Daftar Pinjaman Buku_
![Tampilan Daftar Pinjaman Buku](https://github.com/19amirsaleh/amirsaleh.github.io/blob/main/public/assets/images/Pinjaman_Buku.png?raw=true)

_Tampilan Histori Pinjaman Buku_
![Tampilan Histori Pinjaman (Buku]https://github.com/19amirsaleh/amirsaleh.github.io/blob/main/public/assets/images/Histori_pinjaman_buku.png?raw=true)

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

