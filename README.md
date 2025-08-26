Credit Card Fraud Detection with VGG16
📌 Deskripsi Proyek

Proyek ini adalah implementasi deep learning menggunakan arsitektur VGG16 untuk mendeteksi transaksi kartu kredit yang berpotensi sebagai fraud (penipuan). Model dibangun dengan TensorFlow/Keras dan dataset transaksi kartu kredit, lalu dilakukan pelatihan serta evaluasi untuk mengukur performa deteksi.

Dengan adanya sistem ini, diharapkan dapat membantu industri finansial dalam mendeteksi aktivitas mencurigakan secara otomatis serta meminimalisir kerugian akibat transaksi ilegal.

⚙️ Fitur

Preprocessing dataset transaksi kartu kredit.

Implementasi transfer learning dengan VGG16.

Evaluasi performa model (akurasi, loss, dll).

Visualisasi hasil training.

📂 Struktur Project
📦 CreditCardVGG16
 ┣ 📜 CreditCardVGG16_Fix.ipynb   # Notebook utama (Google Colab)
 ┣ 📜 README.md                   # Dokumentasi project
 ┗ 📂 dataset/                    # Dataset transaksi kartu kredit (jika digunakan lokal)

🚀 Cara Menjalankan Project

Clone repository:

git clone https://github.com/username/CreditCardVGG16.git
cd CreditCardVGG16


Buka file .ipynb di Google Colab atau Jupyter Notebook:

Jika di Google Colab:

Upload file CreditCardVGG16_Fix.ipynb

Pastikan dataset tersedia atau sesuaikan path dataset.

Jika di Jupyter:

jupyter notebook CreditCardVGG16_Fix.ipynb


Jalankan seluruh sel notebook untuk melatih model.

📊 Hasil & Evaluasi

Model dilatih menggunakan VGG16 pre-trained.

Hasil akurasi dan loss divisualisasikan di akhir notebook.

Performa dapat disesuaikan berdasarkan jumlah epoch, learning rate, dan preprocessing dataset.

🛠️ Teknologi yang Digunakan

Python 3.x

TensorFlow / Keras

NumPy, Pandas

Matplotlib, Seaborn

🤝 Kontribusi

Jika ingin berkontribusi:

Fork repository.

Buat branch baru (feature-xyz).

Commit perubahan.

Ajukan pull request.
