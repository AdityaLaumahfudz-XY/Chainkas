Chain-Kas 

Chain-Kas adalah aplikasi manajemen keuangan kelas berbasis Web yang menggabungkan kecepatan Real-time Database dengan keamanan integritas data menggunakan Logika Blockchain berbasis JavaScript.

Project ini dibuat untuk Lomba FESTIKA JATIM 2025

👥 Tim BLOKAS - SMAN 2 Kota Probolinggo
1. Aditya Laumahfudz Isabel** (Developer)
2. Muhammad Danish Pujotomo** (Analyst/Presenter)


#Fitur Unggulan

1. Transparansi Real-time 
Menggunakan Google Firebase, data yang diinput Bendahara akan muncul di layar Wali Kelas dan Siswa dalam hitungan milidetik tanpa perlu refresh halaman.

2. Blockchain Logic & Hashing 
Setiap transaksi dikunci dengan kode kriptografi (Hash) yang saling terhubung (Chaining).
Rumus: `Hash = SHA(PrevHash + Nama + Nominal)`Ini menjamin urutan data tidak bisa diubah.

3. Tamper-Evidence (Anti-Manipulasi) 🚨
Fitur keamanan utama kami. Jika ada seseorang (hacker/admin nakal) yang mencoba mengubah nominal uang langsung dari Database (Backend), sistem akan otomatis mendeteksi ketidakcocokan Hash.
Efek: Baris data akan berubah menjadi warna merah dan muncul peringatan "DATA PALSU!".

4. Bukti Foto Digital 
Bendahara wajib mengunggah foto fisik uang saat input data. Foto dikonversi menjadi Base64 agar tersimpan aman di dalam rantai blok.

---
Teknologi yang Digunakan
Frontend: HTML5, CSS3, Bootstrap 5.3
Logic: Vanilla JavaScript
Database:Firebase Realtime Database (NoSQL)
Architecture:Client-Side Rendering (Standalone)


### 📜 Lisensi
Project ini di bawah lisensi **MIT License**.
