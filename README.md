# Tempry 🖼️

**Tempry** adalah website artikel statis dengan gambar menarik. Dibuat dengan HTML, CSS, dan JavaScript murni — tanpa framework.

## Struktur Proyek

```
tempry/
├── index.html      # Halaman beranda + daftar artikel terbaru
├── artikel.html    # Halaman detail artikel dengan gambar
├── css/
│   └── style.css   # Seluruh styling (responsive)
└── js/
    └── script.js   # Animasi fade-in & smooth scroll
```

## Fitur

- ✅ Halaman beranda dengan hero section + gambar
- ✅ Kartu artikel responsif (grid otomatis)
- ✅ Halaman detail artikel lengkap dengan konten & gambar
- ✅ Animasi fade-in saat scroll (Intersection Observer)
- ✅ Smooth scroll & sticky header
- ✅ Sepenuhnya responsif (mobile-first friendly)

## Cara Menjalankan

Buka langsung `index.html` di browser, atau jalankan server lokal:

```bash
npx serve .
# atau
python -m http.server 8000
```

Lalu buka `http://localhost:8000`.

## Catatan

Gambar menggunakan placeholder dari [picsum.photos](https://picsum.photos). Ganti dengan aset gambarmu sendiri sesuai kebutuhan.
