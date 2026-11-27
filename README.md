# GeoMatika — Jelajahi Bangun Datar

Media pembelajaran matematika interaktif berbasis web untuk siswa **SMP Kelas VII** pada materi **Bangun Datar** (Kurikulum Merdeka).

## Fitur Utama
- **Halaman Pembuka (Welcome Page):** Pintu masuk visual yang ramah siswa SMP tanpa sistem login, akun, atau kata sandi.
- **Pengenalan & Materi Lengkap:** Konsep 2D vs 3D, unsur bangun datar, serta karakteristik dan rumus 11 topik bangun datar (Persegi, Persegi Panjang, Segitiga, Jajar Genjang, Belah Ketupat, Layang-layang, Trapesium, Lingkaran, Segi Banyak Beraturan, Bangun Gabungan, dan Simetri & Transformasi).
- **Laboratorium Geometri (11 Simulasi Interaktif):** Eksplorasi visual berbasis SVG dengan slider dinamis, pemotongan jajar genjang, trapesium kembar, nilai π, dan transformasi simetri.
- **Keliling & Luas:** Perbandingan konsep batas vs daerah, bedah miskonsepsi umum siswa kelas VII, dan tabel ringkasan rumus.
- **10 Soal Latihan HOTS & Evaluasi Otomatis:** Soal kontekstual level C4–C6 (pilihan ganda, isian numerik, dan uraian) lengkap dengan penilaian otomatis, pembahasan, dan rekomendasi belajar.
- **Progres Belajar Anonim:** Riwayat simulasi dan skor latihan tersimpan otomatis di `localStorage` browser perangkat siswa tanpa identitas pribadi.

## Tipografi
- **Inter:** Teks utama, judul, subjudul, paragraf materi, navigasi, tombol, dan antarmuka.
- **STIX Two Math:** Rumus keliling, rumus luas, simbol, dan notasi matematika.
- **DejaVu Sans Mono:** Angka hasil perhitungan, skor, dan tampilan numerik.

## Struktur Direktori
```text
GeoMatika/
├── index.html   # Aplikasi web statis lengkap (HTML, Tailwind CSS, SVG, JavaScript)
└── README.md    # Dokumentasi penggunaan dan panduan deployment
```

## Cara Menjalankan Secara Lokal
Cukup buka file `index.html` menggunakan browser modern (Chrome, Edge, Firefox, atau Safari). Tidak memerlukan server backend, database, maupun proses build.

## Panduan Deployment ke GitHub & Vercel
1. **Siapkan Folder Proyek:** Ekstrak folder `GeoMatika` dan pastikan `index.html` berada di root folder (bukan di dalam subfolder tambahan).
2. **Buat Repository GitHub:** Buka [github.com](https://github.com) → klik **New repository** → beri nama misalnya `geomatika` → pilih **Public** → klik **Create repository**.
3. **Unggah File ke GitHub:** Klik **uploading an existing file**, lalu seret `index.html` dan `README.md` ke halaman tersebut → klik **Commit changes**.
4. **Hubungkan ke Vercel:** Buka [vercel.com](https://vercel.com) dan login menggunakan akun GitHub → klik **Add New...** → **Project** → pilih repository `geomatika` → klik **Import**.
5. **Pengaturan Build Vercel:**
   - **Framework Preset:** `Other`
   - **Root Directory:** `./` (default, tempat `index.html` berada)
   - **Build Command:** Kosongkan (tidak diperlukan)
   - **Output Directory:** Kosongkan (default)
6. **Deploy:** Klik tombol **Deploy** dan tunggu beberapa detik hingga selesai.
7. **Akses Publik:** Website siap diakses melalui tautan publik seperti `https://geomatika.vercel.app` tanpa perlu login.
