# Catatan Dataset

## Unit Analisis

Setiap baris pada `vgsales_snapshot_top150.csv` adalah satu **record platform-rilis**. Sebuah judul dapat muncul beberapa kali apabila tersedia pada platform yang berbeda. Snapshot berisi 150 record dan 136 judul unik.

## Cara Snapshot Dibentuk

1. Dataset sumber memiliki 16,598 record.
2. Data diurutkan menurun menggunakan variabel `Global_Sales`.
3. Diambil 150 record teratas.
4. Snapshot yang digunakan tidak memiliki nilai kosong dan tidak memiliki baris duplikat identik.

## Variabel

- `Rank`: peringkat pada dataset sumber.
- `Name`: judul game.
- `Platform`: platform rilis.
- `Year`: tahun rilis.
- `Genre`: genre.
- `Publisher`: penerbit.
- `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`: penjualan regional dalam juta kopi.
- `Global_Sales`: penjualan global dalam juta kopi.

## Batasan Interpretasi

- Pemilihan top 150 menimbulkan bias menuju game berpenjualan tinggi.
- Agregasi per genre, platform, dan tahun hanya menjelaskan subset ini.
- Data bersifat historis dengan rentang 1982-2015.
- Data berasal dari VGChartz yang dipublikasikan ulang melalui Zenodo, sehingga digunakan untuk eksplorasi visualisasi dan bukan laporan resmi perusahaan.
