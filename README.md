# Dicoding ML Ops Submission 2: Bank Customer Churn Prediction
Nama: Niko Febrianur

Username dicoding: nikofebrianur

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Bank Customer Churn](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn) |
| Masalah | Bisnis perbankan dihadapkan dengan tantangan untuk mengelola tingkat churn pelanggan, di mana pelanggan meninggalkan bank. Oleh karena itu, masalah yang diangkat dalam proyek ini adalah untuk membangun model machine learning yang dapat memprediksi kemungkinan churn pelanggan berdasarkan atribut yang diberikan dalam dataset. Bank memiliki kepentingan bisnis untuk memahami faktor-faktor apa yang mempengaruhi keputusan pelanggan untuk meninggalkan layanan mereka. Dengan mengetahui hal ini, bank dapat mengembangkan program loyalitas dan kampanye retensi yang efektif untuk mempertahankan sebanyak mungkin pelanggan. Mengurangi tingkat churn juga dapat menghasilkan penghematan biaya, karena mendaftarkan pelanggan baru biasanya lebih mahal daripada mempertahankan pelanggan yang sudah ada. |
| Solusi machine learning | Untuk mengatasi masalah tingkat churn pelanggan dalam perbankan, solusi machine learning yang diusulkan adalah mengembangkan model prediktif. Model ini akan membantu bank memprediksi apakah seorang pelanggan cenderung meninggalkan layanan mereka berdasarkan informasi seperti skor kredit, lokasi, usia, saldo, dan faktor lainnya. |
| Metode pengolahan | Dalam penanganan data untuk kasus ini, terdapat sembilan fitur di mana delapan di antaranya akan digunakan sebagai fitur klasifikasi, dan satu fitur sebagai kelas target. Dari keseluruhan fitur, terdapat dua fitur kategorikal dan enam fitur numerik. Proses pengolahan data dimulai dengan pembagian data menjadi dua bagian, yaitu 80% untuk pelatihan (train) dan 20% untuk evaluasi (eval). Selanjutnya, dilakukan serangkaian transformasi data, termasuk mengganti nama fitur yang telah diubah, serta penerapan one-hot encoding untuk fitur kelas. Proses ini bertujuan untuk memastikan bahwa data siap digunakan oleh model machine learning, dengan variabel yang diolah secara sesuai dan memenuhi kebutuhan algoritma yang akan digunakan. Dengan langkah-langkah ini, data telah disiapkan untuk melatih dan mengevaluasi model klasifikasi guna memprediksi keaktifan anggota bank. |
| Arsitektur model | Deskripsi arsitektur model yang diguanakan |
| Metrik evaluasi | Deksripsi metrik yang digunakan untuk mengevaluasi performa model |
| Performa model | Deksripsi performa model yang dibuat |
| Opsi deployment | Sistem machine learning ini akan dideploy menggunakan platform Heroku |
| Web app | Tautan web app yang digunakan untuk mengakses model serving. Contoh: [nama-model](https://model-resiko-kredit.herokuapp.com/v1/models/model-resiko-kredit/metadata)|
| Monitoring | Deksripsi terkait hasil monitoring dari model serving |
