# praktikum1-4PemrogramanWeb2
📚 Web Artikel dengan Sistem Login (CodeIgniter 4)
<p align="center"> <img src="https://img.shields.io/badge/CodeIgniter-4-red?style=for-the-badge&logo=codeigniter"> <img src="https://img.shields.io/badge/PHP-8-blue?style=for-the-badge&logo=php"> <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql"> <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"> </p>
🧾 Deskripsi Project

Project ini merupakan aplikasi web sederhana berbasis CodeIgniter 4 yang dirancang untuk mengelola data artikel secara dinamis dengan sistem autentikasi pengguna.

Aplikasi ini dibuat sebagai bagian dari praktikum Pemrograman Web 2, dengan tujuan untuk memahami konsep dasar pengembangan web modern menggunakan arsitektur MVC (Model-View-Controller).

Dalam aplikasi ini, pengguna diwajibkan untuk login terlebih dahulu sebelum dapat mengakses fitur manajemen artikel. Sistem juga menerapkan keamanan dasar seperti hashing password dan penggunaan session untuk menjaga status login pengguna.

Aplikasi ini sangat cocok sebagai latihan untuk memahami:

CRUD database (Create, Read, Update, Delete)
Sistem login dan keamanan dasar
Routing dan filter pada CodeIgniter 4
Penggunaan session dalam aplikasi web
✨ Fitur Utama
🔐 Authentication (Autentikasi)
Login menggunakan email & password
Password dienkripsi menggunakan password_hash()
Session login (logged_in)
Logout (menghapus session)
🛡️ Authorization (Hak Akses)
Halaman /admin/* dilindungi oleh Auth Filter
User yang belum login akan diarahkan ke halaman login
Proteksi akses URL secara langsung
📰 Manajemen Artikel (CRUD)
➕ Tambah artikel
✏️ Edit artikel
❌ Hapus artikel
📋 List artikel
📸 Screenshot
🔑 Halaman Login

📰 Dashboard Artikel

➕ Tambah Artikel

💡 Ganti gambar di atas dengan screenshot project kamu sendiri

⚙️ Teknologi yang Digunakan
Backend: CodeIgniter 4
Bahasa: PHP
Database: MySQL / MariaDB
Frontend: HTML, CSS (opsional: Bootstrap)
Server: Apache / XAMPP / Laragon
⚙️ Instalasi & Setup
1. Clone Repository
git clone https://github.com/username/nama-repo.git
2. Masuk ke Folder Project
📢 Share ke teman
