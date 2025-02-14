# AgroToolz 🌾

AgroToolz adalah platform berbasis web yang dirancang untuk mempermudah akses ke alat pertanian, konsultasi dengan ahli, dan pembelian bahan pertanian secara online. Dibangun menggunakan **Django** dan mengadopsi **arsitektur microservice** untuk autentikasi melalui **C45 Authenticator Service**, aplikasi ini memberikan pengalaman yang lebih fleksibel dan aman bagi pengguna.

## ✨ Modul dan Fitur  

### 🔑 Manajemen Pengguna  
- User dapat **mendaftar, login, logout, dan mengelola akun mereka** melalui microservice **C45 Authenticator Service**.  
- **Terdapat dua peran utama:**  
  - **Admin** → Mengelola daftar barang yang tersedia untuk disewa/dibeli serta daftar expert konsultasi.  
  - **User** → Dapat melihat katalog barang, tetapi harus **login** untuk melihat detail produk atau melakukan pemesanan.  

### 🚜 Penyewaan Alat Pertanian  
- Menyediakan berbagai alat pertanian seperti **traktor, penggiling padi, dan penyemprot hama** yang dapat disewa.  
- Proses booking sederhana: **pilih alat → tentukan tanggal → dapatkan link bukti pemesanan**.  
- **Admin** dapat menambah, mengedit, atau menghapus daftar alat yang tersedia untuk disewa.  

### 👨‍🌾 Konsultasi dengan Ahli  
- User dapat berkonsultasi dengan **ahli pertanian** untuk mendapatkan solusi terkait pertanian mereka.  
- Konsultasi bisa dilakukan dalam dua cara:  
  - **Booking sesi online** dengan expert.  
  - **Forum diskusi** yang dapat diakses oleh pengguna yang sudah login.  
- **Admin** dapat menambahkan dan mengatur daftar **expert** yang tersedia.  

### 🛒 Penjualan Bahan Pertanian  
- Menyediakan katalog produk seperti **pupuk, benih, pestisida, dan vitamin tanaman**.  
- User bisa **menambahkan produk ke keranjang**, tetapi harus **login** untuk melihat detail produk dan melanjutkan pembelian.  
- **Admin** memiliki kendali penuh untuk menambah, mengedit, dan menghapus daftar produk.  

## 🎯 Tim Pengembang  
- **Project Manager**: Nur Khoirunnisa Salsabila  
- **Developer Lead**: Adelya Amanda  
- **Tester Lead**: Nasha Zahira  
- **Designer Lead**: Ananda Dwi Hanifa  
- **Analyst Lead**: Joanne Kenisa Adelina Limena  

📌 Dikembangkan oleh **kelas PKPL C kelompok 45**  
