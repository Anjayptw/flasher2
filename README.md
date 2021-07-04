# Cara Penggunaan
Untuk user windows dan linux, download file executable di [release](https://github.com/bro-11/flasher2/releases/tag/1.0.0-beta)\
download sesuai OS yang anda pakai.

### Windows
Silahkan buka cmd di folder dimana anda mendownload file executable tadi.\
setelah itu login dengan mengetikkan perintah berikut:
```
flasher2 login
```
Jika sudah selesai login, bisa langsung jalankan botnya dengan double klik di file executablenya atau ketik `flasher2` di cmd.

### Linux
Login dengan perintah berikut:
```
./flasher2 login
```
lalu jalankan botnya dengan perintah:
```
./flasher2
```
gak paham? gausah make linux.

### Android (Termux)
Jika belum download termux di play store, silahkan download terlebih dahulu.

install `wget` dan `proot`
```
pkg install wget
```
lalu download release versi androidnya:
```
wget -O https://github.com/bro-11/flasher2/releases/download/1.0.0-beta/flasher2-android
chmod +x flasher2-android
```
login dengan perintah berikut:
```
./flasher2-android login
```
jalankan botnya:
```
./flasher2-android
```
Note: Jalankan `termux-chroot` setiap kali akan menjalankan bot ini di termux
# Bug?
Boleh laporin bug ke telegram saya [<img src="https://img.shields.io/badge/telegram-bro12221-blue?style=flat&logo=telegram">](https://t.me/bro12221) atau bisa bikin issue
