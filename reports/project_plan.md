# Project Plan: Hero Draft Prediction - MPL ID S14

## Tujuan Proyek
Proyek ini bertujuan untuk membangun model prediktif yang dapat memprediksi hero selanjutnya pada fase draft Mobile Legends: Bang Bang berdasarkan data turnamen MPL Indonesia Season 14. Model ini diharapkan membantu pelatih dan analis dalam menyusun strategi draft pick secara objektif berdasarkan data historis, serta membuka peluang untuk sistem rekomendasi strategi berbasis AI.

## Target Prediksi
Prediksi satu hero selanjutnya dalam urutan fase draft. Fase draft terdiri dari 20 langkah yang terbagi antara dua tim (Blue dan Red). Tabel berikut menggambarkan urutan ban dan pick pada masing-masing tim.
|Step     |1  |2  |3  |4  |5  |6  |7   |8   |9   |10  |11  |12  |13 |14 |15 |16 |17  |18  |19  |20  |
|---------|---|---|---|---|---|---|----|----|----|----|----|----|---|---|---|---|----|----|----|----|
|Blue Team|Ban|   |Ban|   |Ban|   |Pick|    |    |Pick|Pick|    |   |Ban|   |Ban|    |Pick|Pick|    |
|Red Team |   |Ban|   |Ban|   |Ban|    |Pick|Pick|    |    |Pick|Ban|   |Ban|   |Pick|    |    |Pick|

## Stakeholder
- Coaching Staff (coach, analyst, dll)
- Fans Tim
- Penonton MPL ID

## Input dan Output Model
### Input:
Model akan menerima sejumlah fitur sebagai input, seperti:
- Tim yang berada di sisi Blue dan Red
- Versi patch pertandingan
- Statistik historis hero (ban rate, pick rate, win rate)
### Output:
- Prediksi satu hero yang paling mungkin dipilih pada langkah draft selanjutnya (klasifikasi 1 dari 120+ hero)

## Evaluasi Model
Model akan dievaluasi menggunakan:
- **Accuracy**: Seberapa sering model memprediksi hero dengan benar
- **Top-5 Accuracy**: Seberapa sering hero yang diprediksi berada dalam **5 hero teratas**

## Ruang Lingkup dan Batasan
- Data hanya mencakup pertandingan MPL Indonesia Season 14
- Tidak mempertimbangkan faktor pemain individual