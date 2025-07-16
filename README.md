# Analisis Sentimen Ulasan Masyarakat Indonesia

Proyek ini merupakan bagian dari Capstone Project yang bertujuan untuk menganalisis opini publik masyarakat Indonesia melalui data media sosial menggunakan teknologi kecerdasan buatan (AI) dan pemrosesan bahasa alami (NLP). Analisis dilakukan pada tweet berbahasa Indonesia dengan memanfaatkan model IBM Granite untuk klasifikasi sentimen dan peringkasan informasi.

## Dataset

Dataset diambil dari Kaggle:
https://www.kaggle.com/datasets/alvinhanafie/dataset-for-indonesian-sentiment-analysis

Dataset ini berisi tweet berbahasa Indonesia yang telah diberi label sentimen:
- Positif
- Negatif
- Netral

## Teknologi dan Tools

- Python (Google Colab)
- Sastrawi (Library NLP Bahasa Indonesia)
- IBM Granite LLM API
- Matplotlib, Seaborn (visualisasi)
- WordCloud
- Scikit-learn
- Pandas

## Tahapan Analisis

1. **Pengumpulan dan Pembersihan Data**
   - Menghapus URL, emoji, dan karakter khusus
   - Tokenisasi dan penghapusan stopwords

2. **Exploratory Data Analysis (EDA)**
   - Visualisasi distribusi data sentimen
   - Wordcloud untuk masing-masing kategori sentimen

3. **Klasifikasi Sentimen**
   - Menggunakan model IBM Granite untuk klasifikasi ulang
   - Evaluasi menggunakan metrik akurasi dan confusion matrix

4. **Peringkasan Informasi**
   - Menghasilkan ringkasan teks dari masing-masing kategori sentimen menggunakan kemampuan LLM

## Temuan Utama

- Tweet positif banyak muncul dalam konteks pujian terhadap pemerintah, layanan publik, dan acara olahraga.
- Tweet negatif didominasi oleh isu sosial seperti kemacetan, kenaikan harga, dan layanan publik yang kurang baik.
- Tweet netral umumnya berupa berita atau opini informatif tanpa nada emosional.
- Model IBM Granite menunjukkan akurasi klasifikasi sekitar 85% dan mampu memberikan ringkasan yang relevan.

## Rekomendasi

- Pemerintah dan lembaga sosial dapat memanfaatkan AI untuk memantau opini publik secara rutin.
- Data sentimen dapat dijadikan indikator awal terhadap isu-isu sensitif atau viral.
- Perusahaan dan lembaga riset dapat menggunakan metode ini untuk menganalisis umpan balik pelanggan dan persepsi merek.

## Informasi Penulis

Nama: Nela Eka Silvia Lumbanraja  
Email: nelanaingolan43@gmail.com  
Tanggal: 16 Juli 2026

## File dalam Repositori

- `SentiWatch_Analisis_Sentimen_Publik_Indonesia.ipynb`: Notebook utama proyek
- `README.md`: Penjelasan proyek ini

## Lisensi

Proyek ini disusun untuk keperluan edukasi dan tidak dimaksudkan untuk tujuan komersial. Hak cipta atas dataset dan layanan AI sepenuhnya dimiliki oleh penyedia masing-masing.
