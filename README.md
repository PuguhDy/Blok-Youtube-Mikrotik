# Blok-Youtube-Mikrotik
Blok Youtube Via Mikrotik

#bisa cek panduan disitu, sudah cukup jelas
 ## untuk allow satu IP bisa akses ke youtube bisa dengan cara berikut
 1. firewall > nat > chain (forward) > src addres (IP Lokal yang ingin akses)
 2. action > accept
 3. done
