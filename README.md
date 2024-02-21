# Multi-PHP-Docker-Compose

## Cara Setup
1. Buat folder data
2. Copy .env.example ke .env
3. Sesuaikan .env
4. Jalankan docker compose up -d --build untuk menjalankan semua service atau docker-compose up -d --build php-7.4 untuk menjalankan 1 service (ganti php-7.4 sesuai versi yang ingin digunakan)


## Info
![image](https://github.com/chandika7d/Multi-PHP-Docker-Compose/assets/20274245/d1e029e2-e5a6-4339-842b-506ece3c85fb)
Start versi php yang diinginkan, service php tidak bisa dijalankan bersamaan. Jika ingin dijalankan bersamaan ganti port tiap service di file docker-compose.yml
