# 📝 UTS_AksaraJawa_Clustering

## Analisis Clustering Citra Aksara Jawa Menggunakan Python

Proyek ini merupakan implementasi analisis clustering pada citra Aksara Jawa menggunakan teknik Machine Learning berbasis unsupervised learning.  
Notebook ini melakukan preprocessing citra, ekstraksi fitur menggunakan PCA, clustering menggunakan K-Means, serta evaluasi hasil cluster dengan silhouette score dan visualisasi cluster.

---

# 📖 Deskripsi Proyek

**UTS_AksaraJawa_Clustering** adalah proyek pembelajaran Python yang bertujuan untuk menganalisis dan mengelompokkan citra aksara Jawa berdasarkan kemiripan visual.

Proyek menggunakan:
- preprocessing citra grayscale,
- flattening matriks gambar,
- reduksi dimensi menggunakan PCA,
- clustering menggunakan K-Means,
- evaluasi cluster,
- visualisasi distribusi cluster.

Dataset citra berasal dari beberapa kontributor seperti:
- ANDREW
- IUS
- PITA

---

# 🎯 Fitur Utama

- 📂 Load dataset citra aksara Jawa (.png)
- 🖼️ Visualisasi sampel citra
- 🔍 Transformasi citra menjadi fitur numerik
- 📉 Reduksi dimensi menggunakan PCA
- 🤖 Clustering menggunakan K-Means
- 📊 Evaluasi cluster dengan Silhouette Score
- 📈 Visualisasi Elbow Method
- 🧠 Analisis visual hasil cluster
- 🏷️ Dugaan label aksara berdasarkan cluster

---

# 🧠 Teknologi

- Python
- NumPy
- Matplotlib
- Pillow (PIL)
- Scikit-learn
- PCA
- K-Means Clustering

---

# 📂 Struktur File

```bash
UTS_AksaraJawa_Clustering/
├── UTS_AksaraJawa_Clustering.ipynb   # Notebook utama
├── DATA UTS2/                        # Dataset citra aksara Jawa
├── README.md                         # Dokumentasi proyek
