# Algoritma-Genetika-TSP
Algoritma Genetika Traveling Salesman Problem (TSP) dengan PHP Laravel Framework

## Tujuan
Penerapan Algoritma Genetika (AG) untuk Traveling Salesman Problem (TSP)

## Konsep
Untuk mencapai tujuan aplikasi ini, maka beberapa poin yang harus dipenuhi antara lain:

- Pengguna dapat melakukan login ke aplikasi.
- Pengguna dapat menambahkan dan mengubah titik lokasi sebagai gambaran tempat yang harus dikunjungi, dengan memilih titik pada peta google.
- Pengguna dapat menambahkan parameter dasar perhitungan Algoritma Genetika.
- Sistem dapat melakukan perhitungan Algorimat Genetika dengan parameter masukan dari User.

## Memulai Aplikasi
Aplikasi ini dapat dilakukan instalasi baik pada local server maupun online server dengan minimal spesifikasi sebagai berikut:

#### Kebutuhan Server
1. PHP >=8.0 (and meet [Laravel 9.x server requirements](https://laravel.com/docs/9.x/deployment#server-requirements)),
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
![Tampilan Login](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/1.%20Login.png)

#### Tampilan Dashboard
![Tampilan Dashboard](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/2.%20Dashboard.png)

#### Input Lokasi
![Input Lokasi](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/3.%20Input%20Lokasi%20Index.png)

#### Input Lokasi Tambah
![Input Lokasi Tambah](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/4.%20Input%20Lokasi%20Tambah.png)

#### Input Parameter
![Input Parameter](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/5.%20Input%20Parameter.png)

#### Perhitungan Algorimat Genetika
![Perhitungan Algorimat Genetika](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/6.%20Perhitungan%20G.png)

#### Perhitungan Algorimat Genetika - Result
![Perhitungan Algorimat Genetika - Result](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/7.%20Perhitungan%20AG%20Result.png)

## Download Source Code
Source Code dapat diunduh dengan kontribusi melalui tautan berikut ini: [Download Source Code](https://wawrow.github.io/bootstrap-button-designer/)

## License

Algoritma Genetika Multiple Traveling Salesman Problem (TSP) dengan PHP Laravel Framework is a free and open-sourced software under [MIT License](LICENSE).
