# Submission 2: Prediksi Diabetes

Nama: Hanif Al Irsyad

Username dicoding: hanifanta

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Diabetes Disease Dataset](https://www.kaggle.com/datasets/jillanisofttech/diabetes-disease-updated-dataset) |
| Masalah | Diabetes merupakan penyakit yang berat dan bisa menyebabkan komplikasi serius jika tidak dikelola dengan benar. Komplikasi diabetes meliputi masalah pada mata, ginjal, saraf, dan jantung. Diabetes juga merupakan salah satu faktor risiko terbesar untuk penyakit jantung koroner dan stroke.|
| Solusi machine learning | Dari permasalahan diatas dengan memanfaatkan teknologi, machine learning menjadi salah satu solusi untuk membantu mengurangi tingkat kematian yang cukup tinggi akibat penyakit ini. Dengan sebuah sistem prediksi penyakit diabetes, diharapkan para tenaga medis maupun masyarakat dapat terbantu untuk dapat mendeteksi penyakit ini lebih awal. |
| Metode pengolahan | Data yang digunakan pada proyek ini terdapat data numerik. Metode yang digunakan untuk mengelolah data tersebut yaitu menormalisasikan data numerik kedalam range data yang sama.  |
| Arsitektur model | Model yang dibangun cukup sederhana hanya menggunakan Dense layer dan Dropout layer sebagai hidden layer pada model neural network dan memiliki 1 output layer |
| Metrik evaluasi | Metric yang digunakan pada model yaitu AUC, Precision, Recall, BinaryAccuracy, TruePositive, FalsePositive, TrueNegative, FalseNegative untuk mengevaluasi performa model sebuah klasifikasi |
| Performa model | Model yang dibuat menghasilkan performa yang cukup baik dalam memberikan sebuah prediksi dan dari pelatihan yang dilakukan menghasilkan binary_accuracy sebesar 87% dan val_binary_acuracy sebesar 85%, hasil seperti ini sudah cukup baik untuk sebuah sistem klasifikasi namun masih bisa ditingkatkan lagi  |
| Opsi deployment | Proyek machine learning ini dideploy menggunakan salah satu platfrom as a service yaitu HEROKU yang menyediakan layanan gratis untuk mendeploy sebuah proyek. |
| Web app | <> |
| Monitoring | Monitoring pada proyek ini dapat dilakukan dengan menggunakan layanan open-source yaitu prometheus. Contohnya setiap perubahan jumlah request yang dilakukan kepada sistem ini dapat dimonitoring dengan baik dan dapat menampilkan status dari setiap request yang diterima |
