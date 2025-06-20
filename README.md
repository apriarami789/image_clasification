# Klasifikasi Gambar Satelit - RSI-CB256

Proyek ini bertujuan untuk melakukan klasifikasi gambar citra satelit menggunakan dataset RSI-CB256. Dataset berisi gambar citra satelit dari berbagai kelas objek dan digunakan untuk melatih model deep learning klasifikasi gambar.

## 📌 Informasi Pembuat

- **Nama:** Mhd. Apri Arami  
- **Email:** mhd.118290047@student.itera.ac.id  
- **ID Dicoding:** apriarami718

## 📂 Dataset

Dataset digunakan dari Kaggle:  
🔗 [Satellite Image Classification Dataset](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification/data)

Dataset ini terdiri dari gambar beresolusi 256x256 piksel dalam berbagai kategori (seperti jalan, bangunan, air, vegetasi, dll).

## 🛠️ Teknologi dan Library

Notebook ini menggunakan beberapa pustaka berikut:

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- OpenCV (jika digunakan untuk augmentasi gambar)

## 📊 Tujuan dan Proses

1. **Eksplorasi Dataset**: Visualisasi dan analisis distribusi gambar.
2. **Preprocessing**: Resize gambar, augmentasi, dan normalisasi.
3. **Pembuatan Model CNN**: Menggunakan arsitektur CNN untuk klasifikasi.
4. **Training dan Evaluasi**: Melatih model dan mengevaluasi akurasi pada data validasi.
5. **Visualisasi**: Menampilkan kurva akurasi dan loss.

## 🚀 Cara Menjalankan

1. Clone repositori ini:
    ```bash
    git clone https://github.com/username/repo-anda.git
    cd repo-anda
    ```

2. Jalankan Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

3. Buka file `KlasifikasiGambar_Mhd_ApriArami.ipynb` dan jalankan sel satu per satu.

> **Catatan**: Anda perlu mengunduh dataset dari Kaggle dan meletakkannya di direktori yang sesuai sebelum menjalankan notebook.

## 📈 Hasil

Notebook ini memberikan hasil berupa akurasi klasifikasi citra satelit dan menampilkan prediksi dari model CNN terhadap data uji.

---


