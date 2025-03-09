📊 E-Commerce Data Analysis

📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis data dari platform e-commerce untuk memahami pola pelanggan dan faktor yang mempengaruhi penjualan. Ada dua pertanyaan utama yang ingin dijawab:

	1.	Wilayah dengan jumlah pelanggan terbanyak
	2.	Pengaruh tingginya review terhadap penjualan

📂 Struktur Direktori

submission
├───dashboard
| ├───main_data.csv
| └───dashboard.py
├───data
| ├───data_1.csv
| └───data_2.csv
├───notebook.ipynb
├───README.md
└───requirements.txt
└───url.txt

📊 Dataset

Dataset yang digunakan terdiri dari beberapa file CSV:

	•	customers.csv → Informasi pelanggan (ID, lokasi, dsb.)
	•	orders.csv → Data pesanan pelanggan
	•	ratings.csv → Data ulasan dan rating produk

🔍 Metodologi

	1.	Analisis Wilayah dengan Pelanggan Terbanyak
	•	Mengelompokkan pelanggan berdasarkan lokasi (provinsi/kota).
	•	Menghitung jumlah pelanggan di setiap wilayah.
	•	Menampilkan hasil dalam bentuk visualisasi (bar chart).
	2.	Analisis Pengaruh Rating terhadap Penjualan
	•	Menggabungkan data rating dengan jumlah produk terjual.
	•	Membuat scatter plot antara skor ulasan dan total penjualan.
	•	Menggunakan korelasi untuk melihat hubungan antara kedua variabel.

📌 Hasil & Insight

	•	Wilayah dengan pelanggan terbanyak adalah Sao Paulo.
	•	Tidak ada pengaruh tingginya skor review dengan tingkat penjualan

⚙️ Teknologi yang Digunakan

	•	Python (pandas, numpy, scikit-learn, matplotlib, seaborn)
	•	Jupyter Notebook
	•	Google Colab

🚀 Cara Menjalankan Proyek

pip install -r requirements.txt


	Jalankan notebook
	•	Buka Copy_of_Proyek_Analisis_Data.ipynb di Jupyter Notebook atau Google Colab.
	•	Jalankan setiap sel untuk melihat hasil analisis.

📌 Catatan Tambahan

	•	Dataset yang digunakan bersumber dari dicoding.
