# SI_PERPUS

Aplikasi SI_PERPUS menggunakan Framework Laravel 5.8. Aplikasi ini cocok untuk digunakan untuk disekolah/dikampus atau umum. Aplikasi ini memiliki 2 role, yaitu _Administrator Perpustakaan_, dan _Anggota Perpustakaan_. Beberapa CRUD menggunakan AJAX untuk pengambilan data agar mengurangi penggunaan pindah halaman.

### Prasyarat

Berikut beberapa hal yang perlu diinstal terlebih dahulu:

-   Composer (https://getcomposer.org/)
-   PHP 7.2.x
-   MySQL 14.5.x
-   XAMPP

Jika Anda menggunakan XAMPP, untuk PHP dan MySQL sudah menjadi 1 (bundle) didalam aplikasi XAMPP.

### Fitur
-   Register
-   Log In
-   CRUD Pengguna
-   CRUD Kategori Buku
-   CRUD Buku
-   Informasi peminjaman dari pengguna

### Preview Gambar

_Register_
![Image 1](https://imgur.com/undefined)

_Log In Admin_
![Image 2](https://imgur.com/3vE7RoI)

_Log In Anggota_
![Image 3](https://imgur.com/jywhlmC)

_Dashboard_
![Image 4](https://imgur.com/f8y40CF)

_Daftar Pengguna_
![Image 5](https://imgur.com/mZuXxKd)

_Daftar Kategori Buku_
![Image 6](https://imgur.com/KzGhjhr)

_Daftar Buku_
![Image 7](https://imgur.com/NM6Itmn)

_Daftar Peminjam Buku_
![Image 8](https://imgur.com/6Vv1GH4)

_Histori Peminjam Buku_
![Image 9](https://imgur.com/HWiq5pU)

### Langkah-langkah instalasi

-   Clone repository ini

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

### Lisensi

Aplikasi ini boleh untuk dibagi dan diubah. Mohon tidak untuk diperjualbelikan!
