# 🌍 IPS Human Security
### Platform Pembelajaran Interaktif IPS untuk SD Fase C

> Belajar IPS jadi menyenangkan! Platform berbasis **Human Security** untuk siswa SD Kelas 4, 5 & 6 — lengkap dengan materi, video, soal latihan, dan panel admin. Cukup **1 file HTML**, langsung jalan di GitHub Pages.

---

## ✨ Fitur Utama

| Fitur | Keterangan |
|---|---|
| 🏠 **Beranda** | Hero section, statistik konten, dan akses cepat ke semua halaman |
| 📚 **Materi** | Sajian materi IPS bertema Human Security lengkap dengan halaman detail |
| 🎬 **Video** | Galeri video pembelajaran dengan embed player |
| ✏️ **Soal Latihan** | Soal pilihan ganda interaktif dengan koreksi dan penjelasan otomatis |
| 👥 **Tim Pengajar** | Profil lengkap tim pengajar/pengembang |
| 🔐 **Panel Admin** | Login admin untuk tambah, edit, dan hapus semua konten |
| 🔔 **Toast Notifikasi** | Notifikasi sukses/error muncul otomatis setiap aksi admin |
| 💾 **Database Browser** | Semua data tersimpan di `localStorage` — tanpa server, tanpa biaya |

---

## 🗂️ Halaman Website

Navigasi antar halaman menggunakan JavaScript (Single Page Application):

```
🏠 Beranda       — Tampilan utama dengan statistik & akses cepat
📚 Materi        — Daftar materi + halaman detail tiap materi
🎬 Video         — Galeri video dengan embed player
✏️ Soal          — Latihan soal pilihan ganda + penilaian otomatis
👥 Tim           — Profil tim pengajar
🔐 Login Admin   — Halaman login khusus admin
⚙️ Panel Admin   — Kelola materi, video, soal, dan tim
```

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
| **📚 Materi** | Tambah, edit, hapus materi pembelajaran |
| **🎬 Video** | Tambah, edit, hapus video (URL embed) |
| **✏️ Soal** | Tambah, edit, hapus soal pilihan ganda + kunci jawaban |
| **👥 Tim** | Tambah, edit, hapus profil anggota tim pengajar |

Setiap aksi berhasil akan muncul **notifikasi toast** di pojok kanan bawah layar.

---

## 💾 Tentang Penyimpanan Data (localStorage)

Semua konten disimpan di **localStorage** browser. Artinya:

- ✅ Tidak butuh server, database, atau biaya apapun
- ✅ Bekerja 100% di GitHub Pages (hosting gratis)
- ✅ Data langsung tersimpan saat admin menambah atau mengedit konten
- ⚠️ Data tersimpan per-browser — jika cache browser dibersihkan, konten kembali ke data awal
- ⚠️ Konten yang diisi admin di satu perangkat tidak otomatis muncul di perangkat lain

> 💡 **Tips:** Untuk konten yang ingin tampil ke semua pengguna secara permanen, edit langsung data default di fungsi `initData()` di dalam file `index.html`.

---

## 🎨 Topik Materi

| Tema | Subtopik |
|---|---|
| 🛡️ Keamanan Manusia | Pengertian Human Security, 7 dimensi, contoh kasus |
| 🌍 Lingkungan & Masyarakat | Ekosistem, bencana alam, kelestarian alam |
| 🤝 Kerja Sama Sosial | Organisasi masyarakat, norma sosial, gotong royong |
| 💡 Ekonomi Dasar | Kebutuhan, produksi, distribusi, konsumsi |

---

## 🖥️ Teknologi yang Digunakan

- **Bahasa:** HTML, CSS, JavaScript (Vanilla — tanpa framework)
- **Font:** Nunito (Google Fonts)
- **Penyimpanan:** localStorage API
- **Hosting:** GitHub Pages (gratis)
- **Ukuran:** 1 file HTML — ringan dan cepat

---

## 📋 Persyaratan

- ✅ Tidak perlu install apapun
- ✅ Tidak butuh Node.js, PHP, atau server backend
- ✅ Cukup browser modern (Chrome, Firefox, Edge, Safari)
- ✅ Koneksi internet hanya untuk font Google dan embed video

---

## 🔧 Tips & Troubleshooting

**Website tidak berubah setelah edit?**
→ Tekan `Ctrl + Shift + R` untuk hard refresh, atau buka di tab Incognito

**Lupa password admin?**
→ Cari `ADMIN_PASS` di dalam `index.html` dan ubah nilainya

**Data hilang setelah clear browser?**
→ Data kembali ke default. Edit fungsi `initData()` untuk mengubah data bawaan

**Ingin tambah meta anti-cache?**
→ Tambahkan ini di dalam `<head>`:
```html
<meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate">
<meta http-equiv="Pragma" content="no-cache">
<meta http-equiv="Expires" content="0">
```

---

© 2026 Tim Pengembang — Dibuat dengan ❤️ untuk Siswa Indonesia
