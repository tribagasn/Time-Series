# 📈 Time Series Revenue Forecasting

📌 Project Overview

Project ini bertujuan untuk membangun model **Time Series Forecasting** guna memprediksi Total Revenue perusahaan selama enam bulan ke depan berdasarkan data penjualan historis. Proses analisis mencakup data preprocessing, exploratory data analysis (EDA), feature engineering, evaluasi beberapa model forecasting, hingga visualisasi hasil menggunakan Power BI. Beberapa model yang dibandingkan meliputi Naive, Seasonal Naive, Prophet, ARIMA, dan SARIMA untuk menentukan model dengan tingkat akurasi terbaik sebagai pendukung pengambilan keputusan bisnis. :contentReference[oaicite:2]{index=2}

---

🎯  Problem Statement

Perusahaan memerlukan prediksi pendapatan yang akurat sebagai dasar dalam menyusun target penjualan, perencanaan anggaran, serta pengalokasian sumber daya. Namun, fluktuasi revenue historis menyebabkan setiap metode forecasting memiliki tingkat akurasi yang berbeda. Oleh karena itu, diperlukan evaluasi beberapa model forecasting untuk menentukan model yang paling mampu memprediksi revenue secara akurat sehingga dapat mendukung proses perencanaan bisnis di masa mendatang. :contentReference[oaicite:3]{index=3}

---

❓ Business Questions

1. Bagaimana kontribusi Sales Channel dan Item Type terhadap Total Revenue?
2. Model forecasting mana yang memberikan performa terbaik berdasarkan metrik MAE, RMSE, dan MAPE?
3. Berapa proyeksi Total Revenue perusahaan untuk enam bulan ke depan menggunakan model terbaik? :contentReference[oaicite:4]{index=4}

---

⚙️ Method

Project ini dikerjakan melalui beberapa tahapan analisis sebagai berikut:

- **Data Understanding**
  - Memahami struktur dataset yang terdiri dari 100.000 baris dan 14 kolom.
  - Mengidentifikasi tipe data, missing value, duplicate, serta inkonsistensi data. :contentReference[oaicite:5]{index=5} :contentReference[oaicite:6]{index=6}

- **Data Preparation**
  - Mengubah tipe data pada kolom tanggal.
  - Membersihkan inkonsistensi data seperti spasi berlebih.
  - Melakukan feature engineering dengan membuat atribut Year, Month, Quarter, dan Year-Month untuk analisis time series. :contentReference[oaicite:7]{index=7}

- **Exploratory Data Analysis (EDA)**
  - Menganalisis distribusi data, korelasi antar variabel, hubungan antar fitur, serta karakteristik pola time series untuk memahami perilaku revenue. :contentReference[oaicite:8]{index=8}

- **Forecasting**
  - Membangun dan membandingkan model Naive, Seasonal Naive, Prophet, Prophet Seasonal, ARIMA, dan SARIMA menggunakan metrik evaluasi MAE, RMSE, dan MAPE untuk menentukan model terbaik. :contentReference[oaicite:9]{index=9}

- **Dashboard Visualization**
  - Menyajikan hasil analisis dan forecasting ke dalam dashboard Power BI untuk memudahkan monitoring performa model dan proyeksi revenue. :contentReference[oaicite:10]{index=10}

---

💡 Business Recommendations

- Menggunakan **SARIMA** sebagai model utama karena memberikan tingkat akurasi terbaik dibandingkan model lainnya.
- Memanfaatkan hasil forecasting sebagai dasar penyusunan target penjualan, perencanaan anggaran, dan pengambilan keputusan strategis.
- Memprioritaskan kategori produk dengan kontribusi revenue tinggi seperti **Household** dan **Office Supplies**, serta mengevaluasi strategi pada kategori dengan revenue yang lebih rendah agar pertumbuhan penjualan dapat ditingkatkan.
- Melakukan evaluasi dan pembaruan model forecasting secara berkala menggunakan data terbaru agar akurasi prediksi tetap terjaga. :contentReference[oaicite:11]{index=11} :contentReference[oaicite:12]{index=12}

---

✅ Conclusion

Hasil analisis menunjukkan bahwa data revenue memiliki pola musiman yang cukup signifikan meskipun tren jangka panjangnya relatif lemah. Dari seluruh model yang diuji, **SARIMA** memberikan performa terbaik dengan tingkat kesalahan prediksi paling rendah berdasarkan metrik MAE, RMSE, dan MAPE, sehingga mampu menghasilkan proyeksi revenue yang lebih akurat dibandingkan model lainnya. Dengan tingkat akurasi tersebut, model SARIMA direkomendasikan sebagai solusi forecasting yang dapat membantu perusahaan dalam mendukung proses perencanaan bisnis dan pengambilan keputusan yang lebih efektif. :contentReference[oaicite:13]{index=13}
