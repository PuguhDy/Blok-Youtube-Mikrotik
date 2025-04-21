# Blok-Youtube-Mikrotik
Blok Youtube Via Mikrotik

bisa cek panduan disitu, sudah cukup jelas
 ## untuk allow satu IP bisa akses ke youtube bisa dengan cara berikut
 1. firewall > nat > chain (forward) > src addres (IP Lokal yang ingin akses)
 2. action > accept
 3. done

### untuk menjalankan diatas harus urutan firewall di pertama, firewall paling atas akan di ekse dulu
# contoh 
 ![Alt text](https://github.com/PuguhDy/Blok-Youtube-Mikrotik/blob/main/firewall.jpg)

 # akses youtube akan loading tidak terbuka
 ![Alt text](https://github.com/PuguhDy/Blok-Youtube-Mikrotik/blob/main/akses%20%20youtube.jpg)
