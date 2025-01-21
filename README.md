# Klasifikasi-Objek-CNN

Proyek ini bertujuan untuk melakukan klasifikasi objek orang dengan 5 label orang menggunakan **Convolutional Neural Network (CNN)**. Model ini dibangun menggunakan dataset yang telah diaugmentasi, dan proyek ini mencakup langkah-langkah mulai dari pembangunan lingkungan pemrograman hingga evaluasi model.

## Penjelasan

Dalam Project saya ini, saya menunjukkan langkah-langkah membangun model CNN untuk klasifikasi objek orang. Proyek ini melibatkan penggunaan dataset sendiri, yang kemudian diaugmentasi dan dibagi menjadi tiga bagian: **train**, **validation**, dan **test**. Proses ini juga mencakup pembangunan lingkungan pemrograman menggunakan Anaconda dan Jupyter Notebook.

### 1. Pembangunan Lingkungan Pemrograman
- Instalasi Anaconda untuk manajemen lingkungan.
- Pengaturan Jupyter Notebook sebagai IDE.
- Instalasi library utama seperti TensorFlow, NumPy, Matplotlib, dan OpenCV menggunakan conda dan pip.
- Persiapan dataset dengan struktur folder yang mendukung proses pelatihan.

### 2. Penjelasan Konsep CNN dan Dataset Augmentasi
- Penjelasan struktur CNN: konvolusi, pooling, dan fully connected layers.
- Peran augmentasi dataset untuk memperkaya data latih dan mencegah overfitting.
- Pembagian dataset menjadi train, validation, dan test serta penggunaannya:
  - **Train**: Melatih model.
  - **Validation**: Mengevaluasi performa model selama training untuk membantu mendeteksi overfitting atau underfitting.
  - **Test**: Mengevaluasi/menguji performa akhir model.

### 3. Implementasi Model CNN
- Membuat model CNN sederhana menggunakan Keras dengan TensorFlow di Jupyter Notebook.
- Augmentasi dataset menggunakan **ImageDataGenerator**.
- Melatih model pada dataset yang telah diproses.
- Visualisasi proses pelatihan seperti loss dan akurasi.

### 4. Evaluasi dan Refleksi
- Tampilkan hasil klasifikasi pada dataset test dengan lima label/orang.
- Analisis performa model menggunakan akurasi, confusion matrix, atau metrik lainnya.
- Refleksi mengenai tantangan selama pengerjaan dan solusi yang diterapkan.

## Tools dan Library yang Digunakan
- **Anaconda Distribution**: Untuk pengelolaan lingkungan pemrograman.
- **Jupyter Notebook**: IDE utama untuk menulis dan menjalankan kode.
- **Python 3.12**: Bahasa pemrograman utama.
- **TensorFlow dan Keras**: Untuk membangun dan melatih model CNN.
- **NumPy**: Untuk manipulasi data numerik.
- **Matplotlib**: Untuk visualisasi data dan hasil klasifikasi.
- **OpenCV**: Untuk memuat dan memproses gambar dataset.
- **ImageDataGenerator**: Untuk augmentasi dataset.

## 📂 Kode Sumber
Anda dapat mengunduh kode sumber melalui tautan berikut:
[Google Drive - Kode Sumber](https://drive.google.com/drive/u/3/folders/1huEZawR7t60hdvcxaJcL3Z9YcVfXmwHl)

## ⚙️ Model dan Hasil Klasifikasi
Model yang telah dilatih dan hasil klasifikasi dapat diunduh melalui Google Drive di bawah ini:
[Google Drive - Model](https://drive.google.com/drive/u/3/folders/1huEZawR7t60hdvcxaJcL3Z9YcVfXmwHl)

## Instruksi Penggunaan
1. Buat dataset dengan 5 label/class dan tempatkan di satu folder yang sama.
2. Instal semua dependensi yang tercantum dalam `requirements.txt` dengan perintah:
    ```bash
    pip install -r requirements.txt
    ```
3. Buka file `Training.ipynb` di Jupyter Notebook untuk melatih model.
4. Setelah pelatihan selesai, Anda dapat menggunakan model yang telah dilatih untuk melakukan prediksi.

## License
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

