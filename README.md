## Tentang Sekolahku

Sekolahku adalah aplikasi manajemen sekolah berbasis website yang di bangun dan di kembangkan dengan Framework Laravel. Fitur-fitur pada aplikasi Sekolahku antara lain :

-   Website Sekolah (Done)
-   PPDB (Done)
-   Perpustakaan (Done)
-   Sistem Pembayaran Sekolah SPP (Done)
-   Alumni

## Installation

-   Install [Composer](https://getcomposer.org/download) and [Npm](https://nodejs.org/en/download)
-   Clone the repository: `git clone https://github.com/andes2912/sekolahku`
-   Install dependencies: `composer install ; npm install ; npm run dev`
-   Run `cp .env.example .env` for create .env file
-   Run `php artisan migrate --seed` for migration database
-   Run `php artisan storage:link` for create folder storage

## Penggunaan

-   Login sebagai Admin email: kepsek@sch.id & pw: Bismillah
-   Login sebagai PPDB, Perpustakaan, Staf, Pengajar semua dengan password 12345678

## Tampilan

-   Halaman Home
    ![alt](galeri/home.png)

-   Halaman PPDB
    ![alt](galeri/user-ppdb.png)

-   Halaman LOGIN
    ![alt](galeri/login.png)

-   Halaman DASHBOARD
    ![alt](galeri/backend-dashboard.png)

-   Halaman PROFILE
    ![alt](galeri/backend-profile.png)

-   Halaman TAMBAH PROGRAM STUDI
    ![alt](galeri/backend-add-programstudi.png)

-   Halaman LIST PROGRAM STUDI
    ![alt](galeri/backend-list-program-studi.png)

-   Halaman TAMBAH PENGAJAR
    ![alt](galeri/backend-tambah%20pengajar.png)

-   Halaman LIST PENGAJAR
    ![alt](galeri/backend-list-pengajar.png)

-   Halaman STAF PPDB
    ![alt](galeri/backend-stap%20ppd.png)
