# Business-Intelligence-and-Forecasting-Implementation
Built a BI dashboard and implemented forecasting using Triple Exponential Smoothing on airport flight data using Power BI, PostgreSQL, and Pentaho.

**📘 Latar Belakang Proyek**

Bandar Udara Depati Amir Pangkalpinang merupakan salah satu bandara utama di Provinsi Kepulauan Bangka Belitung yang dikelola oleh PT Angkasa Pura II. Dalam operasionalnya, bandara ini menangani data yang kompleks terkait pergerakan pesawat, penumpang, dan kargo setiap tahunnya.

Namun, data-data ini masih tersebar dalam format yang belum terstruktur dan belum dioptimalkan untuk pengambilan keputusan strategis. Oleh karena itu, dibutuhkan penerapan Business Intelligence yang dapat membantu manajemen dalam menganalisis kinerja penerbangan dan memperkirakan tren di masa depan.

Proyek ini bertujuan untuk merancang dan mengimplementasikan sistem dashboard interaktif yang menyajikan informasi menyeluruh terkait operasional bandara, sekaligus menyertakan fitur forecasting (peramalan) berbasis data historis.

**🧩 Ringkasan Proyek**

**🔎 Permasalahan**

Bandara belum memiliki sistem dashboard terintegrasi yang mampu menyajikan informasi operasional secara real-time dan prediktif, sehingga pengambilan keputusan kurang berbasis data historis dan tren.

**🎯 Tujuan**
1. Merancang dan membangun data warehouse dari data penerbangan bandara
2. Mengimplementasikan dashboard visualisasi interaktif menggunakan Microsoft Power BI
3. Menyediakan fitur forecasting untuk memprediksi jumlah pesawat, penumpang, dan kargo
4. Memberikan informasi strategis untuk mendukung manajemen bandara

**🛠️ Solusi**
1. ETL data menggunakan Pentaho Data Integration (PDI)
2. Penyimpanan data terintegrasi di PostgreSQL
3. Visualisasi dashboard dengan Microsoft Power BI
4. Forecasting menggunakan Triple Exponential Smoothing
5. Evaluasi akurasi model dengan MAPE (Mean Absolute Percentage Error)

**🛠️ Tools & Teknologi yang Digunakan**
1. PostgreSQL	= Penyimpanan data warehouse
2. Pentaho Data Integration (PDI)	= Proses ETL (Extract, Transform, Load)
3. Microsoft Power BI	= Visualisasi dashboard & forecasting
4. Excel (.xls)	= Sumber data awal & validasi
5. DAX (Power BI)	= Perhitungan metrik, filtering, dan pembuatan insight
6. Triple Exponential Smoothing	= Peramalan tren pesawat, penumpang, dan kargo

**📂 Struktur Dataset**

Data yang digunakan mencakup periode 2019–2023, dan dibagi ke dalam beberapa kategori utama:
1. Pesawat = Total pesawat datang, berangkat, dan keseluruhan
2. Penumpang = Jumlah penumpang datang, berangkat, dan transit
3. Kargo = Volume kargo datang, berangkat, dan total
4. Tanggal = Skema waktu (bulan, tahun) sebagai dimensi peramalan
5. Fakta Penerbangan = Tabel utama yang menghubungkan seluruh dimensi

**📈 Fitur Dashboard**
1. Dashboard Pesawat = Menampilkan tren pergerakan pesawat berdasarkan bulan dan tahun.
2. Dashboard Penumpang = Memberikan gambaran volume penumpang berdasarkan jenis perjalanan.
3. Dashboard Kargo = Menyediakan data kargo berdasarkan arah (datang vs. berangkat).
4. Dashboard Forecasting = Menyajikan prediksi 12 bulan ke depan untuk pesawat, penumpang, dan kargo.

**🔍 Forecasting & Evaluasi**

Metode: Triple Exponential Smoothing

Parameter:
1. Forecast Length: 12 bulan
2. Seasonality: 12
3. Confidence Interval: 95%
4. Hasil Evaluasi (MAPE):
    - Pesawat: 7,74% → Sangat Akurat
    - Penumpang: 19,08% → Akurat
    - Kargo: 10,95% → Akurat

**✅ Hasil**
1. Tercipta 4 dashboard utama: Pesawat, Penumpang, Kargo, dan Forecasting
2. Sistem mampu menampilkan tren pergerakan tahunan dan bulanan
3. Forecast 12 bulan ke depan menunjukkan akurasi tinggi (MAPE < 10% untuk pesawat)
4. Aplikasi telah diuji oleh manajemen dan dapat digunakan sebagai dasar pengambilan keputusan operasional
5. Berikut adalah link untuk melihat dashboard secara full screen : https://app.powerbi.com/view?r=eyJrIjoiNDI3YzQ3MDEtNDhmZi00NGZiLTg3OGItYjVkODdkN2RmMzU4IiwidCI6IjM0NjI3ODc0LWVkM2EtNDk3Yy04ZmI5LTE2Y2U3ZTk3NjRmMSIsImMiOjEwfQ%3D%3D

**📫 Contact**

Created by Atika Rahmah

Universitas Andalas 

For inquiries: atikachanita@outlook.co.id

LinkedIn: linkedin.com/in/atika-rahmah/

