<h2>Chart Luas Bangunan<h2>

<p align="start">
    <img src="https://github.com/user-attachments/assets/a865856e-7773-4c92-b940-993969c1276f" alt="Logo" width="500">
</p>

<p>Mayoritas bangunan memiliki luas antara 100-400 m², dengan puncak pada 150-200 m², menunjukkan dominasi bangunan berukuran menengah ke bawah. Luas di atas 500 m² semakin jarang, dan sangat sedikit yang melebihi 1000 m².</p>

<h2>Chart Luas Tanah<h2>

<p align="start">
    <img src="https://github.com/user-attachments/assets/b3b2f965-e156-4b62-8b21-866e0846b96a" alt="Logo" width="500">
</p>

<p>Frekuensi tertinggi terdapat pada tanah seluas 100-200 m² dengan hampir 300 bidang, menunjukkan dominasi lahan kecil. Frekuensi menurun tajam setelah 500 m², dan sangat sedikit tanah melebihi 1000 m². Pola ini mencerminkan karakteristik kawasan pemukiman atau perkotaan dengan pembagian lahan yang lebih compact, sementara lahan besar (di atas 1500 m²) sangat jarang.</p>

<h2>Chart Kamar Tidur<h2>

<p align="start">
    <img src="https://github.com/user-attachments/assets/f80f673c-4772-4832-b9d2-25dfadbbcabd" alt="Logo" width="500">
</p>

<p>Dataset menunjukkan bahwa rata-rata rumah yang dijual memiliki 4 kamar tidur, diikuti oleh 5 kamar tidur sebagai jumlah terbanyak kedua.</p>

<h2>Chart Kamar Mandi<h2>

<p align="start">
    <img src="https://github.com/user-attachments/assets/806171a2-9d7b-412f-bccd-012a11170b5b" alt="Logo" width="500">
</p>

<p>Distribusi kamar mandi menunjukkan frekuensi tertinggi pada properti dengan 3 kamar mandi, disusul oleh 4 kamar mandi.</p>

<h2>Chart Garasi<h2>

<p align="start">
    <img src="https://github.com/user-attachments/assets/b864a963-baba-45ac-a98b-4ff86e0e3367" alt="Logo" width="500">
</p>

<p>Distribusi jumlah garasi menunjukkan mayoritas properti memiliki 1-2 garasi, dengan frekuensi tertinggi pada 2 garasi.</p>

<h2>Akurasi Model<h2>

```python
print("Akurasi : ", model.score(x_test, y_test))
```
<span>Akurasi :  0.7713134894077545</span>

<p>Metode multiple linear regression menghasilkan akurasi 77% dalam memprediksi harga rumah berdasarkan variabel seperti luas bangunan, luas tanah, jumlah kamar mandi, kamar tidur, dan garasi. Ini menunjukkan model cukup baik dalam menjelaskan 77% variasi harga rumah, meskipun masih ada ruang untuk perbaikan.</p>
