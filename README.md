# Website Report Canvasing Sales Agent

## Praktik Kerja Lapangan  
**Divisi Business Service, Telkom Sentral Telepon Otomat (STO) Dahlia Kota Samarinda**  

**Oleh:** Mahmuda  
**Fakultas Teknik, Universitas Mulawarman**  
**Samarinda, 2022**

---

## Deskripsi Proyek
Website Report Canvasing Sales Agent bertujuan untuk mempermudah:  
- Monitoring aktivitas sales agent.  
- Melihat laporan hasil kunjungan sales agent secara dokumentasi.  
- Pengelolaan data pelanggan dan dokumentasi kunjungan.  
- Penyimpanan data dan foto kunjungan untuk keperluan Divisi Business Service.  
- Pembuatan laporan yang dapat diekspor dalam format Excel (.xlsx).

Program kerja website ini dibuat agar Divisi Business Service dapat meninjau aktivitas sales agent dengan lebih mudah, cepat, dan terstruktur.

> **Catatan:** File kode sumber website tidak tersedia di repositori ini. Hanya dokumentasi dan screenshot yang disertakan.

---

## Database Website
Pengelolaan database menggunakan **phpMyAdmin** untuk database **MySQL**.  
Berikut beberapa tabel utama:

- **Tabel user**: 4 atribut (id, username, email, password)  
  ![Database User](screenshots/database_user.png)

- **Tabel tb_galery**: 7 atribut (id, nama, tempat, alamat, pelanggan, waktu, file)  
  ![Database Gallery](screenshots/database_tb_galery.png)

---

## Tampilan Website
Berikut beberapa tampilan website selama PKL:

### Sign Up
Form untuk membuat akun dengan input Username, Email, Password, dan Re-Password.  
![Sign Up](screenshots/signup.png)

### Log In
Form login dengan email dan password. Dapat diarahkan ke Sign Up jika belum memiliki akun.  
![Log In](screenshots/login.png)

### Home
Menampilkan foto atau gambar hasil input dari halaman Input Data.  
![Home](screenshots/home.png)

### Input Data
Form input data: name, date, place, address, customer’s name, dan image.  
![Input Data](screenshots/input_data.png)

### Overview
Menampilkan data yang telah diinput. Data dapat dihapus atau dicetak ke Excel.  
![Overview](screenshots/overview.png)

### My Account
Menu untuk mengubah password atau logout dari website.  
![My Account](screenshots/my_account.png)

### Change Password
Form untuk mengganti password lama dengan password baru.  
![Change Password](screenshots/change_password.png)

### About Us
Halaman pengenalan Telkom Indonesia, sejarah, produk, dan visi misi.  
![About Us](screenshots/about_us.png)

---

## Teknologi yang Digunakan
- **PHP, HTML, CSS, JavaScript** – untuk pengembangan website.  
- **MySQL** – untuk penyimpanan data.  
- **phpMyAdmin** – pengelolaan database melalui website.  
- **XAMPP** – server lokal untuk pengembangan.

---

## Tujuan PKL
1. Menerapkan ilmu kuliah dalam praktik nyata.  
2. Memahami etika kerja dan lingkungan profesional.  
3. Menambah pengalaman dan wawasan teknis.  
4. Mengaplikasikan teori akademik ke dunia kerja.

---

## Lisensi
Proyek ini bersifat **non-komersial** dan dibuat untuk keperluan akademik Praktik Kerja Lapangan (PKL).
