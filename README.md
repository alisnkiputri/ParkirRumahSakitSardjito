# ParkirRumahSakitSardjito
# 🏥 Website RSUD Sardjito

Website **RSUD Sardjito** merupakan sebuah website informasi rumah sakit yang dibuat untuk memudahkan pengguna dalam memperoleh informasi mengenai layanan dan fasilitas rumah sakit secara online.

## 📌 Tentang Project

Project ini dibuat sebagai website berbasis web yang menyediakan informasi rumah sakit dengan tampilan yang sederhana, informatif, dan mudah digunakan.
**Mockup:**[MockupRS](https://raw.githubusercontent.com/alisnkiputri/ParkirRumahSakitSardjito/refs/heads/main/mockup.png)
**Flowchart:**[FlowchartRS](https://raw.githubusercontent.com/alisnkiputri/ParkirRumahSakitSardjito/refs/heads/main/flowchart.png)
**Algoritma:**[AlgoritmaRS](https://canva.link/ra68p3tinpxni1l)

Website dapat diakses melalui:

**https://rsudsardjitooo.infinityfree.me/**

## 🎯 Tujuan

Tujuan pembuatan website ini adalah:

* Menyediakan informasi rumah sakit secara online.
* Memudahkan pengguna dalam mengetahui layanan yang tersedia.
* Menampilkan informasi fasilitas rumah sakit.
* Membuat media informasi rumah sakit yang mudah diakses.
* Menerapkan kemampuan dalam pengembangan website menggunakan PHP dan database.

## ✨ Fitur Website

Beberapa fitur yang terdapat dalam website antara lain:

* 🏠 **Home** — Halaman utama website.
* 🏥 **Informasi Rumah Sakit** — Menampilkan informasi mengenai rumah sakit.
* 🩺 **Informasi Layanan** — Menampilkan layanan yang tersedia.
* 👨‍⚕️ **Informasi Dokter** — Menampilkan informasi dokter atau tenaga medis.
* 🏢 **Informasi Fasilitas** — Menampilkan fasilitas yang tersedia.
* 📞 **Kontak** — Menampilkan informasi kontak rumah sakit.
* 🔐 **Login/Admin** — Digunakan untuk mengelola data website apabila tersedia.
* 🗃️ **Database** — Digunakan untuk menyimpan dan mengelola data website.

## 🛠️ Teknologi yang Digunakan

Project ini menggunakan beberapa teknologi, yaitu:

* **HTML** — Membuat struktur halaman website.
* **CSS** — Mengatur tampilan dan desain website.
* **JavaScript** — Menambahkan fungsi interaktif pada website.
* **PHP** — Digunakan sebagai bahasa pemrograman sisi server.
* **MySQL** — Digunakan untuk menyimpan data.
* **XAMPP** — Digunakan sebagai server lokal pada saat proses pengembangan.
* **InfinityFree** — Digunakan sebagai layanan hosting untuk mempublikasikan website.

## 📂 Struktur Project

Contoh struktur folder project:

```text
rsud-sardjito/
│
├── index.php
├── login.php
├── dashboard.php
├── koneksi.php
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── img/
│   └── gambar-website
│
└── README.md
```

## 💻 Cara Menjalankan Project

### 1. Menjalankan di Localhost

1. Install **XAMPP**.
2. Aktifkan **Apache** dan **MySQL**.
3. Simpan folder project ke dalam:

```text
C:\xampp\htdocs\
```

4. Buat database menggunakan **phpMyAdmin**.
5. Import file database SQL jika tersedia.
6. Sesuaikan konfigurasi koneksi database pada file PHP.
7. Buka browser dan akses:

```text
http://localhost/rsud-sardjito/
```

### 2. Menjalankan Versi Online

Website telah diunggah ke hosting **InfinityFree** dan dapat diakses melalui:

```text
https://rsudsardjitooo.infinityfree.me/
```

## 🗄️ Database

Database digunakan untuk menyimpan data yang diperlukan oleh website, seperti data pengguna, dokter, layanan, fasilitas, atau data lainnya sesuai kebutuhan sistem.

Koneksi database pada PHP menggunakan konfigurasi seperti:

```php
$conn = mysqli_connect("localhost", "root", "", "nama_database");
```

> Konfigurasi tersebut perlu disesuaikan dengan database yang digunakan pada project.

## 🎨 Tampilan

Website dirancang agar memiliki tampilan yang:

* Sederhana
* Informatif
* Responsif
* Mudah digunakan
* Nyaman diakses melalui komputer maupun perangkat mobile

## 👥 Pengembang

**Nama:** Alinski Putri
**Kelas:** XI RPL 1
**Jurusan:** Rekayasa Perangkat Lunak (RPL)

## 📄 Lisensi

Project ini dibuat untuk keperluan **pembelajaran dan tugas sekolah**.

---

⭐ **Terima kasih telah mengunjungi project Website RSUD Sardjito.**
