# Membuat-Migration-dan-Controler
Menggunakan Firmwork Laravel
Download composer dengan perintah "composer create-project laravel/laravel=^9.0" universitas"
Buat folder baru bernama "bootstrap.min.css" di dalam folder "public".
Kemudian input/copy paste file "bootstrap.min.css" ke dalam folder "public" => "css" => "bootstrap.min.css"
Buat file baru dengan cara mengetikan perintah = "php artisan make:migration create_mahasiswas_table --create=mahasiswas"
Copy paste file "create_mahasiswas_table.php" ke folder "database" => "migration"
Buka dari cmd kemudian run administrator ketik perintah cd C:\xampp\htdocs\universitas
Ketikkan perintah = php artisan migrate:reset
Ketikkan perintah = php artisan migrate:fresh
Jalankan perintah = php artisan migrate
Buat folder baru bernama "css" di folder "public".
Buat File baru di folder controllers dengan cara mengetikkan perintah = php artisan meke:controller MahasiswaController
Copy paste file "MahasiswaController" ke folder App => Http => Controllers => MahasiswaControler
Jalankan php artisan serve
Buka di browser web seperti Edge atau google Crome dengan cara mengetikkan perintah: localhost:8000
