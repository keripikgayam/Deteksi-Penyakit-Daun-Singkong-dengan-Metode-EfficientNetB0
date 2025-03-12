# Skripsi Deteksi Penyakit Daun Singkong dengan Metode EfficientNetB0
Proyek ini bertujuan untuk mengembangkan sistem deteksi otomatis untuk penyakit daun pada tanaman singkong (Manihot esculenta). Penyakit daun merupakan ancaman serius yang dapat mengurangi hasil panen dan kualitas tanaman singkong. Dengan menggunakan teknik deep learning, khususnya arsitektur Convolutional Neural Network (CNN) EfficientNetB0, proyek ini mampu mengklasifikasikan citra daun singkong ke dalam beberapa kategori penyakit dan daun sehat. Penelitian ini menggunakan dataset yang dapat dilihat sebagai berikut https://www.kaggle.com/competitions/cassava-leaf-disease-classification/data .

## Deskripsi
Sistem ini menggunakan dataset citra daun singkong yang dikumpulkan dari platform Kaggle. Dataset ini terdiri dari citra daun yang diklasifikasikan ke dalam lima kategori:
- Cassava Bacterial Blight (CBB)
- Cassava Brown Streak Disease (CBSD)
- Cassava Green Mottle (CGM)
- Cassava Mosaic Disease (CMD)
- Daun Sehat (healthy)
Model EfficientNetB0 dipilih karena efisiensi komputasinya dan kemampuannya untuk bekerja dengan dataset besar. Model ini dilatih menggunakan teknik augmentasi data untuk meningkatkan variasi sampel dan meningkatkan akurasi.

## Fitur
- Deteksi otomatis penyakit daun singkong menggunakan deep learning.
- Klasifikasi citra ke dalam lima kategori penyakit dan daun sehat.
- Penggunaan arsitektur EfficientNetB0 yang efisien dan akurat.
- Pelatihan model menggunakan dataset dari Kaggle.
- Evaluasi model dengan metrik akurasi, presisi, recall, dan F1-score.

## Teknologi
- Python
- TensorFlow/Keras
- EfficientNetB0

## Hasil
Model yang dikembangkan mencapai akurasi tinggi dalam mengklasifikasikan penyakit daun singkong. Hasil evaluasi menunjukkan bahwa EfficientNetB0 secara signifikan lebih unggul dibandingkan model CNN dasar dan ResNet50.

## Penggunaan
Proyek ini dapat digunakan oleh petani, peneliti, dan pengembang aplikasi pertanian untuk memantau kesehatan tanaman singkong secara otomatis dan mendeteksi penyakit secara dini.

## Kata Kunci
Deteksi penyakit, Manihot Esculenta, EfficientNetB0, Convolutional Neural Network, klasifikasi citra, deep learning.
