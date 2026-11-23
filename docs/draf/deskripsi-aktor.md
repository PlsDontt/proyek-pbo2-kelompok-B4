<!-- Draf T1. Sesuaikan dengan kondisi nyata kos yang disepakati kelompok. -->

# Deskripsi Masalah

Pengelolaan kos-kosan skala kecil sampai menengah umumnya masih dilakukan secara manual, misalnya dengan buku catatan atau lembar Excel yang terpisah untuk data kamar, data penghuni, dan pembayaran sewa. Cara ini menyulitkan pengelola untuk mengetahui kamar mana yang masih kosong, siapa yang menempati kamar tertentu, dan penghuni mana yang belum atau terlambat membayar. Perhitungan denda keterlambatan dan rekap pendapatan bulanan juga harus dihitung ulang setiap kali dibutuhkan, sehingga memakan waktu dan berisiko salah hitung.

Aplikasi desktop ini dibuat agar Pemilik Kos dan Petugas dapat mencatat data kamar dan penghuni, menempatkan penghuni ke kamar yang kosong, mencatat pembayaran sewa beserta dendanya, serta melihat laporan pembayaran dan pendapatan bulanan dalam satu aplikasi. Seluruh data disimpan di database sehingga lebih rapi, mudah dicari, dan dapat dilaporkan kapan saja.

# Aktor

| Aktor | Tugas | Hak akses |
|---|---|---|
| Pemilik Kos | Mengelola data kamar dan tarif sewa, mengelola data penghuni, menempatkan penghuni, mencatat pembayaran, serta memantau laporan pembayaran dan pendapatan bulanan | Akses penuh ke seluruh fitur, termasuk mengubah data kamar dan tarif serta melihat laporan pendapatan bulanan |
| Petugas | Mengelola data penghuni, menempatkan penghuni ke kamar yang kosong, mencatat pembayaran sewa, dan melihat laporan pembayaran | Tidak dapat menambah, mengubah, atau menghapus data kamar dan tarif, dan tidak dapat melihat laporan pendapatan bulanan |

Penghuni kos bukan aktor karena tidak menggunakan aplikasi. Data penghuni hanya dicatat oleh Pemilik Kos atau Petugas.
