RUANG BELAJAR MATEMATIKA — PANDUAN HOSTING

ISI FOLDER
- index.html                 : halaman dashboard utama
- pages/bahan-ajar.html      : bahan ajar skala, rasio, dan laju perubahan
- pages/simulasi.html        : game dan simulasi denah interaktif
- pages/latihan-soal.html    : latihan soal rasio dan proporsi

CARA UPLOAD KE HOSTING
1. Ekstrak file ZIP ini.
2. Buka File Manager hosting dan masuk ke folder website (biasanya public_html).
3. Upload seluruh isi folder website-matematika ke public_html, bukan hanya index.html.
4. Pastikan folder pages ikut ter-upload dan struktur folder tidak berubah.
5. Buka domain. Halaman index.html akan menjadi dashboard utama.

CATATAN
- Tidak memerlukan database, framework, atau instalasi tambahan.
- Navigasi dashboard memuat masing-masing halaman di dalam dashboard.
- Gunakan hosting web statis yang mendukung HTML, CSS, dan JavaScript.
- Jangan memindahkan file halaman keluar dari folder pages karena dashboard memanggilnya melalui path relatif.
