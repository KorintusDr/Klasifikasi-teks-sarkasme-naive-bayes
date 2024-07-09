# Deteksi Sarkasme menggunakan Naive Bayes

## Deskripsi
Proyek ini bertujuan untuk mengembangkan model yang dapat mendeteksi teks sarkastik menggunakan teknik Natural Language Processing (NLP) dengan algoritma Naive Bayes. Dataset yang digunakan berisi judul-judul artikel berita yang sudah diberi label apakah bersifat sarkastik atau tidak.

## Langkah-langkah
1. **Persiapan Data**: Memuat dataset `Sarcasm.json` yang berisi judul-judul artikel beserta labelnya.
2. **Preprocessing**: Mengubah teks menjadi representasi numerik menggunakan `CountVectorizer`.
3. **Pembagian Data**: Memisahkan data menjadi data latih dan data uji dengan `train_test_split`.
4. **Pelatihan Model**: Menggunakan model Naive Bayes (BernoulliNB) untuk melatih data latih.
5. **Evaluasi Model**: Mengukur akurasi model menggunakan data uji.
6. **Prediksi**: Meminta pengguna untuk memasukkan teks baru dan memprediksi apakah teks tersebut sarkastik atau tidak.

## Kebutuhan
- Python 3.x
- Pandas
- NumPy
- Scikit-learn

## Cara Jalankan File 
1. Pastikan Anda telah menginstal Python dan semua library yang diperlukan seperti yang disebutkan di atas.
2. Unduh atau clone repository proyek ini ke dalam lokal komputer Anda.
3. Buka terminal atau command prompt, lalu arahkan ke direktori di mana file IPython Notebook (`main.ipynb`) disimpan.
4. Jalankan Jupyter Notebook dengan mengetikkan perintah:
5. Jelajahi dan buka file `main.ipynb` dari antarmuka Jupyter Notebook.
6. Jalankan seluruh cell di notebook atau jalankan cell per cell sesuai kebutuhan.
7. Ikuti petunjuk di notebook untuk memasukkan teks yang ingin Anda prediksi dan lihat hasil prediksi dari model.

