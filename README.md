![alt text](https://c.top4top.io/p_3568metp21.png?raw=true)

Ini adalah kode Domain Checker atau Website Status Checker yang ditulis dalam Python

⚙️ Fitur-Fitur Kode Ini :
🧵 Multithreading
Menggunakan banyak thread (default: 50) untuk mempercepat proses pengecekan.

Setiap thread akan mengecek domain satu per satu dari antrean.

📄 Input dari File
Membaca daftar domain dari file list.txt

🌐 Cek Status Domain
Coba akses domain menggunakan https dan fallback ke http jika gagal SSL.

Gunakan requests dengan custom User-Agent agar lebih mirip browser sungguhan.

📊 Progress Bar dan Statistik
Tampilkan progres checking dalam bentuk jumlah & persentase.

Setelah semua selesai, tampilkan summary:
- Total domain
- Jumlah live dan dead
- Waktu eksekusi dan kecepatan

💾 Simpan Hasil
Tulis hasil ke dua file:

live.txt ➡️ untuk domain yang aktif

dead.txt ➡️ untuk domain yang tidak aktif

🚀 Keunggulan:

✅ Cepat karena multi-threading

✅ Robust dengan error handling yang baik

✅ User-friendly dengan interface berwarna

✅ Efisien memory dengan iterator

✅ Flexible timeout dan thread count

🔐 Catatan:
Tidak mengecek apakah domain tersebut expired secara WHOIS — hanya cek apakah bisa diakses.

Tidak mengikuti robots.txt atau pengecekan etis lainnya.
