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

## Referensi
- [Jurnal dan Materi Algoritma Genetika](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/tree/main/referensi)
- [A to Z Algoritma Genetika](https://kulikode.gitbook.io/algoritma-genetika)
## Memulai Aplikasi
Aplikasi ini dapat dilakukan instalasi baik pada local server maupun online server dengan minimal spesifikasi sebagai berikut:

#### Kebutuhan Server
1. PHP >=8.0 (and meet [Laravel 9.x server requirements](https://laravel.com/docs/9.x/deployment#server-requirements)),
2. MySQL or MariaDB database,

#### Langkah Instalasi

1. Clone the repo / download source code
2. `$ cd algo_laravel`
3. `$ composer install`
4. `$ cp .env.example .env`
5. `$ php artisan key:generate`
6. Buat Databaase MySQL baru dengan nama misalnya genetika_laravel, lalu dump database dari file SQL pada folder aplikasi "genetika_laravel.sql"
(with simple command: `$ mysqladmin -urootuser -p create genetika_laravel`)
7. Set database credentials on `.env` file
8. `$ php artisan migrate`
9. `$ php artisan serve`
10. Login dengan alamat email `admin@admin.com` dan password `admin123`

## Screenshots
#### Tampilan Login
![Tampilan Login](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/1.%20Login%20Page.png)

#### Tampilan Dashboard
![Tampilan Dashboard](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/2.%20Dashboard.png)

#### Input Lokasi
![Input Lokasi](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/3.%20Input%20Lokasi%20Index.png)

#### Input Lokasi Tambah
![Input Lokasi Tambah](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/4.%20Input%20Lokasi%20Tambah.png)

#### Input Parameter
![Input Parameter](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/5.%20Input%20Parameter.png)

#### Perhitungan Algoritma Genetika
![Perhitungan Algoritma Genetika](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/6.%20Perhitungan%20AG.png)

#### Perhitungan Algorimat Genetika - Result
![Perhitungan Algorimat Genetika - Result](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/7.%20Perhitungan%20AG%20Result.png)

## Update 15 Juli 2023
- Penambahan upload gambar dan deskripsi lokasi
- Penambahan halaman user untuk pencairan rute terpendek menampilkan gambar dan deskripsi lokasi yang telah diinput
- Fixing bug pada pengaturan variable

## Screenshots Update 15 Juli 2023
#### Tampilan User Konsultasi Rute Terpendek Traveling
![Tampilan User Konsultasi Rute Terpendek Traveling](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/8.%20Menu%20User%20Dashboard.png)
#### Tampilan Tambah Gambar dan Deskripsi
![Tampilan Tambah Gambar dan Deskripsi](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/9.%20Add%20image%20upload%20and%20description.png)
#### Tampilan Pilih Lokasi Awal
![Tampilan Pilih Lokasi Awal](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/10.%20Pilih%20lokasi%20awal.png)
#### Tampilan Pilih Lokasi Tujuan (Multiple Select)
![Tampilan Pilih Lokasi Tujuan (Multiple Select)](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/11.%20Pilih%20lokasi%20tujuan%20(multiple).png)
#### Tampilan Hasil Pencairan Rute Tercepat
![Tampilan Hasil Pencairan Rute Tercepat](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/blob/main/images/12.%20Hasil%20pencarian%20rute%20tercepat.png)

## Download Source Code
Source Code dapat diunduh dengan kontribusi melalui tautan berikut ini: [Download Source Code](https://produk.mayar.link/catalog/algoritma-genetika-traveling-salesman-problem-tsp-dengan-php-laravel-framework)

## Pertanyaan dan Jawaban
Kritik dan saran dapat disampaikan melalui [issues](https://github.com/kulikode-dev/Algoritma-Genetika-TSP/issues)

## Credits
- PHP Laravel Framework versi 9
- Tampilan UI dibuat dengan template [SB Admin 2 Free Version](https://startbootstrap.com/theme/sb-admin-2)

## Terms & Conditions
- Aplikasi dibuat dan telah dilakukan pengujian berhasil dijalankan. Apabila terdapat fitur-fitur yang perlu ditambahkan silakan untuk dikembangkan sesuai dengan kebutuhan. 
- Segala tindakan yang dilakukan oleh pengguna atas aplikasi ini, menjadi tanggungjawab dan resiko masing-masing pengguna. Kami tidak bertanggung jawab atas segala kerugian dan/ atau kerusakan sehubungan dengan penggunaan aplikasi ini. 
- Harap tetap mencantumkan credits atas tampilan template UI sesuai dengan ketentuan license yang berlaku.

## License
- Algoritma Genetika Traveling Salesman Problem (TSP) dengan PHP Laravel Framework is a free and open-sourced software under [MIT License](https://opensource.org/licenses/MIT).
- The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
- Source Code stored via [Mega.nz - Free Cloud Storage](https://mega.nz/aff=5gEfSEGiEzQ)
