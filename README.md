# TREND-ANALYSIS-OF-ONLINE-COURSE-CODEPOLITAN-
---

# 📊 TREND-ANALYSIS-OF-ONLINE-COURSE-CODEPOLITAN-

## 📌 Deskripsi Project

Project ini bertujuan untuk menganalisis tren kursus online pada platform **Codepolitan** menggunakan data yang tersedia secara publik.

Analisis dilakukan untuk memahami:

* Minat pengguna terhadap kursus tertentu
* Distribusi harga dan rating
* Hubungan antara harga, rating, dan jumlah peserta
* Aktivitas dan tren pengguna di platform

Data dikumpulkan melalui proses scraping menggunakan API/JSON dengan status code 200, tanpa memerlukan login.

🔗 **Google Colab Project:**
[https://colab.research.google.com/drive/1tw4xtsXbJpWMJCw2edEAtCAiE_FO8D_D?usp=sharing](https://colab.research.google.com/drive/1tw4xtsXbJpWMJCw2edEAtCAiE_FO8D_D?usp=sharing)

🌐 **Sumber Data:**
[https://www.codepolitan.com/](https://www.codepolitan.com/)

---

# 🎯 Business Understanding

Project ini dirancang untuk menjawab pertanyaan bisnis berikut:

1. Kursus online apa yang paling banyak diminati?
2. Berapa jumlah total kursus yang tersedia di platform?
3. Berapa jumlah total kursus gratis (Rp.0,-) yang tersedia?
4. Kursus apa saja yang memiliki lebih dari 500 ulasan?
5. Berapa level kursus yang tersedia?
6. Bagaimana distribusi level kursus?
7. Bagaimana distribusi rating kursus dengan nilai > 4.5?
8. Bagaimana hubungan antara harga dan rating?
9. Bagaimana hubungan antara harga dan jumlah peserta?
10. Bagaimana hubungan antara rating dan jumlah peserta?

---

# 🚧 Batasan Analisis

Untuk menjaga validitas dan konsistensi data, analisis memiliki batasan sebagai berikut:

* Hanya menggunakan data yang tersedia secara publik
* Data harus dapat diakses tanpa login
* Data diperoleh melalui API/JSON dengan status code 200
* Tidak memuat harga yang mengharuskan login
* Hanya menganalisis kursus terbaru yang ditampilkan
* Jika terdapat informasi tidak lengkap, maka akan diisi dengan nilai 0
* Data harus menunjukkan tren atau aktivitas pengguna

---

# 🔄 Workflow Project

Project ini mengikuti tahapan analisis data sebagai berikut:

1. **Business Understanding**
2. **Scraping Data**
3. **Data Understanding**
4. **Data Preparation**
5. **Exploratory Data Analysis (EDA)**
6. **Answer The Research Question**
7. **Conclusion & Recommendation**

---

# 🛠 Tools & Technology

* Python
* Google Colab
* Requests (API Access)
* JSON Processing
* Pandas
* Matplotlib / Seaborn
* Data Visualization

---

# 📊 Insight yang Diharapkan

Melalui project ini, diharapkan dapat diperoleh insight mengenai:

* Tren kursus yang sedang populer
* Perbandingan kursus gratis vs berbayar
* Pengaruh harga terhadap rating dan jumlah peserta
* Faktor yang mempengaruhi tingginya jumlah peserta
* Segmentasi kursus berdasarkan level

Insight ini dapat membantu:

* Platform dalam menyusun strategi konten
* Instructor dalam menentukan harga
* User dalam memilih kursus terbaik

---

# 📌 Kesimpulan

Project ini menunjukkan bagaimana data publik dapat dimanfaatkan untuk memahami tren pasar edutech.
Dengan pendekatan berbasis data, kita dapat mengidentifikasi pola minat pengguna dan hubungan antar variabel penting seperti harga, rating, dan jumlah peserta.

---

