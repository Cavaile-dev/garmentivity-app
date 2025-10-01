# Garmentivity App - Employee Productivity Predictor 
Aplikasi machine learning untuk memprediksi apakah seorang karyawan masuk ke dalam kategori produktif atau tidak menggunakan pengembangan model **CatBoostClassifier**.

---

## Latar Belakang
Tim kerja di industri sering memiliki performa yang bervariasi (produktif dan tidak produktif). Namun sampai saat ini, penilaian produktivitas masih banyak dilakukan secara manual dan subjektif. Maka dari itu dibutuhkan sistem otomatis yang mampu mengklasifikasikan produktivitas tim kerja untuk mendukung evaluasi dan pengambilan keputusan.

## Tujuan Projek
Tujuan dari projek ini adalah 
1. Mengidentifikasi fitur-fitur penting yang mempengaruhi produktivitas tim kerja (misalnya jumlah pekerja, SMV, idle time, lembur, dll).
2. Mengembangkan model klasifikasi menggunakan model Cat Boost Classifier yang cocok untuk data dengan fitur kategorikal.
3. Menguji akurasi dan kinerja model menggunakan metrik evaluasi seperti akurasi, precision, recall, dan f1-score.
4. Memberikan rekomendasi tindakan bagi HRD berdasarkan hasil klasifikasi, seperti pengecekan idle time atau alokasi SDM.

## Dataset
Dataset yang dikumpulkan dan dipakai adalah Productivity Prediction of Garment Employees yang diperoleh dari UC Irvine Machine Learning Repository (Al Imran, A., Rahim, M. S., & Ahmed, T., 2021).

## Pemilihan Algoritma
Kami menggunakan model Cat Boost Classifier karena algoritma ini dirancang untuk meminimalkan overfitting melalui pendekatan gradient boosting yang unik, yang bermanfaat dalam skenario dengan data yang terbatas (Wang et al., 2024). 

## Web Application
<img src="\images\tampilan_app.JPG" alt="Preview" width="600"/>
<img src="\images\contoh_predict.JPG" alt="Preview" width="600"/>

## Hasil Prediksi
- Model akan menampilkan apakah karyawan tersebut produktif atau tidak.
- Diberikan rekomendasi untuk HR untuk step selanjutnya berdasarkan kinerja karyawannya
