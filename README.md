# Jarkom-Modul-3-IT16-2023
- Tarisha Syira Mazaya Putri (5027211061)
- Evan Darya Kusuma (5027211069)

## Daftar Isi
- [Soal 0](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-0)
- [Soal 1](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-1)
- [Soal 2](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-2)
- [Soal 3](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-3)
- [Soal 4](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-4)
- [Soal 5](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-5)
- [Soal 6](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-6)
- [Soal 7](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-7)
- [Soal 8](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-8)
- [Soal 9](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-9)
- [Soal 10](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-10)
- [Soal 11](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-11)
- [Soal 12](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-12)
- [Soal 13](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-13)
- [Soal 14](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-14)
- [Soal 15](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-15)
- [Soal 16](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-16)
- [Soal 17](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-17)
- [Soal 18](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-18)
- [Soal 19](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-19)
- [Soal 20](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/tree/main#soal-20)

## Network Configurations
![image](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/fddd9bc4-91e5-4181-9f98-7e797f005785)
Pertama-tama, membuat konfigurasi sesuai dengan topologi yang sudah dibuat.

## Soal 1
(1) Lakukan konfigurasi sesuai dengan peta yang sudah diberikan.

- Aura
```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.241.1.1
	netmask 255.255.255.0

auto eth2
iface eth2 inet static
	address 192.241.2.1
	netmask 255.255.255.0

auto eth3
iface eth3 inet static
	address 192.241.3.1
	netmask 255.255.255.0

auto eth4
iface eth4 inet static
	address 192.241.4.1
	netmask 255.255.255.0
```
- Himmel
```
auto eth0
iface eth0 inet static
	address 192.241.1.2
	netmask 255.255.255.0
	gateway 192.241.1.1
```
- Heiter
```
auto eth0
iface eth0 inet static
	address 192.241.1.3
	netmask 255.255.255.0
	gateway 192.241.1.1
```
- Denken
```
auto eth0
iface eth0 inet static
	address 192.241.2.2
	netmask 255.255.255.0
	gateway 192.241.2.1
```
- Eisen
```
auto eth0
iface eth0 inet static
	address 192.241.2.3
	netmask 255.255.255.0
	gateway 192.241.2.1
```
- Frieren
```
auto eth0
iface eth0 inet static
	address 192.241.4.4
	netmask 255.255.255.0
	gateway 192.241.4.1
```
- Flamme
```
auto eth0
iface eth0 inet static
	address 192.241.4.5
	netmask 255.255.255.0
	gateway 192.241.4.1
```
- Frieren
```
auto eth0
iface eth0 inet static
	address 192.241.4.6
	netmask 255.255.255.0
	gateway 192.241.4.1
```
- Lawine
```
auto eth0
iface eth0 inet static
	address 192.241.3.5
	netmask 255.255.255.0
	gateway 192.241.3.1
```
- Lugner
```
auto eth0
iface eth0 inet static
	address 192.241.3.6
	netmask 255.255.255.0
	gateway 192.241.3.1
```
- Revolte
```
auto eth0
iface eth0 inet static
	address 192.241.3.2
	netmask 255.255.255.0
	gateway 192.241.3.1
```
- Ritcher
```
auto eth0
iface eth0 inet static
	address 192.241.3.3
	netmask 255.255.255.0
	gateway 192.241.3.1
```
- Sein
```
auto eth0
iface eth0 inet static
	address 192.241.4.2
	netmask 255.255.255.0
	gateway 192.241.4.1
```
- Stark
```
auto eth0
iface eth0 inet static
	address 192.241.4.3
	netmask 255.255.255.0
	gateway 192.241.4.1
```
## Soal 0
Setelah mengalahkan Demon King, perjalanan berlanjut. Kali ini, kalian diminta untuk melakukan register domain berupa riegel.canyon.yyy.com untuk worker Laravel dan granz.channel.yyy.com untuk worker PHP (0) mengarah pada worker yang memiliki IP [prefix IP].x.1.

Diperlukan instalasi bind9, pada DNS Server yaitu `Heiter`. Lalu, melakukan konfigurasi untuk meregistrasi domain riegel.canyon dan granz.channel pada `.bashrc`

```
apt-get update
apt-get install bind9 -y

echo '
zone "riegel.canyon.IT16.com" {
        type master;
        notify yes;
        file "/etc/bind/jarkom/riegel.canyon.IT16.com";
};

zone "granz.channel.IT16.com" {
    type master;
    notify yes;
    file "/etc/bind/jarkom/granz.channel.IT16.com";
};
' > /etc/bind/named.conf.local

mkdir /etc/bind/jarkom

cp /etc/bind/db.local /etc/bind/jarkom/riegel.canyon.IT16.com
cp /etc/bind/db.local /etc/bind/jarkom/granz.channel.IT16.com

echo '
;
; BIND data file for local loopback interface
;
$TTL    604800
@       IN      SOA     riegel.canyon.IT16.com. root.riegel.canyon.IT16.com. (
                              2         ; Serial
                         604800         ; Refresh
                          86400         ; Retry
                        2419200         ; Expire
                         604800 )       ; Negative Cache TTL
;
@       IN      NS      riegel.canyon.IT16.com.
@       IN      A       192.241.4.4 #frieren 
www     IN	    CNAME	  riegel.canyon.IT16.com.
' > /etc/bind/jarkom/riegel.canyon.IT16.com

echo '
;
; BIND data file for local loopback interface
;
$TTL    604800
@       IN      SOA     granz.channel.IT16.com. root.granz.channel.IT16.com. (
                              2         ; Serial
                         604800         ; Refresh
                          86400         ; Retry
                        2419200         ; Expire
                         604800 )       ; Negative Cache TTL
;
@       IN      NS      granz.channel.IT16.com.
@       IN      A       192.241.3.4 #lawiner 
www     IN	    CNAME	  granz.channel.IT16.com.
' > /etc/bind/jarkom/granz.channel.IT16.com

echo 'options {
      directory "/var/cache/bind";

      forwarders {
              192.168.122.1;
      };

      // dnssec-validation auto;
      allow-query{any;};
      auth-nxdomain no;    # conform to RFC1035
      listen-on-v6 { any; };
}; ' >/etc/bind/named.conf.options

service bind9 restart
```
## Output
(gambar)

## Soal 2
Client yang melalui Switch3 mendapatkan range IP dari [prefix IP].3.16 - [prefix IP].3.32 dan [prefix IP].3.64 - [prefix IP].3.80 (2)

Untuk mengerjakan soal ini, diperlukan konfigurasi DHCP Relay yaitu `Aura`. Berikut konfigurasinya.
```
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.241.0.0/16

apt-get update
apt-get install isc-dhcp-relay -y
service isc-dhcp-relay start

echo '
SERVERS="192.241.1.2"
INTERFACES="eth1 eth2 eth3 eth4"
OPTIONS=' > /etc/default/isc-dhcp-relay

echo 'net.ipv4.ip_forward=1' > /etc/sysctl.conf

service isc-dhcp-relay restart
```
Setelah itu, perlu dilakukan konfigurasi di DHCP Server yaitu `Himmel` untuk menetapkan range IP sesuai dengan permintaan soal.

```
echo 'nameserver 192.168.122.1' > /etc/resolv.conf

apt-get update
apt-get install isc-dhcp-server
dhcpd --version

echo 'INTERFACES="eth0"' > /etc/default/isc-dhcp-server

echo '
subnet '192.241.1.0' netmask '255.255.255.0' {
   
}

subnet '192.241.2.0' netmask '255.255.255.0' {
   
}

subnet '192.241.3.0' netmask '255.255.255.0' {
    range '192.241.3.16' '192.241.3.32';
    range '192.241.3.64' '192.241.3.80';
    option routers '192.241.3.1';
}
 ' > /etc/dhcp/dhcpd.conf

service isc-dhcp-server restart
service isc-dhcp-server status
```
## Output 
(gambar)

## Soal 3
Client yang melalui Switch4 mendapatkan range IP dari [prefix IP].4.12 - [prefix IP].4.20 dan [prefix IP].4.160 - [prefix IP].4.168

Seperti soal sebelumnya, perlu ditambahkan konfigurasi pada `Himmel` untuk menetapkan range IP.

```
echo 'nameserver 192.168.122.1' > /etc/resolv.conf

apt-get update
apt-get install isc-dhcp-server
dhcpd --version

echo 'INTERFACES="eth0"' > /etc/default/isc-dhcp-server

echo '
subnet '192.241.1.0' netmask '255.255.255.0' {
   
}

subnet '192.241.2.0' netmask '255.255.255.0' {
   
}

subnet '192.241.3.0' netmask '255.255.255.0' {
    range '192.241.3.16' '192.241.3.32';
    range '192.241.3.64' '192.241.3.80';
    option routers '192.241.3.1';
}

subnet '192.241.4.0' netmask '255.255.255.0' {
    range '192.241.4.12' '192.241.4.20';
    range '192.241.4.160' '192.241.4.168';
    option routers '192.241.4.1';
}
 ' > /etc/dhcp/dhcpd.conf

service isc-dhcp-server restart
service isc-dhcp-server status
```
## Output
(gambar)

## Soal 4
Client mendapatkan DNS dari Heiter dan dapat terhubung dengan internet melalui DNS tersebut.

Untuk menyelesaikan soal ini, perlu ditambahkan konfigurasi option domain-name-servers yang diarahkan ke IP Heiter. Berikut konfigurasinya:

```
echo '
subnet '192.241.1.0' netmask '255.255.255.0' {
   
}

subnet '192.241.2.0' netmask '255.255.255.0' {
   
}

subnet '192.241.3.0' netmask '255.255.255.0' {
    range '192.241.3.16' '192.241.3.32';
    range '192.241.3.64' '192.241.3.80';
    option routers '192.241.3.1';
    option domain-name-servers '192.241.1.3';
}

subnet '192.241.4.0' netmask '255.255.255.0' {
    range '192.241.4.12' '192.241.4.20';
    range '192.241.4.160' '192.241.4.168';
    option routers '192.241.4.1';
    option domain-name-servers '192.241.1.3';
}
 ' > /etc/dhcp/dhcpd.conf
```

## Soal 5
Lama waktu DHCP server meminjamkan alamat IP kepada Client yang melalui Switch3 selama 3 menit sedangkan pada client yang melalui Switch4 selama 12 menit. Dengan waktu maksimal dialokasikan untuk peminjaman alamat IP selama 96 menit.

Untuk menyelesaikan soal ini, perlu ditambahkan konfigurasi default-lease-time dan max-lease-time sesuai dengan soal. Berikut merupakan konfigurasinya:

```
echo '
subnet '192.241.1.0' netmask '255.255.255.0' {
   
}

subnet '192.241.2.0' netmask '255.255.255.0' {
   
}

subnet '192.241.3.0' netmask '255.255.255.0' {
    range '192.241.3.16' '192.241.3.32';
    range '192.241.3.64' '192.241.3.80';
    option routers '192.241.3.1';
    option domain-name-servers '192.241.1.3';
    default-lease-time '180';
    max-lease-time '5760';
}

subnet '192.241.4.0' netmask '255.255.255.0' {
    range '192.241.4.12' '192.241.4.20';
    range '192.241.4.160' '192.241.4.168';
    option routers '192.241.4.1';
    option domain-name-servers '192.241.1.3';
    default-lease-time '720';
    max-lease-time '5760';
}
 ' > /etc/dhcp/dhcpd.conf
```

## Output
(gambar)

## Soal 13
Semua data yang diperlukan, diatur pada Denken dan harus dapat diakses oleh Frieren, Flamme, dan Fern. (13)

Diperlukan instalasi mysql dan konfigurasi di Database Server yaitu, `Denken`.
```
apt-get update
apt-get install mariadb-server -y
service mysql start

echo "
[mysqld]
skip-networking=0
skip-bind-address
" > /etc/mysql/my.cnf

service mysql restart
```
Kemudian, jalankan command ini pada terminal `Denken`.
```
mysql -u root -p
pass : root

CREATE USER 'kelompokIT16'@'%' IDENTIFIED BY 'passwordIT16';
CREATE USER 'kelompokIT16'@'localhost' IDENTIFIED BY 'passwordIT16';
CREATE DATABASE dbkelompokIT16;
GRANT ALL PRIVILEGES ON *.* TO 'kelompokIT16'@'%';
GRANT ALL PRIVILEGES ON *.* TO 'kelompokIT16'@'localhost';
FLUSH PRIVILEGES;
```
Lalu, pada worker Laravel diperlukan instalasi berikut ini. 
```
apt-get update
apt-get install mariadb-client -y
```
Untuk melakukan pengecekan, gunakan command ini pada terminal laravel worker `Frieren`.
```
mariadb --host=192.241.2.2 --port=3306 --user=kelompokIT16 --password
```
```
SHOW DATABASES;
```
## Output
![WhatsApp Image 2023-11-15 at 7 07 19 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/112f9991-b72c-4fb2-9427-4f6d2fa77350)

## Soal 14
Frieren, Flamme, dan Fern memiliki Riegel Channel sesuai dengan quest guide berikut. Jangan lupa melakukan instalasi PHP8.0 dan Composer.

Untuk menyelesaikan soal ini, perlu melakukan beberapa instalasi pada Laravel Worker. Berikut langkah instalasinya:
```
apt-get update

apt-get install -y lsb-release ca-certificates apt-transport-https software-properties-common gnupg2
curl -sSLo /usr/share/keyrings/deb.sury.org-php.gpg https://packages.sury.org/php/apt.gpg
sh -c 'echo "deb [signed-by=/usr/share/keyrings/deb.sury.org-php.gpg] https://packages.sury.org/php/ $(lsb_release -sc) main" > /etc/apt/sources.list.d/php.list'

apt-get install php8.0-mbstring php8.0-xml php8.0-cli php8.0-common php8.0-intl php8.0-opcache php8.0-readline php8.0-mysql php8.0-fpm php8.0-curl unzip wget -y

apt-get install nginx -y
apt-get install lynx -y
apt-get install apache2-utils -y

apt-get install wget -y
wget https://getcomposer.org/download/2.0.13/composer.phar
chmod +x composer.phar
mv composer.phar /usr/bin/composer

apt-get install git -y
```
Selanjutnya, lakukan git clone pada repository yang telah diberikan.
```
git clone https://github.com/martuafernando/laravel-praktikum-jarkom.git
cd /var/www/laravel-praktikum-jarkom/
composer update
composer install
```
Lalu, perlu melakukan beberapa konfigurasi pada tiap worker sebagai berikut:
```
cp .env.example .env 

echo '
APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack
LOG_DEPRECATIONS_CHANNEL=null
LOG_LEVEL=debug

DB_CONNECTION=mysql
DB_HOST=192.241.2.2
DB_PORT=3306
DB_DATABASE=dbkelompokIT16
DB_USERNAME=kelompokIT16
DB_PASSWORD=passwordIT16

BROADCAST_DRIVER=log
CACHE_DRIVER=file
FILESYSTEM_DISK=local
QUEUE_CONNECTION=sync
SESSION_DRIVER=file
SESSION_LIFETIME=120

MEMCACHED_HOST=127.0.0.1

REDIS_HOST=127.0.0.1
REDIS_PASSWORD=null
REDIS_PORT=6379

MAIL_MAILER=smtp
MAIL_HOST=mailpit
MAIL_PORT=1025
MAIL_USERNAME=null
MAIL_PASSWORD=null
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"

AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=us-east-1
AWS_BUCKET=
AWS_USE_PATH_STYLE_ENDPOINT=false

PUSHER_APP_ID=
PUSHER_APP_KEY=
PUSHER_APP_SECRET=
PUSHER_HOST=
PUSHER_PORT=443
PUSHER_SCHEME=https
PUSHER_APP_CLUSTER=mt1

VITE_PUSHER_APP_KEY="${PUSHER_APP_KEY}"
VITE_PUSHER_HOST="${PUSHER_HOST}"
VITE_PUSHER_PORT="${PUSHER_PORT}"
VITE_PUSHER_SCHEME="${PUSHER_SCHEME}"
VITE_PUSHER_APP_CLUSTER="${PUSHER_APP_CLUSTER}"
' > /var/www/laravel-praktikum-jarkom/.env

cd /var/www/laravel-praktikum-jarkom && php artisan migrate:fresh
cd /var/www/laravel-praktikum-jarkom && php artisan db:seed --class=AiringsTableSeeder
cd /var/www/laravel-praktikum-jarkom && php artisan key:generate
cd /var/www/laravel-praktikum-jarkom && php artisan jwt:secret
cd /var/www/laravel-praktikum-jarkom && php artisan storage:link

chown -R www-data.www-data /var/www/laravel-praktikum-jarkom/storage
```
Selanjutnya lakukan konfigurasi nginx sebagai berikut pada masing-masing worker dimana port nya adalah sebagai berikut.
```
192.241.4.6:8001; # Fern 
192.241.4.5:8002; # Flamme
192.241.4.4:8003; # Frieren
```
Berikut konfigurasi nginxnya. Disini saya menggunakan port pada worker `Frieren`
```
echo 'server {
    listen 8003;

    root /var/www/laravel-praktikum-jarkom/public;

    index index.php index.html index.htm;
    server_name _;

    location / {
            try_files $uri $uri/ /index.php?$query_string;
    }

    # pass PHP scripts to FastCGI server
    location ~ \.php$ {
      include snippets/fastcgi-php.conf;
      fastcgi_pass unix:/var/run/php/php8.0-fpm.sock;
    }

    location ~ /\.ht {
            deny all;
    }

    error_log /var/log/nginx/implementasi_error.log;
    access_log /var/log/nginx/implementasi_access.log;
}' > /etc/nginx/sites-available/laravel-worker

ln -s /etc/nginx/sites-available/praktikum-jarkom /etc/nginx/sites-enabled/laravel-worker
service php8.0-fpm start
service nginx start
```
Selanjutnya, dilakukan testing pada masing-masing worker dengan command berikut:
```
lynx localhost:[port]
```

## Output
![WhatsApp Image 2023-11-18 at 2 16 32 AM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/34061c80-15a8-4c9c-bf2d-0ac48c6663c4)

## Soal 15
Riegel Channel memiliki beberapa endpoint yang harus ditesting sebanyak 100 request dengan 10 request/second. Lakukan testing pada endpoint POST /auth/register.

Untuk menyelesaikan soal ini, dilakukan testing menggunakan Apache Benchmark terhadap salah satu worker dan dilakukan di salah satu client. Sebagai contoh, testing akan dilakukan terhadap worker `Frieren` di client `Revolte`. Untuk melakukan testing, perlu melakukan instalasi dan membuat file body yang akan dikirimkan ke endpoint di client terlebih dahulu seperti berikut ini:
```
apt-get update
apt-get install lynx -y
apt-get install htop -y
apt-get install apache2-utils -y
apt-get install jq -y

echo '
{
  "username": "kelompokIT16",
  "password": "passwordIT16"
}' > register.json
```
Lalu, lakukanlah perintah berikut dari sisi client Revolte
```
ab -n 100 -c 10 -p register.json -T application/json http://192.241.4.4:8003/api/auth/register
```
## Output
![WhatsApp Image 2023-11-18 at 2 54 10 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/c7c1e2ba-222e-49f4-94ec-10553f52a0de)

## Soal 16
Lakukan testing pada endpoint POST /auth/register

Seperti soal sebelumnya, perlu membuat file body terlebih dahulu yang akan dikirim pada endpoint /api/auth/login sebagai berikut:
```
echo '
{
  "username": "kelompokIT16",
  "password": "passwordIT16"
}' > login.json
```
Lalu, lakukanlah perintah berikut dari sisi client Revolte
```
ab -n 100 -c 10 -p login.json -T application/json http://192.241.4.4:8003/api/auth/login
```
## Output
![WhatsApp Image 2023-11-18 at 3 06 59 PM (1)](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/d9c27fb6-d0bf-4cba-a41e-3ae76c258fae)

## Soal 17
Lakukan testing pada endpoint GET /me

Diperlukan melakukan testing menggunakan Apache Benchmark pada salah satu worker saja. Disini kami akan menggunakan worker laravel `Frieren` yang nantinya akan menjadi worker yang akan ditesting oleh client `Revolte`. Sebelum dilakukan testing. Ada beberapa konfigurasi yang harus disiapkan sebagai berikut:

Dapatkan tokennya terlebih dahulu sebelum mengakses endpoint /api/me
```
curl -X POST -H "Content-Type: application/json" -d @login.json http://192.241.4.4:8003/api/auth/login > login_output.txt
token=$(cat login_output.txt | jq -r '.token')
```
Untuk melihat token, jalankan command berikut
```
cat login_output.txt
```
![WhatsApp Image 2023-11-18 at 3 13 21 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/861ae129-e96c-4eea-b03b-9025d40921be)

Selanjutnya, jalankan command berikut untuk melakukan testing di client:
```
ab -n 100 -c 10 -H "Authorization: Bearer $token" http://192.241.4.4:8003/api/me
```

## Output
![WhatsApp Image 2023-11-18 at 3 17 59 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/63da7292-b2ec-4e0f-bd0f-6aa0feeb248d)

## Soal 18
Untuk memastikan ketiganya bekerja sama secara adil untuk mengatur Riegel Channel maka implementasikan Proxy Bind pada Eisen untuk mengaitkan IP dari Frieren, Flamme, dan Fern.

Untuk menyelesaikan soal ini, perlu dilakukan konfigurasi nginx pada Load Balancer yaitu Eisen. Berikut konfigurasinya:
```
echo 'nameserver 192.241.1.3' > /etc/resolv.conf
apt-get update
apt-get install apache2-utils -y
apt-get install nginx -y
apt-get install lynx -y

echo 'upstream worker {
    server 192.241.4.6:8001;
    server 192.241.4.5:8002;
    server 192.241.4.4:8003;
}

server {
    listen 80;
    server_name riegel.canyon.IT16.com www.riegel.canyon.IT16.com;

    location / {
        proxy_pass http://worker;
    }
} 
' > /etc/nginx/sites-available/laravel-worker

ln -s /etc/nginx/sites-available/laravel-worker /etc/nginx/sites-enabled/laravel-worker

service nginx restart

service nginx start
```
Selanjutnya pada DNS Server atau Heiter, perlu dilakukan perubahan sedikit yaitu mengganti IP pada domain server riegel.canyon.it21.com menjadi IP Eisen. Berikut konfigurasinya:

```
echo '
;
; BIND data file for local loopback interface
;
$TTL    604800
@       IN      SOA     riegel.canyon.IT16.com. root.riegel.canyon.IT16.com. (
                              2         ; Serial
                         604800         ; Refresh
                          86400         ; Retry
                        2419200         ; Expire
                         604800 )       ; Negative Cache TTL
;
@       IN      NS      riegel.canyon.IT16.com.
@       IN      A       192.241.2.3 #eisen 
www     IN	    CNAME	  riegel.canyon.IT16.com.
' > /etc/bind/jarkom/riegel.canyon.IT16.com
```
Selanjutnya, dilakukan testing pada salah satu client yaitu `Revolte` dengan command berikut:
```
ab -n 100 -c 10 -p login.json -T application/json http://www.riegel.canyon.IT16.com/api/auth/login
```
## Output
![WhatsApp Image 2023-11-18 at 4 35 32 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/bfe3c008-fb90-4c94-95be-728a2cd103a9)

![WhatsApp Image 2023-11-18 at 4 39 19 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/a61a5e46-ad21-48e4-85e8-cee7c2c53f3e)

## Soal 19
Untuk meningkatkan performa dari Worker, coba implementasikan PHP-FPM pada Frieren, Flamme, dan Fern. Untuk testing kinerja naikkan 
- pm.max_children
- pm.start_servers
- pm.min_spare_servers
- pm.max_spare_servers
sebanyak tiga percobaan dan lakukan testing sebanyak 100 request dengan 10 request/second kemudian berikan hasil analisisnya pada Grimoire. 

Untuk menyelesaikan soal ini, dilakukan empat percobaan konfigurasi PHP-FPM yaitu, percobaan awal sesuai dengan setup awal, dan tiga percobaan lainnya. Berikut merupakaan keempat konfigurasi yang kami coba di worker:

Script 1
```
echo '[www]
user = www-data
group = www-data
listen = /run/php/php8.0-fpm.sock
listen.owner = www-data
listen.group = www-data
php_admin_value[disable_functions] = exec,passthru,shell_exec,system
php_admin_flag[allow_url_fopen] = off

; Choose how the process manager will control the number of child processes.

pm = dynamic
pm.max_children = 5
pm.start_servers = 2
pm.min_spare_servers = 1
pm.max_spare_servers = 3' > /etc/php/8.0/fpm/pool.d/www.conf

service php8.0-fpm restart
```
Script 2
```
echo '[www]
user = www-data
group = www-data
listen = /run/php/php8.0-fpm.sock
listen.owner = www-data
listen.group = www-data
php_admin_value[disable_functions] = exec,passthru,shell_exec,system
php_admin_flag[allow_url_fopen] = off

; Choose how the process manager will control the number of child processes.

pm = dynamic
pm.max_children = 25
pm.start_servers = 5
pm.min_spare_servers = 3
pm.max_spare_servers = 10' > /etc/php/8.0/fpm/pool.d/www.conf

service php8.0-fpm restart
```
Script 3
```
echo '[www]
user = www-data
group = www-data
listen = /run/php/php8.0-fpm.sock
listen.owner = www-data
listen.group = www-data
php_admin_value[disable_functions] = exec,passthru,shell_exec,system
php_admin_flag[allow_url_fopen] = off

; Choose how the process manager will control the number of child processes.

pm = dynamic
pm.max_children = 50
pm.start_servers = 8
pm.min_spare_servers = 5
pm.max_spare_servers = 15' > /etc/php/8.0/fpm/pool.d/www.conf

service php8.0-fpm restart
```
Script 4
```
echo '[www]
user = www-data
group = www-data
listen = /run/php/php8.0-fpm.sock
listen.owner = www-data
listen.group = www-data
php_admin_value[disable_functions] = exec,passthru,shell_exec,system
php_admin_flag[allow_url_fopen] = off

; Choose how the process manager will control the number of child processes.

pm = dynamic
pm.max_children = 75
pm.start_servers = 10
pm.min_spare_servers = 5
pm.max_spare_servers = 20' > /etc/php/8.0/fpm/pool.d/www.conf

service php8.0-fpm restart
```

## Output
Script 1
![WhatsApp Image 2023-11-18 at 5 18 18 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/98df34db-4c89-49d9-8f57-355797221d2f)

Script 2
![WhatsApp Image 2023-11-18 at 5 21 14 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/5e45609e-f9ac-4b8d-bd9b-c369dc215211)

Script 3
![WhatsApp Image 2023-11-18 at 5 23 55 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/dfa0d427-5464-4a7c-931d-c6aecad594ad)

Script 4
![WhatsApp Image 2023-11-18 at 5 27 00 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/37b3b098-3f1d-42fa-bfa1-d2b396a663fa)

## Soal 20
Nampaknya hanya menggunakan PHP-FPM tidak cukup untuk meningkatkan performa dari worker maka implementasikan Least-Conn pada Eisen. Untuk testing kinerja dari worker tersebut dilakukan sebanyak 100 request dengan 10 request/second.

Untuk menyelesaikan soal ini, dilakukan penambahan konfigurasi least_conn di Eisen. Berikut konfigurasinya:
```
echo '
    upstream worker {
    least_conn;
    server 192.241.4.6:8001;
    server 192.241.4.5:8002;
    server 192.241.4.4:8003;
}

server {
    listen 80;
    server_name riegel.canyon.IT16.com www.riegel.canyon.IT16.com;

    location / {
        proxy_pass http://worker;
    }
} 
' > /etc/nginx/sites-available/laravel-worker
service nginx restart
```
Konfigurasi PHP-FM yang digunakan adalah konfigurasi percobaan script ketiga.

Selanjutnya, dilakukan testing di client menggunakan command berikut:
```
ab -n 100 -c 10 -p login.json -T application/json http://www.riegel.canyon.IT16.com/api/auth/login
```

## Output
![WhatsApp Image 2023-11-18 at 5 29 19 PM](https://github.com/tarishaicha/Jarkom-Modul-3-IT16-2023/assets/107459188/bbcc11d8-4d2b-4d1f-b47f-98d8f54d42d8)



