# 🌍 IPS Human Security
### Platform Pembelajaran Interaktif IPS untuk SD Fase C — Kelas 5 & 6

> Belajar IPS jadi menyenangkan! Platform berbasis **Human Security** untuk siswa SD Fase C (Kelas 5 & 6) — lengkap dengan 7 materi, 7 video, soal latihan, profil tim pengajar, dan panel admin. Cukup **1 file HTML**, langsung jalan di GitHub Pages.

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|---|---|
| 🏠 **Beranda** | Hero section, statistik konten, dan akses cepat ke semua halaman |
| 📚 **Materi** | 7 materi IPS berbasis 7 dimensi Human Security, lengkap dengan tujuan pembelajaran |
| 🎬 **Video** | 7 video pembelajaran dengan embed player YouTube |
| ✏️ **Soal Latihan** | Soal pilihan ganda (A–D) interaktif dengan koreksi dan penjelasan otomatis |
| 👥 **Tim Pengajar** | Profil lengkap tim pengajar/pengembang |
| 🔐 **Panel Admin** | Login admin untuk tambah, edit, dan hapus semua konten |
| 🔔 **Toast Notifikasi** | Notifikasi sukses/error muncul otomatis di setiap aksi admin |
| 💾 **Database Browser** | Semua data tersimpan di `localStorage` — tanpa server, tanpa biaya |

---

## 🗂️ Halaman Website

Navigasi antar halaman menggunakan JavaScript (Single Page Application — 1 file HTML):

```
🏠 Beranda        — Tampilan utama dengan statistik & akses cepat
📚 Materi         — Daftar 7 materi + halaman detail tiap materi
🎬 Video          — Galeri 7 video dengan embed YouTube player
✏️ Soal           — Latihan soal pilihan ganda + penilaian otomatis
👥 Tim            — Profil tim pengajar
🔐 Login Admin    — Halaman login khusus admin
⚙️ Panel Admin    — Kelola materi, video, soal, dan tim
```

---

## 📚 Daftar Materi (7 Materi — Sesuai 7 Dimensi Human Security)

| No | Judul | Dimensi Human Security | Kelas |
|---|---|---|---|
| 1 | 🛡️ Apa Itu Human Security? | Pengantar 7 Dimensi | Kelas 5 |
| 2 | 🌿 Menjaga Lingkungan Kita | Keamanan Lingkungan | Kelas 5 |
| 3 | 🌈 Keberagaman dalam Masyarakat | Keamanan Komunitas | Kelas 5 |
| 4 | 🤝 Kerjasama di Lingkungan Sekolah | Keamanan Komunitas | Kelas 5 |
| 5 | 🏠 Kebutuhan Dasar Manusia | Keamanan Ekonomi | Kelas 6 |
| 6 | ⚖️ Hak dan Kewajiban Warga Negara | Keamanan Politik | Kelas 6 |
| 7 | 🌾 Keamanan Pangan dan Gizi untuk Semua | Keamanan Pangan | Kelas 6 |

---

## 🎬 Daftar Video (7 Video — Sesuai 7 Dimensi Human Security)

| No | Judul Video | Durasi | Tema |
|---|---|---|---|
| 1 | 🛡️ Pengenalan Human Security untuk Anak SD | 08:45 | Human Security |
| 2 | 🌿 Menjaga Lingkungan Hidup Kita Bersama | 12:20 | Keamanan Lingkungan |
| 3 | 🌈 Keberagaman Budaya Indonesia yang Indah | 15:00 | Keamanan Komunitas |
| 4 | 🤝 Gotong Royong: Nilai Luhur Bangsa | 09:30 | Keamanan Komunitas |
| 5 | 💰 Keamanan Ekonomi: Bebas dari Kemiskinan | 11:15 | Keamanan Ekonomi |
| 6 | 🏥 Keamanan Kesehatan untuk Semua | 10:40 | Keamanan Kesehatan |
| 7 | 🌾 Keamanan Pangan: Hak Makan yang Cukup | 13:00 | Keamanan Pangan |

---

## 🚀 Cara Deploy ke GitHub Pages

### Langkah 1 — Buat Repository
1. Buka [github.com](https://github.com) → login
2. Klik **"New repository"**
3. Beri nama, contoh: `ips-human-security`
4. Pilih **Public** → klik **"Create repository"**

### Langkah 2 — Upload File
1. Di halaman repository, klik **"uploading an existing file"**
2. Drag & drop file `index.html` dan `README.md`
3. Klik **"Commit changes"**

### Langkah 3 — Aktifkan GitHub Pages
1. Buka tab **Settings** di repository
2. Klik **Pages** di menu kiri
3. Di bagian **Source**, pilih **"Deploy from a branch"**
4. Pilih branch **`main`** → folder **`/ (root)`**
5. Klik **Save**

### Langkah 4 — Website Live ✅
Tunggu 1–3 menit, lalu akses di:
```
https://USERNAME.github.io/ips-human-security/
```

> ⚠️ **Penting:** Gunakan **"Deploy from a branch"**, bukan "GitHub Actions" — agar langsung jalan tanpa konfigurasi tambahan.

---

## 🔄 Cara Update Konten di GitHub

Setiap kali mengedit file `index.html` di GitHub:

1. Buka file `index.html` di repository
2. Klik ikon **pensil ✏️** (Edit this file)
3. Lakukan perubahan
4. Klik **"Commit changes"** → **"Commit directly to main"**
5. Tunggu **1–2 menit** lalu buka website
6. Tekan **`Ctrl + Shift + R`** (hard refresh) agar cache browser tidak menghalangi perubahan

---

## ⚙️ Cara Menggunakan Panel Admin

### Login
- Klik tombol **🔐 Admin** di pojok kanan atas navigasi
- Masukkan kredensial berikut:

| | |
|---|---|
| **Username** | `admin` |
| **Password** | `ips2026` |

### Mengelola Konten
Setelah login, pilih tab yang ingin dikelola:

| Tab | Yang Bisa Dilakukan |
|---|---|
| **👥 Mahasiswa / Tim** | Tambah, edit, hapus profil anggota tim pengajar |
| **📚 Materi** | Tambah, edit, hapus materi (pilih Fase C - Kelas 5 atau Kelas 6) |
| **🎬 Video** | Tambah, edit, hapus video (masukkan URL YouTube lengkap) |
| **✏️ Soal** | Tambah, edit, hapus soal pilihan ganda A–D beserta kunci jawaban dan penjelasan |

Setiap aksi berhasil akan muncul **notifikasi toast** hijau di pojok kanan bawah layar.

---

## 💾 Tentang Penyimpanan Data (localStorage)

Semua konten disimpan di **localStorage** browser. Artinya:

- ✅ Tidak butuh server, database, atau biaya apapun
- ✅ Bekerja 100% di GitHub Pages (hosting gratis)
- ✅ Data langsung tersimpan saat admin menambah atau mengedit konten
- ⚠️ Data tersimpan per-browser — jika cache browser dibersihkan, konten kembali ke data awal (default)
- ⚠️ Konten yang diisi admin di satu perangkat tidak otomatis muncul di perangkat lain

> 💡 **Tips:** Untuk konten yang ingin tampil ke semua pengguna secara permanen, edit langsung data default (`DEFAULT_MATERI`, `DEFAULT_VIDEO`, `DEFAULT_SOAL`) di dalam file `index.html`.

---

## 🌐 7 Dimensi Human Security (UNDP 1994)

| Dimensi | Makna |
|---|---|
| 💰 Keamanan Ekonomi | Bebas dari kemiskinan, memiliki penghasilan layak |
| 🌾 Keamanan Pangan | Bebas dari kelaparan, akses pangan bergizi |
| 🏥 Keamanan Kesehatan | Akses layanan kesehatan dan hidup sehat |
| 🌿 Keamanan Lingkungan | Hidup di lingkungan yang bersih dan lestari |
| 🔒 Keamanan Diri | Bebas dari kekerasan dan ancaman fisik |
| 👥 Keamanan Komunitas | Menjaga identitas, tradisi, dan kebersamaan |
| 🗳️ Keamanan Politik | Hak asasi manusia dan kebebasan dasar terlindungi |

---

## 🖥️ Teknologi yang Digunakan

- **Bahasa:** HTML, CSS, JavaScript Vanilla (tanpa framework)
- **Font:** Nunito (Google Fonts)
- **Penyimpanan:** localStorage API
- **Hosting:** GitHub Pages (gratis)
- **Ukuran:** 1 file HTML — ringan dan cepat

---

## 📋 Persyaratan

- ✅ Tidak perlu install apapun
- ✅ Tidak butuh Node.js, PHP, atau server backend
- ✅ Cukup browser modern (Chrome, Firefox, Edge, Safari)
- ✅ Koneksi internet hanya untuk font Google Fonts dan embed video YouTube

---

## 🔧 Tips & Troubleshooting

**Website tidak berubah setelah edit di GitHub?**
→ Tekan `Ctrl + Shift + R` untuk hard refresh, atau buka di tab Incognito

**Lupa password admin?**
→ Cari `ADMIN_PASS` di dalam `index.html` dan ubah nilainya

**Data hilang setelah clear browser?**
→ Data kembali ke default. Edit `DEFAULT_MATERI`, `DEFAULT_VIDEO`, `DEFAULT_SOAL` untuk mengubah data bawaan

**Ingin tambah meta anti-cache agar perubahan langsung terlihat?**
→ Tambahkan ini di dalam `<head>`:
```html
<meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Expires" content="0">
```

---

© 2026 Tim Pengembang — Dibuat dengan ❤️ untuk Siswa Indonesia
