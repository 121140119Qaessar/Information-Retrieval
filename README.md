# Sistem Pencarian Dokumen Ilmiah

Sistem pencarian dokumen ilmiah menggunakan metode TF-IDF dan SBERT untuk menemukan dokumen yang relevan berdasarkan kueri pengguna.

## Persiapan Dataset

### Dataset arXiv
Aplikasi ini menggunakan dataset paper ilmiah arXiv. Untuk menjalankan kode dengan benar:

1. Unduh dataset "arXiv_scientific dataset.csv"
2. Buat folder `Data` di direktori utama (jika belum ada)
3. Tempatkan file CSV di folder `./Data/`

Struktur folder yang benar:
```
└── Information Retrieval/
    └── Tubes/
        ├── Data/
        │   └── arXiv_scientific dataset.csv
        ├── Tubes.ipynb
        └── readme.md
```

## Fitur Utama

- Preprocessing teks dengan lemmatization
- Vektorisasi menggunakan TF-IDF
- Vektorisasi menggunakan SBERT (Sentence-BERT)
- Perhitungan similaritas berbasis cosine similarity
- Evaluasi performa dengan metrics precision, recall, MAP, dan nDCG
- Antarmuka pencarian interaktif

## Cara Menjalankan

1. Pastikan dataset sudah diletakkan sesuai petunjuk di atas
2. Install dependencies yang diperlukan:
   ```
   pip install -r requirements.txt
   ```
3. Buka dan jalankan file notebook `IR.ipynb` menggunakan Jupyter Notebook atau Visual Studio Code
4. Jalankan seluruh sel kode secara berurutan
5. Gunakan antarmuka pencarian interaktif di bagian akhir notebook
