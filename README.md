<h1>Deskripsi Singkat</h1>
Analisis sentimen digunakan untuk pemrosesan bahasa alami (Natural Language Processing/ NLP), sehingga dapat melakukan analisis pendapat,perasaan, reaksi orang mengenai suatu hal, misalnya produk, layanan.
Metode yang digunakan pada analisis sentimen terbagi menjadi 3 (tiga), yaitu: 
i). tahap 1, penentuan kelas/ label sentimen pada data skala Likert dengan clustering
menggunakan K-Means++, 
ii). tahap 2, penentuan kelas/ label sentimen
pada data komentar dengan menggunakan Latent Dirichlet Allocation (LDA)
untuk mendapatkan topic modeling, 
iii). tahap 3, penentuan kelas/ label yang menggabungkan data kelas/ label yang didapatkan pada tahap 1 dan tahap 2 dengan clustering menggunakan K-Means++. 

Data yang digunakan berjumlah 1424 record yang terdiri dari data skala Likert dan komentar. 

* Tahap 1 dilakukan clustering menggunakan data skala Likert didapatkan sentimen negatif sebanyak 637 (44,7%) dan sentimen positif sebanyak 787 (55,3%). 
* Tahap 2 dilakukan topic modeling dengan LDA untuk data komentar didapatkan hasil 1070 (75,2%) sentimen positif dan 354 (24,8%) sentimen negatif. 
* Tahap 3 dilakukan clustering dari data hasil tahap 1 dan tahap 2 didapatkan hasil sebanyak 480 (33,7%) sentimen netral, 731 (51,4%) sentimen positif dan 213(14,9%) sentimen negatif.
---
<h1>Tools</h1>

* Python Programming Language
* Jupyter Notebook
* Streamlit
