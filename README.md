## Test Your Laravel Routing Skills

Repositori ini adalah test bagi Anda: 
    isi `routes/web.php` dan `routes/api.php` yang sengaja dikosongkan.

Di kedua file tersebut, Anda akan menemukan komentar yang menjelaskan 12 tugas. Untuk sebagian besar tugas, Anda perlu menulis SATU baris kode.

Contoh:

```
// Task 2: point the GET URL "/user/[name]" to the UserController method "show"
// It doesn't use Route Model Binding, it expects $name as a parameter
// Put one code line here below
```

Untuk menguji apakah semua rute berfungsi dengan benar, ada pengujian PHPUnit di file `tests/Feature/RoutesTest.php`.

Pada awalnya, jika Anda menjalankan `php artisan test`, atau `vendor/bin/phpunit`, kedelapan pengujian tersebut gagal.
Tugas Anda adalah membuat ujian tersebut lulus.


## How to Submit Your Solution

Silalakan clone repository ini. Setelah anda menyelesaikan tes, lakukan push ke branch `main`.
Ini akan secara otomatis menjalankan tes melalui Github Actions dan yang menunjukkan jika tes tersebut lulus.

