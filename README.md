# UAS Deep Learning
# Nama Kelompok 
| Nama                                | NPM       |
| ----------------------              | :--------:|
| Ilham Dio Putra                     | G1A021024 | 
| Arief Satrio Budi Prasojo           | G1A021076 |
| Irfan Luthfi                        | G1A021090 | 

# Deskripsi Proyek

Proyek kelompok ini bertujuan untuk memenuhi **tugas akhir** dari mata kuliah Deep Learning, dengan fokus pada klasifikasi gambar gedung belajar yang ada di Universitas Bengkulu. Proyek ini menggunakan***pre-trained***  model yaitu ***EfficientNetV2B3*** untuk mengklasifikasikan gambar gedung belajar ke dalam 7 kelas yang berbeda. Setiap kelas mewakili tipe atau kategori gedung belajar yang ada di kampus Universitas Bengkulu. Proyek ini bertujuan untuk memberikan solusi otomatis dalam pengenalan dan klasifikasi gambar gedung, yang dapat berguna untuk berbagai aplikasi, seperti manajemen aset dan pemetaan kampus.
# Dataset:
Dataset yang kami gunakan berupa sampel dari 7 gedung belajar yang ada di universitas bengkulu, harusnya ada **8** tapi dibuat jadi **7** karena **gedung belajar 3 & 4** terletak di lokasi yang sama maka dijadikan satu tempat. Dengan tiap kelas  masing-masing kurang lebih 30 foto dengan total 213 data.

# Hasil dan Pembahasan 
## Grafik Evaluasi Model 
### Grafik Training dan Validation Accuracy
![Overview Banner!](https://github.com/IlhamDioPutra/UAS_DEEP-LEARNING/blob/main/Result/Accuracy.png)<br/>
### Grafik Training dan Validation Loss
![Overview Banner!](https://github.com/IlhamDioPutra/UAS_DEEP-LEARNING/blob/main/Result/Loss.png)<br/>
Berdasarkan hasil evaluasi model yang ditunjukkan oleh dua grafik utama, yaitu **Training and Validation Accuracy** serta **Training and Validation Loss**, dapat disimpulkan bahwa model ini menunjukkan **kinerja yang sangat baik** baik pada tahap pelatihan (training) maupun validasi (validation).
Akurasi pada **training** dan **validation** berhasil mencapai nilai prediksi lebih dari **85%** (**callback**) hanya dalam **2 epoch** pertama. Ini menandakan bahwa model sudah mulai mengidentifikasi pola dengan baik sejak awal pelatihan.
Meskipun demikian, ada kemungkinan bahwa **callback** yang lebih tinggi dapat menghasilkan **kinerja yang lebih baik**, karena berdasarkan grafik yang ada, **akurasi terus meningkat** dengan setiap epoch tambahan. Dengan optimasi lebih lanjut, model ini berpotensi untuk mencapai **akurasi yang lebih tinggi** dan **penurunan loss yang lebih signifikan**.<br />
## Matriks Evaluasi 
### Classification Report
![Overview Banner!](https://github.com/IlhamDioPutra/UAS_DEEP-LEARNING/blob/main/Result/Classification%20Report.png)<br/>
### Confusion Matrix
![Overview Banner!](https://github.com/IlhamDioPutra/UAS_DEEP-LEARNING/blob/main/Result/Confusion%20Matrix.png)<br/>
Berdasarkan laporan **evaluasi model klasifikasi** dan **Confusion Matrix**, performa model menunjukkan **akurasi sempurna** yaitu **100%** pada tahap **Validation**. Hal ini menunjukkan bahwa model berhasil melakukan **prediksi yang sangat akurat** pada setiap sampel data yang diberikan, dengan tidak ada kesalahan prediksi sama sekali.
Namun, perlu diingat bahwa **hasil sempurna ini mungkin terjadi karena** jumlah dataset yang digunakan relatif **sedikit** dan **serupa**, yang dapat membuat model lebih mudah dalam mengenali pola dan menghasilkan prediksi yang benar. Dengan dataset yang terbatas dan kurang beragam, model mungkin memiliki kecenderungan untuk memberikan hasil yang lebih baik, tetapi ini juga berarti model tersebut belum diuji pada variasi data yang lebih luas.<br><br>
Ke depannya, kami berharap dapat **menambahkan lebih banyak data** yang beragam dan representatif untuk memperkaya model. Dengan dataset yang lebih besar dan beragam, diharapkan model ini dapat diuji pada situasi yang lebih nyata dan memberikan hasil evaluasi yang **lebih konsisten dan terpercaya**. Dengan cara ini, model diharapkan mampu menangani berbagai jenis data dengan akurasi yang tetap tinggi, dan lebih siap untuk diterapkan dalam kondisi dunia nyata yang lebih kompleks.
## Testing 
![Overview Banner!](https://github.com/IlhamDioPutra/UAS_DEEP-LEARNING/blob/main/Result/Confusion%20Matrix.png)<br/>
Secara keseluruhan, hasil prediksi model sudah menunjukkan kinerja yang baik, dengan akurasi keseluruhan mencapai 87%. Meskipun demikian, masih terdapat beberapa kesalahan 
dalam prediksi,yang terlihat dari variasi performa antar kelas
# Analisa Model
Model yang kami gunakan **MobileNetV2** termasuk dalam kategori **deep learning** karena menggunakan arsitektur jaringan saraf dalam (deep neural network) yang terdiri dari 
banyak lapisan untuk memproses data. Berbeda dengan shallow learning, yang biasanya hanya melibatkan satu atau beberapa lapisan sederhana dalam model, MobileNetV2 dirancang 
untuk menangani data yang lebih kompleks dengan cara yang lebih efisien.
# Referensi :mag_right:
1. [Link Youtube :point_left:](https://www.youtube.com/watch?v=Ax6P93r32KU)
