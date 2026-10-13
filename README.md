# Web Portofolio Tim — UTS Pemrograman Web

> **Proyek Ujian Tengah Semester (UTS)** mata kuliah **Pemrograman Web**  
> Program Studi D4 Manajemen Informatika · Kelas 2025D · Universitas Negeri Surabaya

---

## Deskripsi Proyek

Website portofolio tim mahasiswa yang dirancang dan dikembangkan sebagai penugasan UTS mata kuliah Pemrograman Web. Website ini menampilkan profil lengkap seluruh anggota tim, proyek yang dikerjakan, serta halaman kontak interaktif.

Fitur utama website:
- **Bubble Scroll Navigation** — Transisi antar-slide yang halus dan elegan di halaman Home
- **Light / Dark Mode** — Pengalihan tema terang & gelap dengan penyimpanan preferensi via `localStorage`
- **Dynamic Profile** — Data profil anggota tim dimuat secara dinamis tanpa reload halaman
- **Form Validasi** — Formulir kontak dengan validasi interaktif berbasis JavaScript
- **Responsive Design** — Tampilan menyesuaikan berbagai ukuran layar

---

## Anggota Tim

| No | Nama | NIM | Peran |
|----|------|-----|-------|
| 1 | **Rahmadhani Akhsanul Rijal** | 25091397127 | Project Manager |
| 2 | **Rozaq Abdul Ghani** | 25091397145 | Desain UI |
| 3 | **Liani Komala Sari** | 25091397143 | Document Editor |

---

## Struktur File

```
UTS/
├── index.html          # Halaman Home (Bubble Scroll — Hero + 3 Team Member)
├── about.html          # Halaman About Us (Profil detail tiap anggota tim)
├── project.html        # Halaman Project (Deskripsi proyek UTS)
├── contact.html        # Halaman Contact Us (Informasi kontak + Form pesan)
├── style.css           # Stylesheet utama (variabel warna, layout, dark mode)
├── js/
│   ├── bubble-scroll.js  # Logika navigasi bubble scroll & transisi slide
│   ├── theme.js          # Logika toggle Light/Dark mode + localStorage
│   └── form.js           # Validasi & handling formulir kontak
├── foto.jpeg           # Foto Rahmadhani Akhsanul Rijal
├── Foto Rozak.jpeg     # Foto Rozaq Abdul Ghani
├── Foto Liani.jpeg     # Foto Liani Komala Sari
├── foto1.jpg           # Gambar logo navbar
├── Logo UTS.png        # Logo proyek UTS
├── Logo Github.jpg     # Ikon sosial media GitHub
├── Logo Linkedin.jpg   # Ikon sosial media LinkedIn
├── Logo Instagram.jpg  # Ikon sosial media Instagram
├── Logo Email.jpg      # Ikon email
└── Logo Maps.jpg       # Ikon lokasi
```

---

## Teknologi yang Digunakan

| Teknologi | Keterangan |
|-----------|------------|
| **HTML5 Semantik** | Struktur halaman menggunakan elemen semantik (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) |
| **CSS3** | Variabel CSS kustom, CSS Grid, Flexbox, animasi transisi |
| **Vanilla JavaScript** | Bubble scroll, dark mode, validasi form — tanpa framework eksternal |
| **localStorage** | Menyimpan preferensi tema pengguna secara persisten |
| **Responsive Design** | Layout menyesuaikan layar desktop, tablet, dan mobile |

---

## Sistem Warna

Website menggunakan palet warna terstandarisasi yang didefinisikan sebagai CSS Custom Properties:

| Nama Warna | Keterangan |
|------------|------------|
| **Dark Chocolate** | Warna gelap utama (latar dark mode) |
| **Milk Tea** | Warna netral tengah |
| **Misty Rose** | Warna aksen lembut |

---

## Cara Menjalankan

Website ini merupakan **static website** (HTML, CSS, JS murni) dan **tidak memerlukan server atau build tool** apapun.

### Cara 1 — Buka Langsung di Browser
1. Clone atau download repositori ini
2. Buka file `index.html` langsung di browser (Chrome, Firefox, Edge, dll.)

### Cara 2 — Menggunakan Live Server (VS Code)
1. Install ekstensi **Live Server** di VS Code
2. Klik kanan pada `index.html` → pilih **"Open with Live Server"**

---

## Halaman Website

| Halaman | File | Deskripsi |
|---------|------|-----------|
| **Home** | `index.html` | Hero section + slide kartu tiap anggota tim |
| **About Us** | `about.html` | Detail profil, skill, dan informasi akademik anggota tim |
| **Project** | `project.html` | Deskripsi proyek UTS beserta teknologi dan peran tim |
| **Contact Us** | `contact.html` | Informasi kontak tim + formulir kirim pesan |

---

## Fitur Unggulan

### Bubble Scroll
Halaman Home menggunakan sistem navigasi bubble unik di mana konten beralih antar-slide secara smooth saat di-scroll atau mengklik dot navigasi di samping layar.

### Dark / Light Mode
Toggle tema dapat diakses melalui tombol di sudut kanan navbar. Preferensi tema tersimpan otomatis di `localStorage` sehingga tetap konsisten saat halaman direfresh.

### Dynamic Profile Switcher
Halaman About Us memuat data profil ketiga anggota tim secara dinamis menggunakan JavaScript — cukup klik tab anggota untuk beralih tampilan profil tanpa reload halaman.

---

## Catatan

- Proyek ini dikembangkan murni sebagai **tugas akademik** mata kuliah Pemrograman Web.
- Tidak menggunakan framework CSS (seperti Bootstrap atau Tailwind) maupun framework JavaScript (React, Vue, dll.) — semua ditulis dengan **Vanilla HTML, CSS, dan JavaScript**.

---

© 2026 Tim Portofolio Mahasiswa — D4 Manajemen Informatika, Universitas Negeri Surabaya.
