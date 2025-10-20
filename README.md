Pertemuan 02 — Basic CSS

Ringkasan:
Panduan singkat untuk memahami dasar-dasar CSS: selector, warna, font, dan tata letak. Cocok sebagai materi pengantar untuk mempercantik tampilan halaman web.


---

Isi singkat

Pengenalan apa itu CSS dan fungsinya

Tiga jenis selector utama (element, class, id)

Cara menerapkan CSS: internal dan eksternal

Contoh singkat untuk langsung dicoba



---

❓ Apa itu CSS?

CSS (Cascading Style Sheets) digunakan untuk mengatur tampilan halaman web agar lebih rapi dan menarik — mis. warna, ukuran font, jarak, dan layout.


---

🧭 Selector utama

Terdapat tiga selector yang sering dipakai:

Selector elemen — menargetkan tag HTML langsung (contoh: p, h1)

Selector class (.namaClass) — untuk beberapa elemen yang berbagi gaya sama

Selector id (#namaID) — untuk elemen yang unik pada satu halaman



---

🛠️ Cara menerapkan CSS

1. CSS Internal

Dituliskan di dalam tag <style> pada file HTML:

<head>
  <style>
    body { font-family: Arial, sans-serif; }
    .teks-merah { color: #e74c3c; }
  </style>
</head>

2. CSS Eksternal

Ditulis di file terpisah (mis. style.css) dan di-link di HTML:

<!-- index.html -->
<head>
  <link rel="stylesheet" href="style.css">
</head>

/* style.css */
h1 { font-size: 28px; }
.container { max-width: 900px; margin: 0 auto; padding: 20px; }
