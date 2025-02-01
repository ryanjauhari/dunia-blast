# dunia-blast
Program ini adalah broadcast forwading, di butuhkan database pelanggan agar dapat melakukan pengiriman pesan massal 25 pesan perdetik.
Menggunakan mekanisme asyncronous processing, hanya berfokus pada pendistribusian pesan tidak berfokus pada pengelolaan apakah pengiriman berhasil atau tidak.
Hanya gunakan codebase ini jika kamu paham alur program nya.

Di buat terpisah untuk menghindari crash/keberatan pada server utama, dapat di jalankan pada server terpisah. Sehingga program bisa berjalan dengan skalabilitas yang tinggi.
