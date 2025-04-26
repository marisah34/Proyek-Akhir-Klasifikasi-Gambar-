# Proyek-Akhir-Klasifikasi-Gambar-

# Deskripsi
Proyek ini bertujuan untuk membangun model klasifikasi gambar yang dapat membedakan tiga jenis objek: Plastic, Paper, dan Garbage Bag. Proyek dikembangkan menggunakan TensorFlow dan Keras, dengan tahapan mulai dari persiapan data hingga konversi model ke berbagai format deployment.

1. Struktur Proyek
Import Library
Menggunakan berbagai library seperti TensorFlow, Keras, scikit-image, OpenCV, dan lainnya untuk preprocessing dan training.

2. Persiapan Data

- Load dataset dari file ZIP.

- Melakukan eksplorasi data awal.

3. Preprocessing Data

- Resize gambar.

- Augmentasi gambar (rotation, noise, gamma adjustment, dll).

- Split dataset menjadi training, validation, dan testing.

4. Pembangunan Model

- Membuat model CNN menggunakan Sequential.

- Menggunakan Conv2D, MaxPooling2D, dan Dense Layers.

- Menerapkan callbacks seperti EarlyStopping dan ModelCheckpoint.

5. Evaluasi Model

- Menggunakan confusion matrix dan classification report.

- Visualisasi akurasi dan loss training.

6.Konversi Model

Menyimpan model ke format:

- TensorFlow SavedModel

- TensorFlow Lite (.tflite)

- TensorFlow.js (.json dan .bin)

7. Inference (Opsional)

- Mencoba prediksi menggunakan model yang sudah dilatih.
