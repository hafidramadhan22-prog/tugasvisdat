# Visdat Gaming — Video Game Sales Explorer

> Dashboard modern dan responsif untuk mengeksplorasi **150 record platform-rilis** dengan `Global_Sales` tertinggi dari dataset *Video Games Sales*.

🌐 Demo: `https://finalproject-visdat.vercel.app/`


## Fitur Dashboard

- Pencarian berdasarkan judul game atau penerbit.
- Filter genre dan platform.
- Tab metrik: Global, North America, Europe, Japan, dan Other Sales.
- Pilihan ranking Top 5, Top 10, atau Top 15.
- Empat chart interaktif: ranking, komposisi genre, tren tahun rilis, dan distribusi wilayah.
- Klik irisan doughnut untuk memfilter genre.
- Tooltip, animasi entrance Chart.js, count-up KPI, dan insight otomatis.
- Tabel detail delapan record teratas.
- Layout responsif untuk laptop dan HP.

## Sumber dan Ruang Lingkup Data

- Nama dataset: **Video Games Sales**
- Penerbit dataset: Gregory Smith melalui Zenodo
- Asal data: hasil pengambilan data VGChartz
- URL: https://zenodo.org/records/5898311
- Dataset sumber: **16.598 record**
- Data pada dashboard: **150 record platform-rilis** dengan `Global_Sales` tertinggi
- Judul unik pada subset: **136 judul**
- Rentang tahun subset: **1982–2015**
- Satuan penjualan: **juta kopi**

### Catatan Interpretasi

Satu judul dapat muncul pada beberapa baris apabila dirilis di platform berbeda. Semua insight hanya berlaku pada subset top 150 dan tidak mewakili seluruh industri video game atau kondisi pasar terkini.

## Struktur Folder

```text
tugasvisdat/
├── index.html
├── style.css
├── app.js
├── vgsales_snapshot_top150.csv
├── CATATAN_DATA.md
└── README.md

## Menjalankan di Lokal

Gunakan ekstensi **Live Server** di Visual Studio Code, atau jalankan:

```bash
python -m http.server 3000
```

Kemudian buka `http://localhost:3000`. Chart.js dan font dipanggil melalui CDN sehingga koneksi internet diperlukan.

## Deploy ke Vercel

1. Buat repository GitHub publik.
2. Unggah seluruh file project ke root repository GitHub.
3. Import repository pada Vercel.
4. Pilih preset **Other/Static** tanpa build command.
5. Klik **Deploy**.
6. Uji URL melalui HP dan perangkat lain.
7. Ganti URL placeholder pada README, laporan, dan slide.

## Teknologi

- HTML
- CSS
- JavaScript
- Chart.js melalui CDN
- Vercel

## Anggota Kelompok

- M Hafid Ramadhan — 103012330194
- Akbar Jundi Pradita — 103012300081
- Muhammad Rifqi Syahban Arzakhy — 103012300418
- Muhammad Alivio Putra — 103012300098
- Farrel Musyaffa — 103012300147
