# Projectkan
Analisis Data Penjualan Toko Elektronik
Proyek ini menyediakan analisis komprehensif terhadap data penjualan untuk sebuah toko elektronik fiktif selama periode enam bulan (Januari - Juni 2024). Seluruh proses, mulai dari pembuatan data sampel hingga visualisasi dan penarikan kesimpulan, terkandung dalam satu file Jupyter Notebook (Analisa_Data_Penjualan_Produk.ipynb).

📝 Deskripsi Proyek
Notebook ini dirancang untuk mensimulasikan dan menganalisis data transaksi penjualan produk elektronik. Tujuannya adalah untuk mengidentifikasi tren penjualan, produk terlaris, dan kategori produk yang paling berkontribusi terhadap pendapatan. Hasil analisis disajikan dalam bentuk visualisasi data yang mudah dipahami dan diakhiri dengan wawasan kunci serta rekomendasi bisnis yang dapat ditindaklanjuti.

🚀 Fitur & Tahapan Analisis
Proses analisis dalam notebook ini mencakup beberapa tahapan utama:

Simulasi Data: Membuat dataset sampel yang realistis berisi 1000 transaksi penjualan. Data ini mencakup informasi seperti tanggal, produk, kategori, harga, dan kuantitas.

Eksplorasi Data (EDA): Melakukan analisis data eksploratif untuk memahami statistik dasar dari dataset, seperti total pendapatan, rata-rata nilai transaksi, dan jumlah produk terjual.

Analisis Berdasarkan Kategori: Mengelompokkan data berdasarkan kategori produk (Electronics vs. Accessories) untuk membandingkan performa penjualan dan kontribusi pendapatan.

Analisis Berdasarkan Produk: Mengidentifikasi produk-produk terlaris berdasarkan total pendapatan yang dihasilkan.

Analisis Tren Bulanan: Menganalisis tren penjualan dari bulan ke bulan untuk melihat adanya fluktuasi atau pola musiman.

Visualisasi Data: Membuat dashboard visual 2x2 yang merangkum temuan-temuan utama dari analisis.

Wawasan & Rekomendasi: Menarik kesimpulan dari data dan memberikan rekomendasi bisnis strategis berdasarkan wawasan tersebut.

📈 Visualisasi Dashboard
Dashboard analisis penjualan terdiri dari empat plot utama:

Pie Chart (Revenue by Category): Menunjukkan persentase kontribusi pendapatan dari setiap kategori produk.

Bar Chart (Revenue by Product): Menampilkan perbandingan pendapatan yang dihasilkan oleh setiap produk, diurutkan dari yang terlaris.

Line Chart (Monthly Sales Trend): Menggambarkan tren total pendapatan setiap bulannya untuk mengidentifikasi performa penjualan dari waktu ke waktu.

Heatmap (Sales: Product vs Month): Memetakan total penjualan untuk setiap produk pada setiap bulan, memudahkan identifikasi produk yang populer di bulan-bulan tertentu.

💡 Wawasan Kunci (Key Insights)
Berdasarkan analisis data, ditemukan beberapa wawasan penting:

Total Pendapatan: Mencapai sekitar Rp 12,18 Miliar selama periode 6 bulan.

Produk Terlaris: Laptop adalah produk yang menghasilkan pendapatan tertinggi.

Kategori Dominan: Kategori Electronics memberikan kontribusi pendapatan yang jauh lebih besar dibandingkan kategori Accessories.

Bulan Terbaik: Penjualan tertinggi tercatat pada bulan Januari 2024.

📋 Rekomendasi Bisnis
Dari wawasan yang diperoleh, berikut adalah beberapa rekomendasi yang diusulkan:

Fokus Promosi: Alokasikan anggaran promosi lebih besar pada kategori Electronics yang menjadi pendorong utama pendapatan.

Manajemen Stok: Tingkatkan stok untuk produk-produk terlaris seperti Laptop, terutama menjelang akhir bulan di mana tren penjualan cenderung meningkat.

Strategi Bundling: Buat penawaran paket (bundle) antara produk Accessories (seperti mouse atau headphone) dengan produk Electronics (seperti laptop) untuk meningkatkan penjualan produk aksesoris.

Analisis Lanjutan: Lakukan analisis lebih mendalam untuk memahami penyebab fluktuasi penjualan bulanan, misalnya dengan melihat dampak hari libur atau event promosi tertentu.

⚙️ Cara Menjalankan Proyek
Untuk menjalankan analisis ini di komputer Anda, ikuti langkah-langkah berikut:

Prasyarat: Pastikan Anda telah menginstal Python dan pustaka-pustaka yang diperlukan.

Bash

pip install pandas numpy matplotlib seaborn
Unduh File: Unduh file Analisa_Data_Penjualan_Produk.ipynb dari repositori ini.

Buka Notebook: Buka file tersebut menggunakan Jupyter Notebook, JupyterLab, atau Google Colab.

Jalankan Semua Sel: Untuk mereplikasi hasil analisis, jalankan semua sel di dalam notebook secara berurutan dari atas ke bawah.

📚 Pustaka yang Digunakan
Pandas: Untuk manipulasi dan analisis data.

NumPy: Untuk operasi numerik dan pembuatan data sampel.

Matplotlib: Untuk membuat visualisasi data statis.

Seaborn: Untuk membuat visualisasi data yang lebih menarik dan informatif.
