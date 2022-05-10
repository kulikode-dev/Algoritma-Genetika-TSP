# Algoritma-Genetika-TSP
Algoritma Genetika Multiple Traveling Salesman Problem (TSP) dengan PHP Laravel Framework

## Tujuan
Penerapan Algoritma Genetika (AG) untuk Multiple Traveling Salesman Problem (TSP)

## Konsep
Untuk mencapai tujuan aplikasi ini, maka beberapa poin yang harus dipenuhi antara lain:

- Pengguna dapat melakukan login ke aplikasi.
- Pengguna dapat menambahkan dan mengubah titik lokasi sebagai gambaran tempat yang harus dikunjungi, dengan memilih titik pada peta google.
- Pengguna dapat menambahkan parameter dasar perhitungan Algoritma Genetika.
- Sistem dapat melakukan perhitungan Algorimat Genetika dengan parameter masukan dari User.

## Memulai Aplikasi
Aplikasi ini dapat dilakukan instalasi baik pada local server maupun online server dengan minimal spesifikasi sebagai berikut:

#### Kebutuhan Server
1. PHP >=7.3 (and meet [Laravel 9.x server requirements](https://laravel.com/docs/9.x/deployment#server-requirements)),
2. MySQL or MariaDB database,

#### Langkah Instalasi

1. Clone the repo : `alamat git akan dikirim melalui chat`
2. `$ cd algo_laravel`
3. `$ composer install`
4. `$ cp .env.example .env`
5. `$ php artisan key:generate`
6. Create new MySQL database for this application  
(with simple command: `$ mysqladmin -urootuser -p create genetika_laravel`)
7. Set database credentials on `.env` file
8. `$ php artisan migrate`
9. `$ php artisan serve`
10. Login account.

## Kolaborasi
Jika kamu ingin mengembangkan aplikasi ini lebih lanjut dengan kolaborasi, silakan menghubungi kami.

## Screenshots
#### Tampilan Login
![Tampilan Login](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/1. Login.png)

#### Tampilan Dashboard
![Tampilan Dashboard](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/2. Dashboard.png)

#### Input Lokasi
![Input Lokasi](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/3. Input Lokasi Index.png)

#### Input Lokasi Tambah
![Input Lokasi Tambah](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/4. Input Lokasi Tambah.png)

#### Input Parameter
![Input Parameter](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/5. Input Parameter.png)

#### Perhitungan Algorimat Genetika
![Perhitungan Algorimat Genetika](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/6. Perhitungan AG.png)

#### Perhitungan Algorimat Genetika - Result
![Perhitungan Algorimat Genetika - Result](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/images/7. Perhitungan AG Result.png)

## License

Algoritma Genetika Multiple Traveling Salesman Problem (TSP) dengan PHP Laravel Framework is a free and open-sourced software under [MIT License](LICENSE).
