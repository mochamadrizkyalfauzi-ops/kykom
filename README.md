# 📖 KYKOM - Website Baca Komik Online

Website baca komik gratis menggunakan MangaDex API.
Dibuat dengan Python (Flask) + HTML + CSS + JavaScript (React)

---

## 📁 Struktur File

```
kykom/
├── app.py              ← Backend Python (Flask)
├── requirements.txt    ← Daftar library Python
├── Procfile            ← Konfigurasi untuk deploy
├── README.md           ← File ini
└── templates/
    └── index.html      ← Tampilan website (React)
```

---

## 🖥️ Cara Jalankan di Laptop (Lokal)

### Langkah 1 — Install Python
Kalau belum ada, download di: https://python.org/downloads
Centang "Add Python to PATH" saat install!

### Langkah 2 — Buka Terminal / CMD
Di folder kykom, klik kanan → "Open in Terminal"
atau buka CMD lalu ketik:
```
cd path/ke/folder/kykom
```

### Langkah 3 — Install Library
```
pip install -r requirements.txt
```

### Langkah 4 — Jalankan Website
```
python app.py
```

### Langkah 5 — Buka di Browser
Buka: http://localhost:5000

---

## 🌐 Cara Deploy ke Railway (Bisa Diakses Orang Lain)

### Langkah 1 — Upload ke GitHub
1. Buat akun di https://github.com (gratis)
2. Klik "New Repository" → beri nama "kykom"
3. Upload semua file kykom ke repository itu

### Langkah 2 — Deploy di Railway
1. Buka https://railway.app
2. Login pakai akun GitHub
3. Klik "New Project" → "Deploy from GitHub repo"
4. Pilih repository "kykom"
5. Railway otomatis mendeteksi Procfile dan deploy!

### Langkah 3 — Dapatkan Link
Setelah deploy selesai (±2 menit), kamu dapat link seperti:
👉 https://kykom.up.railway.app

Link itu bisa dibuka siapa saja di seluruh dunia! 🌍

---

## 🛠️ Teknologi yang Digunakan

| Bagian      | Teknologi              |
|-------------|------------------------|
| Backend     | Python 3 + Flask       |
| Frontend    | HTML, CSS, JavaScript  |
| UI Library  | React 18 (via CDN)     |
| API Komik   | MangaDex API (gratis)  |
| Deploy      | Railway                |

---

## ✨ Fitur Website

- 🔥 Tampilkan 18 komik populer di homepage
- 🔍 Pencarian komik berdasarkan judul
- 📚 Halaman detail komik (deskripsi, genre, daftar chapter)
- 📖 Baca komik halaman per halaman
- 📱 Responsive (bisa dibuka di HP)

---

Dibuat untuk tugas Dasar Pemrograman
