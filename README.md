# My Personal Portfolio Website

Selamat datang di portfolio pribadi saya! Website ini dibuat untuk menampilkan keahlian, pengalaman, dan proyek-proyek yang telah saya kerjakan di bidang [sebutkan bidang Anda, misal: pengembangan web, data science, dll.]. Anda juga bisa mengunduh CV dan melihat sertifikasi saya.

## Fitur Utama

* **Responsif:** Tampilan optimal di berbagai perangkat (desktop, tablet, mobile).
* **Desain Modern & Bersih:** Menggunakan estetika IT dengan palet warna gelap dan aksen cerah.
* **Latar Belakang Interaktif:** Efek partikel dinamis yang mengisi seluruh halaman, memberikan tampilan "live wallpaper" menggunakan Particle.js.
* **Navigasi Mudah:** Struktur satu halaman dengan navigasi sticky.
* **Informasi Lengkap:** Biodata, daftar keahlian, riwayat pengalaman, dan detail proyek.
* **Download CV:** Tautan langsung untuk mengunduh CV Anda.
* **Bagian Sertifikasi:** Menampilkan kredensial dan sertifikasi profesional yang Anda miliki.
* **Integrasi GitHub Pages:** Siap di-deploy dan diakses secara publik.

## Teknologi yang Digunakan

* **HTML5:** Struktur dasar halaman web.
* **CSS3:** Styling (Flexbox, Grid, Variabel CSS) untuk desain yang rapi dan responsif.
* **JavaScript (ES6+):** Untuk *smooth scrolling*, fungsionalitas hamburger menu, dan inisialisasi Particle.js.
* **Particle.js:** Library JavaScript untuk efek latar belakang partikel.
* **Font Awesome:** Untuk ikon.
* **Google Fonts:** Untuk tipografi yang menarik (`Poppins` dan `Fira Code`).

## Instalasi dan Penggunaan

Website ini adalah website statis, jadi tidak memerlukan proses instalasi yang kompleks.

1.  **Clone repositori ini:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    ```
2.  **Jalankan dengan Server Lokal (Direkomendasikan):**
    Karena adanya efek partikel yang memuat file JSON secara asinkron, disarankan untuk menjalankan website melalui server lokal. Jika Anda menggunakan XAMPP:
    * Pastikan folder `my_portfolio` berada di `C:\xampp\htdocs\`.
    * Buka XAMPP Control Panel dan **Start Apache**.
    * Akses website Anda di browser melalui: `http://localhost/my_portfolio/`
    * **Penting:** Jika Anda hanya membuka file `index.html` langsung dari browser (`file:///...`), efek partikel mungkin tidak muncul karena batasan keamanan browser.

## Deployment ke GitHub Pages

1.  Pastikan semua kode Anda sudah di-push ke branch `main` (atau `master`) di repositori GitHub Anda.
2.  Di repositori GitHub Anda, pergi ke **Settings** > **Pages**.
3.  Pilih `main` (atau `master`) sebagai *source branch* dan `/ (root)` sebagai folder.
4.  Klik **Save**.
5.  Website Anda akan tersedia di URL yang diberikan oleh GitHub Pages (contoh: `https://your-username.github.io/your-repository-name/`).

## Kustomisasi

Anda dapat dengan mudah mengkustomisasi portfolio ini:

* Ganti `img/profile.jpg` dengan foto profil Anda.
* **PENTING:** Ganti `docs/your-cv.pdf` dengan file CV Anda dan perbarui path di `index.html`.
* Perbarui konten di `index.html` dengan informasi pribadi, keahlian, pengalaman, dan detail proyek Anda.
* Tambahkan atau ganti gambar proyek di folder `img/`.
* Tambahkan gambar sertifikasi Anda di `img/` dan perbarui detailnya di bagian "Sertifikasi" di `index.html`.
* Sesuaikan warna, font, dan gaya di `css/style.css` dan `css/components.css` agar sesuai dengan preferensi pribadi Anda.
* **Untuk efek partikel:** Edit `js/particles.json` untuk mengubah jumlah, warna, ukuran, dan interaktivitas partikel. Anda bisa bereksperimen dengan berbagai pengaturan untuk mendapatkan tampilan yang Anda inginkan.

---

Terima kasih telah mengunjungi portfolio saya!

---

**Langkah Terakhir yang Perlu Anda Lakukan:**

1.  **Buat/Perbarui Semua File:** Pastikan Anda menyalin dan menyimpan kode ini ke file yang sesuai di dalam struktur folder `my-portfolio` Anda. **Perhatikan nama file dan folder dengan sangat teliti.**
2.  **Personalisasi Konten:** Ganti semua placeholder (`[Nama Anda]`, `[Profesi Anda]`, `docs/your-cv.pdf`, link sosial media, detail pengalaman, proyek, dan sertifikasi) dengan informasi Anda sendiri.
3.  **Pastikan Aset Ada:** Masukkan foto profil Anda (`profile.jpg`), gambar proyek (`project-1.jpg`, `project-2.jpg`), gambar sertifikasi (`certificate-aws.jpg`, dll.), dan file CV (`your-cv.pdf`) ke dalam folder `img/` dan `docs/` yang sesuai.
4.  **Jalankan dengan XAMPP:**
    * Buka XAMPP Control Panel.
    * **Stop Apache** (jika sedang berjalan).
    * **Start Apache** (setelah memastikan semua file sudah di tempatnya).
    * Buka browser dan akses `http://localhost/my_portfolio/`.
5.  **Hard Refresh dan Debugging:** Selalu lakukan Hard Refresh (`Ctrl+Shift+R` atau `Cmd+Shift+R`) setiap kali Anda membuat perubahan. Gunakan Developer Tools (`F12`) untuk memeriksa tab **Console** (untuk error JavaScript) dan **Network** (untuk memastikan semua file dimuat dengan `200 OK`).

Dengan semua kode ini, website Anda seharusnya sudah menampilkan efek partikel di seluruh halaman!