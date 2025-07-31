# UAS-RNN-Anjeli-dan-Hafizh-Kecerdasan-Buatan-Kelas-D-2025-
# 🧠 Forecasting Konsumsi Daya Listrik Harian Menggunakan RNN

Proyek ini merupakan bagian dari Ujian Akhir Semester (UAS) mata kuliah **Kecerdasan Buatan - Kelas D (2025)** oleh Anjeli dan Hafizh. Kami menggunakan model **Recurrent Neural Network (RNN)** untuk memprediksi konsumsi daya listrik harian berbasis data time series.

## 📁 Struktur Proyek
UAS-RNN-Anjeli-dan-Hafizh-Kecerdasan-Buatan-Kelas-D-2025/
├── forecasting_beban_listrik_rnn.ipynb
├── dataset/
│ └── beban_listrik_harian.csv
├── hasil_visualisasi/
│ ├── train_vs_test.png
│ └── prediksi_rnn.png
├── laporan/
│ └── laporan_final.pdf
└── README.md


## 📊 Dataset

Dataset yang digunakan berupa konsumsi beban listrik harian dalam format `.csv`. Dataset telah diproses dan diskalakan sebelum digunakan dalam model pembelajaran.

## ⚙️ Teknologi dan Library

Proyek ini dibangun menggunakan:

- Python 3.x
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## 🚀 Instalasi & Eksekusi

Tidak perlu instalasi lokal. Anda cukup membuka notebook pada Google Colab.

### Langkah-langkah:

1. Buka file `forecasting_beban_listrik_rnn.ipynb` di Google Colab.
2. Upload dataset `beban_listrik_harian.csv` ke session Colab.
3. Jalankan sel kode secara berurutan.
4. Visualisasi hasil pelatihan dan prediksi akan ditampilkan di akhir proses.

> 📎 Jika ingin dijalankan secara lokal, pastikan semua dependensi telah diinstal:

```bash
pip install numpy pandas scikit-learn matplotlib tensorflow

📈 Output
Visualisasi meliputi:

Perbandingan data latih dan data uji

Plot hasil prediksi model RNN

Evaluasi loss model

👥 Kontributor
Anjeli Rizki Syamiaputri (202331065)
Hafizh Hilman Asyhari (202331206)
