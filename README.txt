PORTOFOLIO RADIUS KOSGORO - PAKET SITUS
========================================

ISI FOLDER
  index.html          Halaman utama (semua halaman karya ada di dalamnya)
  images/             78 gambar (img-01.jpg dst.)
  videos/             6 video 3D Animation (MP4, 30 detik, sudah dikompres)
  cv/                 CV PDF: CV-Radius-Kosgoro.pdf (ID), CV-Radius-Kosgoro-EN.pdf (EN)
  README.txt          Panduan ini

CARA MEMASANG DI NETLIFY (gratis)
  1. Buka netlify.com lalu daftar / masuk.
  2. Buka menu "Sites", cari kotak "Drag and drop your site folder here".
  3. Ekstrak file ZIP ini, lalu seret SELURUH FOLDER (yang berisi index.html) ke kotak itu.
  4. Tunggu beberapa saat (video membuat unggahan sedikit lebih lama). Netlify memberi
     alamat seperti nama-acak.netlify.app.
  5. Ganti nama alamatnya di: Site configuration > Change site name.
  6. Domain sendiri (opsional): beli di registrar, lalu sambungkan lewat
     Domain management > Add a domain. Ikuti petunjuk DNS dari Netlify.

LAYANAN LAIN (cara serupa): Vercel, Cloudflare Pages, GitHub Pages.

CATATAN
  - Jangan pindahkan atau ganti nama folder images/, videos/, dan cv/. index.html
    memanggilnya dengan alamat relatif.
  - Video hanya diunduh saat tombol putar diklik, jadi halaman tetap ringan dan
    suaranya ikut terputar (versi Artifact hanya cuplikan 8 detik tanpa suara).
  - Total ukuran folder sekitar 21 MB. Cek batas ukuran dan bandwidth paket hosting
    yang dipilih di situs resminya sebelum mengunggah.
  - Font memuat dari Google Fonts, jadi perlu internet saat dibuka.
  - Pratinjau tautan di WhatsApp/LinkedIn (Open Graph) belum dipasang karena butuh
    alamat domain final. Minta ditambahkan setelah situs punya alamat.
  - Setiap perubahan konten: unggah ulang foldernya (Netlify: Deploys > drag folder baru).
