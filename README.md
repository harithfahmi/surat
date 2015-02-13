# Aplikasi persuratan

Tampilan aplikasi :

- Daftar surat

![preview](https://github.com/agussudarmanto/surat/blob/master/preview.jpg)

- Entri surat masuk

![entridata](https://github.com/agussudarmanto/surat/blob/master/entridata.jpg)

Cara instalasi :

1. copy folder surat ke direktori web server anda mis: ke `htdocs` atau ke `www`
2. buka `phpmyadmin` dan load file `database.sql` ke database server anda (database otomatis dibuat dengan nama `surat`
3. ubah file `index.php`, ganti variable `DB_USER` `DB_PASSWORD` `DB_NAME` sesuaikan dengan database anda
```php
define("DB_SERVER" , "localhost");
define("DB_USER" , "surat");
define("DB_PASSWORD", "surat");
define("DB_NAME" , "surat");
define("BASEPATH" , "http://localhost/surat/");
define("APPS_PARAM_IDX" , 2);
define("MODULE_PARAM_IDX" , 3);
define("ACTION_PARAM_IDX" , 4);
```

Setelah selesai buka internet browser anda dan kunjungi halaman aplikasi `http://localhost/surat/`
```
login : admin
password : 12345
```
Silahkan dimodifikasi sesuai kebutuhan anda.