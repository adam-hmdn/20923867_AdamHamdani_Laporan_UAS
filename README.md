Halaman Login ada 2 :
1. Admin 
   - username : Adam
   - password : hakko
2. Constummer
   - username : adam
   - password : adam

(di file conn.php)
<?php
$db_host = "localhost";
$db_user = "root";
$db_pass = "qwerty123"; // Bisa diganti sesuai password database masing-masing, Kalo tidak di password maka kosongkan saja.
$db_name = "warnasol";

$koneksi = mysqli_connect($db_host, $db_user, $db_pass, $db_name);