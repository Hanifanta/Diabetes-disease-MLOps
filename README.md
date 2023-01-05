# Submission 2: Prediksi Diabetes

Nama: Hanif Al Irsyad

Username dicoding: hanifanta

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Heart Failure Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) |
| Masalah | Gagal jantung (heart failure) adalah kondisi di mana jantung tidak dapat memompa darah dengan cukup efektif. Ini dapat terjadi karena berbagai sebab, seperti penyakit jantung koroner, hipertensi (tekanan darah tinggi), dan diabetes. Ketika jantung tidak dapat memompa darah dengan cukup baik, darah tidak dapat mengalir dengan lancar ke seluruh tubuh, sehingga tubuh tidak mendapatkan cukup oksigen dan nutrisi. Ini dapat menyebabkan gejala seperti kelelahan, sesak napas, dan edema (pembengkakan). Gagal jantung dapat menyebabkan komplikasi serius, seperti stroke dan serangan jantung, jika tidak dikelola dengan benar. Gagal jantung merupakan masalah kesehatan yang serius dan merupakan salah satu penyebab utama kematian di seluruh dunia. Prevalensi gagal jantung di dunia terus meningkat, terutama di negara-negara dengan tingkat kepadatan penduduk yang tinggi dan tingkat kejadian penyakit kronis yang tinggi.|
| Solusi machine learning | Dari permasalahan diatas dengan memanfaatkan teknologi, machine learning menjadi salah satu solusi untuk membantu mengurangi tingkat kematian yang cukup tinggi akibat penyakit ini. Dengan sebuah sistem prediksi penyakit Gagal jantung, diharapkan para tenaga medis maupun masyarakat dapat terbantu untuk dapat mendeteksi penyakit ini lebih awal. |
| Metode pengolahan | Dalam dataset yang digunakan terdapat dua jenis fitur, yaitu fitur yang berjenis kategorikal dan numerik. Untuk fitur kategorikal akan ditransformasi menjadi numerikal menggunakan one-hot-encoding. Untuk fitur numerik akan dinormalisasi sehingga semua value berada pada range yang sama.  |
| Arsitektur model | Model yang dibangun cukup sederhana hanya menggunakan Dense layer dan Dropout layer sebagai hidden layer pada model neural network dan memiliki 1 output layer |
| Metrik evaluasi | Metric yang digunakan pada model yaitu AUC, Precision, Recall, BinaryAccuracy, TruePositive, FalsePositive, TrueNegative, FalseNegative untuk mengevaluasi performa model sebuah klasifikasi |
| Performa model | Model yang dibuat menghasilkan performa yang cukup baik dalam memberikan sebuah prediksi dan dari pelatihan yang dilakukan menghasilkan binary_accuracy sebesar 87% dan val_binary_acuracy sebesar 85%, hasil seperti ini sudah cukup baik untuk sebuah sistem klasifikasi namun masih bisa ditingkatkan lagi  |
| Opsi deployment | Proyek machine learning ini dideploy menggunakan salah satu platfrom as a service yaitu HEROKU yang menyediakan layanan gratis untuk mendeploy sebuah proyek. |
| Web app | https://heart-prediction.up.railway.app |
| Monitoring | Monitoring pada proyek ini dapat dilakukan dengan menggunakan layanan open-source yaitu prometheus. Contohnya setiap perubahan jumlah request yang dilakukan kepada sistem ini dapat dimonitoring dengan baik dan dapat menampilkan status dari setiap request yang diterima |
