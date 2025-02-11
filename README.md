# Hate Speech Detection NLP

Proyek ini bertujuan untuk mendeteksi hate speech pada platform media sosial dengan menerapkan Sentiment Analysis dan Natural Language Processing (NLP). Dengan meningkatnya ujaran kebencian secara online, model ini membantu mengidentifikasi postingan yang mengandung ujaran kebencian, pelecehan, atau diskriminasi, sehingga dapat digunakan untuk moderasi konten atau penelitian sosial.

Langkah-Langkah Proyek
1. Pengumpulan Data
   - Scraping atau menggunakan dataset publik (misalnya dari Kaggle atau Twitter API).
   - Data terdiri dari teks dengan label hate speech atau non-hate speech.

2. Preprocessing Data
   - Cleansing: Menghapus tanda baca, URL, angka, dan emoji.
   - Tokenisasi & Lemmatization: Memecah teks menjadi kata-kata dasar.
   - Stopword Removal: Menghapus kata umum yang tidak memiliki arti sentimen.

3. Labeling Data
   - Menggunakan dataset yang sudah terlabel atau crowdsourcing untuk anotasi manual.
   - Label kategori: Hate Speech, Offensive Speech, atau Neutral Speech.

4. Pelatihan Model
   - Menggunakan model Machine Learning (Naïve Bayes, SVM, Random Forest) atau Deep Learning (LSTM, BERT, Transformer-based models).
   - Melatih model dengan data latih yang sudah diproses.

5. Evaluasi Model
   - Menggunakan accuracy, precision, recall, F1-score untuk mengukur kinerja model.
   - Menganalisis misclassification dan meningkatkan model jika diperlukan.

6. Visualisasi & Deployment
   - Menampilkan hasil analisis dalam bentuk grafik tren hate speech pada media sosial.
