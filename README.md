# Multi-PHP-Docker-Compose

## Cara Setup
1. Buat folder data
2. Copy .env.example ke .env
3. Sesuaikan .env
4. Jalankan ```docker-compose -p "web-service" up -d --build``` untuk menjalankan semua service
5. atau jalankan ```docker-compose -p "web-service" up -d --build php-7.4``` untuk menjalankan 1 service (ganti php-7.4 sesuai versi yang ingin digunakan)

## ENV
1. UID : ID User
2. GID : ID Group
3. MYSQL_ROOT_PASSWORD : Password Root MariaDB
4. MYSQL_USER : Username MariaDB
5. MYSQL_PASSWORD : Password untuk user dengan username diatas
6. PROJECT_FOLDER : Lokasi folder project php (sama kaya htdocs)


## Info
1. Jika terjadi error seperti dibawah itu normal, karena port disetting sama.
![image](https://github.com/chandika7d/Multi-PHP-Docker-Compose/assets/20274245/9ed0c333-8746-42ac-bc6b-20db9c1c1f11)

2. Start versi php yang diinginkan, service php tidak bisa dijalankan bersamaan karena portnya sama. Jika ingin dijalankan bersamaan ganti port tiap service di file docker-compose.yml
![image](https://github.com/chandika7d/Multi-PHP-Docker-Compose/assets/20274245/d1e029e2-e5a6-4339-842b-506ece3c85fb)
