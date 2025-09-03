# Support-Vector-Machine-Implementation-for-YouTube-Sentiment-Analysis-on-Retina-Data-Trade
Implementation of SVM Algorithm for YouTube Sentiment Analysis on Retina Data Trade

## Deskripsi  
Repositori ini berisi implementasi **algoritma Support Vector Machine (SVM)** untuk melakukan **analisis sentimen pada komentar YouTube** terkait isu warga yang rela menyerahkan data retina demi uang. Proyek ini mencakup tahap **pengumpulan data, preprocessing teks, pelabelan sentimen, training model, serta evaluasi performa algoritma SVM**.  

## Fitur Utama  
- Pengambilan data komentar dari YouTube.  
- Pembersihan dan preprocessing teks (stopword removal, tokenisasi, stemming).  
- Klasifikasi sentimen (positif, negatif, netral).  
- Implementasi algoritma **Support Vector Machine (SVM)**.  
- Evaluasi performa model menggunakan metrik akurasi, presisi, recall, dan F1-score.  

## Struktur Folder  
```bash
├── data/              # Dataset komentar YouTube
├── src/               # Notebook preprocessing & training
├── results/           # Hasil evaluasi model
└── README.md          # Dokumentasi proyek
```

## Instalasi & Penggunaan  
1. Clone repositori ini:  
   ```bash
   git clone https://github.com/username/Sentiment-Analysis-YouTube-Retina-Data-Trade-SVM.git
   cd Sentiment-Analysis-YouTube-Retina-Data-Trade-SVM
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Buat API Key YouTube Data API v3  
   - Buka [Google Cloud Console](https://console.cloud.google.com/)  
   - Aktifkan **YouTube Data API v3**  
   - Buat API Key baru  
   - Simpan API key tersebut di variabel dalam notebook sebelum menjalankan *crawling data*, contoh:
     ```python
     api_key = "MASUKKAN_API_KEY_DI_SINI"
     ```

4. Jalankan notebook atau script:  
   ```bash
   jupyter notebook notebooks/SentimentAnalysis_Retina_SVM.ipynb
   ```

## Dataset  
Dataset berupa komentar publik dari YouTube yang membahas isu penyerahan data retina untuk uang. Data diproses melalui tahap preprocessing sebelum digunakan untuk training model.  

## Hasil & Evaluasi  
Model SVM dievaluasi dengan metrik klasifikasi:  

| Metrik    | Nilai |
|-----------|-------|
| Akurasi   | 0.87  |
| Presisi   | 0.85  |
| Recall    | 0.86  |
| F1-Score  | 0.85  |

Hasil evaluasi dapat dilihat di folder `results/`.  