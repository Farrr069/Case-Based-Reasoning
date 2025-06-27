Case-Based Reasoning (CBR) Project

Proyek ini menunjukkan penerapan Case-Based Reasoning (CBR) untuk analisis kasus hukum, yang meliputi pembersihan data, representasi kasus, retrieval, dan prediksi.

Struktur Proyek
Case-Based-Reasoning/
│
├── data/                  # Data mentah & data yang telah diproses
│   ├── raw/               # Data mentah (file PDF, HTML, dll.)
│   └── processed/         # Data yang telah diproses (CSV, JSON)
│
├── notebooks/             # Jupyter notebook untuk setiap tahap
│   ├── (UAS_PENALARAN_KOMPUTER.ipynb)
│   
├── README.md              # Deskripsi proyek dan instruksi penggunaan
└── requirements.txt       # Daftar dependensi untuk proyek


Instalasi

Ikuti langkah-langkah berikut untuk menyiapkan lingkungan dan menjalankan proyek:

1. Clone repository:

git clone https://github.com/username/Case-Based-Reasoning.git
cd Case-Based-Reasoning

2. Install dependensi:
Install dependensi yang diperlukan dengan menjalankan perintah berikut:

pip install -r requirements.txt

Ini akan menginstall library yang dibutuhkan seperti:
• pandas
• numpy
• scikit-learn
• matplotlib
• seaborn
• PyPDF2

Struktur Folder

• /data/: Berisi data mentah dan data yang sudah diproses.
    • /data/raw/: Data mentah (file PDF, HTML, dll.)
    • /data/processed/: Data yang telah diproses dalam format CSV dan JSON.
• /notebooks/: Folder untuk Jupyter notebooks tiap tahap proyek.
    • (UAS_PENALARAN_KOMPUTER.ipynb) : tahap dari awal untuk membangun case base sampai  Tahap untuk evaluasi performa model menggunakan metrik seperti akurasi, presisi, recall,   dan F1-score.
    
Penggunaan

1. Jalankan notebooks:
    • Langsung buka file notebook dan jalankan sel satu persatu:
        1. UAS_PENALARAN_KOMPUTER.ipynb

2. Data:
    • Data mentah dapat ditemukan di folder /data/raw/, sementara data yang telah diproses akan disimpan di folder /data/processed/.
    • Setiap notebook akan menghasilkan file CSV dan JSON yang diperlukan untuk analisis lebih lanjut.

3. Hasil Akhir:
    • Prediksi: Setelah menjalankan notebook prediksi, hasil prediksi kasus model akan disimpan di /data/results/predictions.csv.





