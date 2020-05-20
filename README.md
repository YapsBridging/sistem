# APA ITU YBS-SISTEM ?

Ybs-system merupakan sebuah minimum sistem 
yang umumnya di miliki oleh sebuah aplikasi, 
dan terpasang pada sebuah template admin.

Ybs-sistem saat ini terpasang hanya 
pada template admin tabler yang telah dimodifikasi...

Buat teman teman yang ga mau pusing lagi masalah
* [sistem login]
* [hak akses pengguna/level konfigurasi]
* [user konfigurasi]
* [reset password]
* [Menu Management]
* [Upload File]
* [First Page Loading]
* [Combobox Chained/link]
* [Notifikasi ke telegram]

tapi tetap masih mau NGODING..

## ayoo buruan pakai YBS Sistem..

adapun fitur-fitur yang di sediakan
antara lain :
* [sistem login]
* [hak akses pengguna/level konfigurasi]
* [user konfigurasi]
* [reset password]
* [First Page Loading]
* [Menu Management]
* [Menu Page Maintenance]
* [Bot Manager -Telegram]

tools tambahan :
* [CRUD Generator]
* [Dropzone Upload File]
* [Combobox Link]

element html :
* [Element : Default  Template Tabler]
* [Element : Panel Style Admin LTE 3]
* [Element : Button App Style Admin LTE 3]
* [Element : Grafik Chart JS]
* [Element : Panel Bootstrap]
* [Element : Widget Counter Admin Lte]


kini anda tidak perlu lagi membangun aplikasi dari awal

YBS Sistem juga dapat melakukan pembatasan akses terhadap menu-menu,

Menu pada setiap level user dapat berbeda beda sesuai dengan akses yang di berikan.

### note :
perlu di perhatikan YBS System bukan sebuah plugin/Library yang dapat di pasang pada template-template lain..
saat ini YBS system terpasang pada template tabler yang telah di modifikasi, namun jika anda ingin menggunakan pada template lain maka tidak ada larangan.

YBS Sistem juga menyediakan data-login seperti :
_user_id
_user_name
_user_picture
_user_level_id
_user_level_name
_user_form_id
_user_form_code
_user_form_name
_user_form_shortcut
_is_dashboard
_token

sehingga anda tidak perlu melakukan query lagi,
cukup mengunakan perintah $this..(lihat menu pada dokumentasi).

Ybs Sistem juga dilengkapi dengan YBS CRUD Generator,
membuat semuanya semakin mudah..

YBS CRUD Generator Memiliki Beberapa Kelebihan antara lain :

### Table join
memungkinkan melakukan join table dengan tingkat kedalaman join yang di inginkan. 
sehingga anda tidak perlu pusing membuat query join.

### Options Crud private / public.
private : data yang di input hanya dapat di Lihat,update,delete oleh user yang melakukan input.
public  : data yang di input dapat di lihat,update,delete oleh semua user yang memiliki otorisasi yang sama.

### Validasi Data Double or empty pada Form Create-Update
anda tidak perlu lagi repot melakukan coding validasi untuk data double or kosong,
karena code nya sdh terbentuk otomasi pada File Controller.

### Konfigurasi File hasil Generate
Konfigurasi File hasil Generate seperti file list,file create-update,terletak dlm sebuah file config 
sehingga memudahkan saat ada perubahan title atau content table list,atau perubahan form input create-update.

Pilihan Generate Type Input Untuk Form Create-Update,seperti Type :
* [Text (All) untuk  input semua karakter]
* [Text (A-Z) hanya untuk alfabelt tanpa spasi]
* [Text (0-9) hanya untuk number  tanpa spasi]
* [Text (A-Z,0-9) hanya untuk alfabeth dan number tanpa spasi]
* [Text Password]
* [ComboBox    *menampilkan isi table field lain, konfigurasi pada file config]
* [Date  menampilkan input date]


Project ini dibangun menggunakan :
Template tabler
framework CodeIgniter Version 3.1.9
database Mysqli
php 7.1.10.
Bootstrap 3.


### YBS SISTEM Update 1.0.11 Feb 2020
* [sistem login]
* [hak akses pengguna/level konfigurasi]
* [user konfigurasi]
* [reset password]
* [Menu Management]
* [Upload File]
* [First Page Loading]
* [Combobox Chained/link]
* [Notifikasi ke telegram]


