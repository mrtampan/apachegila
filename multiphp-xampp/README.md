## intruksi

SETTING EXTENSION PHP XAMPP
1. Buka folder C:/xampp/php/NAMA-FOLDER-VERSI-PHP (PHP5_6_40 / PHP7_4_13, dll)
2. Ubah format file php.ini.production menjadi php.ini
3. Aktifkan extension default dibawah dengan cara menghapus komentar yang ditandai tanda ;
4. Contoh ; extension_dir ubah menjadi extension_dir
- extension_dir
- extension=bz2
- extension=curl
- extension=ftp
- extension=fileinfo
- extension=gd2
- extension=gettext
- extension=gmp
- extension=intl
- extension=mbstring
- extension=exif
- extension=mysqli
- extension=openssl
- extension=pdo_mysql
- extension=pdo_sqlite
- extension=php_sqlite3


SETTING APACHE XAMPP
1. Klik config, pilih httpd-xampp.conf
2. Paste script config-httpd.txt dibagian paling bawah,
3. Gunakan listen port yang belum terpakai di PC, cek di CMD, ketik netstat -aon
4. Masukkan port yang belum terpakai di settingan httpd-xampp.conf pada masing-masing config versi php.
5. Simpan


## Tutorial

https://youtu.be/uTmsY9A80PI
