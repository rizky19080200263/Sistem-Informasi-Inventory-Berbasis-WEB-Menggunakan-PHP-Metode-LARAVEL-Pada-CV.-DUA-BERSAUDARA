
![Lgin](https://github.com/user-attachments/assets/ad6be581-7aac-45fd-852d-e1dbd646e7e2)

## *:information_source: Inventoryweb*
Aplikasi ini bisa anda gunakan untuk mengontrol stock barang yang anda miliki sehingga jelas transaksi keluar dan masuk barang tersebut juga mempermudah kontrol barang tersebut.
<br><br>
Untuk tampilannya saya sudah pasang template admin `bootstrap v5` yaitu `sash admin`.

## *:sparkles: Fitur*
* **Dashboard**
* **Jenis Barang**
* **Satuan Barang**
* **Merk Barang**
* **Barang**
* **Customer**
* **Barang Masuk**
* **Barang Keluar**
* **Laporan Barang Masuk**
* **Laporan Barang Keluar**
* **Laporan Stok Barang**
* **Setting Website**
* **Setting Hak Akses user per Role**
* **Setting Menu (bisa tambah menu atau bisa hapus menu)**

## *:electric_plug: Plugin*
* **Yajra Datatables**
* **SweetAlert**
* **jQuery**
* **Datetime picker**

## *:gear: Requirement*
<p>
<img alt="gambar" src="https://img.shields.io/badge/PHP%20-%5E8.1-green"/>
<img alt="gambar" src="https://img.shields.io/badge/Node JS%20-%5E16.14.0-green"/>
<img alt="gambar" src="https://img.shields.io/badge/Npm%20-%5E8.3.1-green"/>
<img alt="gambar" src="https://img.shields.io/badge/Composer%20-%5E2.3.9-green"/>
</p>

## *:rocket: Instalasi*
#### :arrow_right: Clone Project / Download File
Clone Project dengan perintah terminal `gitbash` sebagai berikut:
```
git clone git@github.com:radhiant/laravel-inventoryweb.git
```
Atau bisa klik tombol download Zip dan extrak file tersebut
#### :arrow_right: Buat Database
Buat Database `db_inventoryweb`
#### :arrow_right: Config ENV
Ubah file dari `env.development` jadi `.env`

Setting `DB_DATABASE`, `DB_USERNAME`, `DB_PASSWORD` yang ada di file `.env` sesuai Nama Database mysql kalian

#### :arrow_right: Set Up
Buka Terminal di proyek folder Anda dan jalankan perintah dibawah ini:
```
composer install
```
```
php artisan storage:link
```
#### :arrow_right: Import Database
Import file database `db_inventoryweb.sql` yang ada di folder `database/db` ke phpmyadmin 

#### :arrow_right: Jalankan Aplikasi
```
php artisan serve
```
copy & paste `http://127.0.0.1:8000/` ke browser anda.

#### :arrow_right: Login Default
username: `superadmin` password: `12345678`
<br>
username: `admin` password: `12345678`
<br>
username: `operator` password: `12345678`
<br>
username: `manajer` password: `12345678`

## *:desktop_computer: Preview*
![Halaman Utama](https://github.com/user-attachments/assets/b8ca1d4a-abf1-42f9-a98b-66b8715816c5)
![Stock Barang](https://github.com/user-attachments/assets/677a0dde-7837-4655-9500-33227195b178)
![Jenis barang](https://github.com/user-attachments/assets/33e4be88-a7d1-44f7-9763-0d4a0987f266)
![Merk](https://github.com/user-attachments/assets/9eca5ba1-8f93-4442-82a0-40d223cd27a3)
![Satuan Barang](https://github.com/user-attachments/assets/daab9945-5800-4c08-89ad-d87b8f49e775)
![Costumer](https://github.com/user-attachments/assets/82913d53-210f-47fa-84f3-79d0ff29279e)
![Barang masuk](https://github.com/user-attachments/assets/a704ab6f-bc0d-4dba-96e2-43d5d48aa93f)
![Barang keluar](https://github.com/user-attachments/assets/a795cd99-df23-4fc9-977d-8d7b5fc2604a)


