🧠 Credit Card Fraud Detection — Deep Learning VGG16
Proyek ini adalah implementasi deep learning menggunakan arsitektur VGG16 untuk mendeteksi transaksi kartu kredit yang berpotensi sebagai fraud. Model dibangun dengan TensorFlow/Keras dan dataset transaksi kartu kredit. Cocok untuk pembelajaran machine learning, penelitian, maupun implementasi sistem deteksi penipuan finansial.
---
📂 Struktur File
| File                        | Deskripsi                                                          |
| --------------------------- | ------------------------------------------------------------------ |
| `CreditCardVGG16_Fix.ipynb` | Notebook utama berisi preprocessing, training, dan evaluasi model. |
| `requirements.txt`          | Daftar dependencies yang diperlukan.                               |
| `README.md`                 | Dokumentasi project.                                               |
---
⚙️ Alur Model
| Tahap                  | Deskripsi                                                              |
| ---------------------- | ---------------------------------------------------------------------- |
| **Data Preprocessing** | Membersihkan, menyeimbangkan data, dan menyiapkan input.               |
| **Transfer Learning**  | Menggunakan arsitektur **VGG16 pretrained** sebagai feature extractor. |
| **Training Model**     | Fine-tuning layer sesuai dataset kartu kredit.                         |
| **Evaluasi**           | Menghitung akurasi, loss, dan visualisasi hasil.                       |
---
✨ Fitur Utama
🔄 Transfer Learning dengan VGG16 untuk deteksi transaksi fraud.
📊 Visualisasi training (akurasi & loss).
⚡ Implementasi cepat dengan TensorFlow/Keras.
📝 Notebook interaktif untuk eksplorasi & modifikasi.
---
🚀 Cara Menjalankan
Clone repo:
git clone https://github.com/rizkynandapr/CreditCardVGG16.git
cd CreditCardVGG16
---
Install dependencies:
pip install -r requirements.txt
Jalankan notebook:
jupyter notebook CreditCardVGG16_Fix.ipynb
---
🛠️ Teknologi yang Digunakan
Python 3.x
TensorFlow / Keras
NumPy, Pandas
Matplotlib, Seaborn
scikit-learn
---
📊 Hasil
Model menunjukkan akurasi yang baik dalam klasifikasi transaksi.
Visualisasi hasil training ditampilkan pada notebook.
