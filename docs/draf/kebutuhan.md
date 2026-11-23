
# Kebutuhan Fungsional

| Kode | Kebutuhan | Prioritas |
|---|---|---|
| KF-01 | Sistem dapat memeriksa username dan kata sandi sebelum aplikasi digunakan, menentukan peran pengguna (Pemilik Kos atau Petugas), dan menutup aplikasi setelah 3 kali percobaan login gagal berturut-turut. | Tinggi |
| KF-02 | Sistem dapat menambah, mengubah, dan menghapus data kamar (nomor, tipe, tarif bulanan, status), serta menolak penghapusan kamar yang sedang ditempati. Fitur ini hanya untuk Pemilik Kos. | Tinggi |
| KF-03 | Sistem dapat mencari kamar berdasarkan nomor atau tipe dan menampilkan statusnya (Kosong atau Terisi). | Sedang |
| KF-04 | Sistem dapat menambah, mengubah, dan menghapus data penghuni (nama, nomor HP, asal, tanggal masuk), dan mengembalikan status kamar menjadi Kosong jika penghuni yang dihapus sedang menempati kamar. | Tinggi |
| KF-05 | Sistem dapat mencari penghuni berdasarkan nama atau nomor HP. | Sedang |
| KF-06 | Sistem dapat menempatkan penghuni ke kamar berstatus Kosong dan mengubah status kamar menjadi Terisi, serta menolak jika penghuni sudah menempati kamar lain. | Tinggi |
| KF-07 | Sistem dapat mencatat pembayaran sewa (penghuni, kamar, bulan tagihan, tanggal bayar), serta menolak pembayaran jika penghuni tidak menempati kamar tersebut atau bulan tagihan itu sudah dibayar. | Tinggi |
| KF-08 | Sistem dapat menghitung jumlah yang harus dibayar, yaitu tarif kamar ditambah denda Rp10.000 jika tanggal bayar melewati tanggal 10 pada bulan tagihan, serta menetapkan status pembayaran Tepat Waktu atau Terlambat. | Tinggi |
| KF-09 | Sistem dapat menampilkan laporan pembayaran (tanggal bayar, penghuni, kamar, bulan tagihan, jumlah, status) yang dapat disaring berdasarkan rentang tanggal dan status. | Tinggi |
| KF-10 | Sistem dapat menampilkan laporan pendapatan per bulan berupa jumlah pembayaran dan total pendapatan, serta hanya dapat dibuka oleh Pemilik Kos. | Sedang |
| KF-11 | Sistem dapat mengekspor laporan pembayaran ke file CSV. | Rendah |

# Kebutuhan Nonfungsional

| Kode | Kebutuhan |
|---|---|
| KNF-01 | Kata sandi disimpan sebagai hash, tidak dalam bentuk teks asli. |
| KNF-02 | Aplikasi berjalan di Windows dengan JDK 21 dan MySQL 8. |
| KNF-03 | Setiap kesalahan input ditampilkan dengan pesan yang menjelaskan cara memperbaikinya. |
| KNF-04 | Setiap penghapusan data didahului dialog konfirmasi yang menyebutkan data yang akan dihapus. |
