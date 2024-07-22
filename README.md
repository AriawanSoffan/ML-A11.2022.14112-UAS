# Prediksi Diabetes Menggunakan K-Nearest Neighbors

## 1. Judul / Topik Project dan Identitas Lengkap
**Judul:** Prediksi Diabetes Menggunakan K-Nearest Neighbors  
**Identitas:**  
- Nama: Ariawan Soffan Farajaya
- NIM: A11.2022.14112

## 2. Ringkasan dan Permasalahan Project + Tujuan yang Akan Dicapai + Model / Alur Penyelesaian
### Ringkasan
Proyek ini bertujuan untuk membangun model prediksi diabetes menggunakan algoritma K-Nearest Neighbors (KNN). Data yang digunakan adalah dataset diabetes dari Pima Indian. Prediksi diabetes penting untuk deteksi dini dan pengelolaan penyakit ini.

### Permasalahan
Diabetes adalah penyakit kronis yang dapat menyebabkan komplikasi serius jika tidak terdeteksi dan dikelola dengan baik. Tujuan proyek ini adalah membangun model yang dapat memprediksi apakah seseorang mengidap diabetes berdasarkan sejumlah fitur klinis.

### Tujuan
1. Menganalisis dataset diabetes.
2. Melakukan pra-pemrosesan data dan feature engineering.
3. Melatih dan mengevaluasi model K-Nearest Neighbors untuk prediksi diabetes.
4. Mengoptimalkan hyperparameter model untuk meningkatkan akurasi.

### Model / Alur Penyelesaian

```mermaid
graph TD
    A[Mulai] --> B[Impor Data]
    B --> C[Exploratory Data Analysis (EDA)]
    C --> D[Pembersihan Data]
    D --> E[Membuat Fitur Turunan]
    E --> F[Standarisasi Fitur]
    F --> G[Split Data Training dan Testing]
    G --> H[Melatih Model KNN]
    H --> I[Optimisasi Hyperparameter]
    I --> J[Evaluasi Model]
    J --> K[Kesimpulan]
    K --> L[Selesai]
```

## 3. Penjelasan Dataset, EDA dan Proses Features Dataset
### Dataset
Dataset yang digunakan adalah dataset diabetes dari Pima Indian yang tersedia secara publik. Dataset ini terdiri dari beberapa fitur klinis seperti jumlah kehamilan, kadar glukosa, tekanan darah, ketebalan kulit, insulin, BMI, riwayat diabetes keluarga, dan usia.

### Exploratory Data Analysis (EDA)
EDA dilakukan untuk memahami distribusi data, mengidentifikasi outliers, dan menemukan hubungan antar fitur. Beberapa langkah yang dilakukan dalam EDA:
- Menampilkan statistik deskriptif dari dataset.
- Membuat visualisasi data seperti histogram, box plot, dan pair plot.
- Mengidentifikasi missing values.

### Proses Features Dataset
1. **Pembersihan Data:** Menghapus atau mengimputasi missing values.
2. **Membuat Fitur Turunan:** Menghasilkan fitur baru yang mungkin lebih relevan.
3. **Standarisasi Fitur:** Menstandarisasi fitur untuk memastikan semua fitur memiliki skala yang sama.

## 4. Proses Learning / Modeling
Modeling dilakukan menggunakan algoritma K-Nearest Neighbors (KNN). Proses ini melibatkan:
1. Membagi dataset menjadi data training dan testing.
2. Melakukan oversampling menggunakan SMOTE untuk menangani ketidakseimbangan kelas.
3. Melatih model KNN dengan data training.
4. Melakukan validasi silang menggunakan nested cross-validation untuk menghindari overfitting.
5. Mengoptimalkan hyperparameter model menggunakan GridSearchCV.

## 5. Performa Model
Evaluasi model dilakukan dengan mengukur akurasi, precision, recall, dan F1-score pada data testing. Hasil evaluasi menunjukkan bahwa model KNN mampu memprediksi diabetes dengan cukup baik. Berikut adalah hasil evaluasi model:

- **Akurasi:** [nilai akurasi]
- **Precision:** [nilai precision]
- **Recall:** [nilai recall]
- **F1-score:** [nilai F1-score]

## 6. Diskusi Hasil dan Kesimpulan
### Diskusi Hasil
Model KNN menunjukkan performa yang baik dalam memprediksi diabetes. Namun, ada beberapa hal yang perlu diperhatikan:
- Ketidakseimbangan kelas masih menjadi tantangan meskipun sudah dilakukan oversampling.
- Akurasi model dapat ditingkatkan dengan melakukan feature engineering lebih lanjut dan mencoba algoritma lain.

### Kesimpulan
Proyek ini berhasil membangun model prediksi diabetes menggunakan KNN dengan performa yang cukup baik. Penggunaan teknik oversampling dan validasi silang membantu meningkatkan akurasi model. Langkah selanjutnya adalah melakukan pengujian dengan algoritma lain dan lebih banyak eksperimen feature engineering untuk meningkatkan performa model.

---

Anda bisa menambahkan informasi tambahan atau modifikasi sesuai dengan kebutuhan proyek Anda.
