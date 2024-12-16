# Rangkuman Telat Presensi - Network Layer Protocol (oleh Kelompok 7)

### IPv6
IPv6 adalah solusi dari keterbatasan IPv4, dikarenakan dalam hal jumlah alamat yang tersedia. Dengan format alamat 128-bit, IPv6 menyediakan ruang alamat yang lebih luas dan efisiensi jaringan yang lebih baik melalui struktur header yang lebih sederhana. Beberapa fitur utama IPv6 meliputi:
- **Autokonfigurasi**: Menggunakan SLAAC untuk pengaturan otomatis perangkat.
- **Protokol Routing**: Dukungan untuk RIPng, OSPFv3, dan BGP4+.
- **Mekanisme Transisi**: Dual Stack, Tunneling, dan NAT-PT untuk kompatibilitas dengan IPv4.

### ICMP
ICMP (Internet Control Message Protocol) adalah protokol yang berfungsi untuk melaporkan kesalahan dan melakukan diagnostik jaringan. Beberapa aplikasi penting ICMP meliputi:
- **Ping**: Untuk memeriksa konektivitas perangkat dalam jaringan.
- **Traceroute**: Untuk melacak rute pengiriman paket.
- **Pesan Kesalahan**: Memberitahukan masalah seperti host tidak dapat dijangkau atau TTL habis.

### ARP dan RARP
- **ARP (Address Resolution Protocol)**: Menerjemahkan alamat IP menjadi alamat MAC untuk komunikasi dalam jaringan.
- **RARP (Reverse ARP)**: Sebaliknya, menerjemahkan alamat MAC menjadi alamat IP, biasanya untuk perangkat tanpa IP tetap.

### IGMP
IGMP (Internet Group Management Protocol) digunakan untuk komunikasi multicast, memungkinkan beberapa perangkat berbagi satu alamat IP untuk menerima data yang sama. Protokol ini membantu mengoptimalkan sumber daya jaringan dalam komunikasi grup.

### Protokol Routing
Protokol routing bertanggung jawab untuk mengatur pergerakan data antar jaringan:
- **Static Routing**: Jalur ditentukan secara manual, aman, namun kurang fleksibel untuk jaringan besar.
- **Dynamic Routing**: Menggunakan algoritma seperti Distance Vector (RIP) dan Link State (OSPF) untuk menemukan jalur terbaik secara otomatis.
- **Hybrid Routing**: Menggabungkan kekuatan Static dan Dynamic Routing, seperti pada EIGRP.

