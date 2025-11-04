## Hasil Pengujian Ping Gagal

![Ping Gagal](Screenshot%202025-11-05%20003957.png)


### Penjelasan
Ping pada gambar di atas gagal karena tidak ada jalur komunikasi yang menghubungkan perangkat pengirim dan penerima pada lapisan jaringan (Layer 3). Hal ini biasanya terjadi karena router yang berfungsi sebagai penghubung antar subnet belum dikonfigurasi.Akibatnya, paket ICMP yang dikirim oleh PC tidak dapat diteruskan ke alamat tujuan 192.168.0.3.

## Hasil Pengujian Ping Berhasil
![Ping Gagal](Screenshot%202025-11-05%20004014.png)

### Penjelasan
Pada percobaan kedua, seluruh paket ping berhasil diterima tanpa kehilangan data (0% loss), yang menandakan bahwa router telah berfungsi dengan baik dalam melakukan routing antar subnet. Selain itu, switch Cisco 2960 secara otomatis mengaktifkan antarmuka yang terhubung ke perangkat, sehingga komunikasi antar perangkat di jaringan berjalan lancar. Hasil ini menunjukkan bahwa konfigurasi jaringan sudah benar dan komunikasi antar perangkat pada subnet yang berbeda dapat dilakukan dengan sukses


### link youtube
https://youtu.be/SInsB57xDRA
