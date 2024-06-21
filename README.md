# massive-kelompok-5
Project massive kelompok.5
________________________
Teams
Aissa Wahyuning Rahayu - Universitas Gadjah Mada
Cindy Laura Tampubolon - Politeknik Negeri Batam
M. Arsyi Muntaha - Universitas Sains Al-Quran Wonosobo
Muhammad Gunawan - Universitas Negeri Semarang
____________________________________________________

#Idea Background
1. Theme
Tema : Pendidikan

2. Problem
Masalah :  ketidaksesuaian metode pembelajaran

3. Solution
Solusi : Dapat membantu meningkatkan pembelajaran bagi siswa diluar dari materi sekolah yang diberikan oleh guru dan membantu siswa dalam mengerjakan tugas yang diberikan.
___________________________________________________
#Dataset and Algorithm
1. Dataset
Data Collection
Kami menggunakan dataset dari kaggel yang berisikan Kurikulum akademik yang ada di sekolah, Jadwal pembelajaran
Data & Nilai siswa, Data soal
.
Data Cleaning
Kami menggunakan pandas untuk membersihkan data. Berikut tabel contoh data yang belum dibersihkan dan yang sudah:
Poin soal dataset boleh ditambahkan sesuai kebutuhan.

2. Algorithm
Kami menerapkan algoritma Supported Vector Machine untuk membangun model yang dapat mengidentifikasi pola-pola penipuan dalam transaksi. Algoritma ini dipilih karena kemampuannya dalam menangani berbagai jenis fitur dan toleransi terhadap  data yang tidak seimbang.

Pembangunan Model
proses pembangunan dan  pelatihan model, mulai dari pengumpulan data, pra-pemrosesan data, pemilihan model, pelatihan model, hingga evaluasi model. Mungkin ada kotak-kotak yang mewakili setiap  langkah dengan panah yang menghubungkannya. 
Pengumpulan Data: Mengumpulkan data dari sumber yang relevan.
Pra-pemrosesan Data :Mengubah data kategorik ke numerik.
Pembagian Data:Memisahkan data menjadi set pelatihan (training set) dan set pengujian (testing set) untuk evaluasi model.
Pemilihan Model: Memilih algoritma machine learning yang sesuai, seperti SVM untuk data multi-kelas dan sangat cocok untuk masalah dengan banyak fitur.
Pelatihan Model:Melatih model menggunakan data pelatihan dan Menyempurnakan parameter model (hyperparameter tuning) untuk meningkatkan kinerja.
Evaluasi Model: Menyempurnakan parameter model (hyperparameter tuning) untuk meningkatkan kinerja dan Menggunakan metrik evaluasi seperti akurasi, precision, recall, dan F1-score.
Validasi Model: Menggunakan teknik validasi silang (cross-validation) untuk memastikan model tidak overfitting.
Deployment Model: Mengintegrasikan model yang sudah dilatih ke dalam web
Monitoring dan Maintenance: Memantau kinerja model secara berkala dan memperbarui model jika diperlukan.


Model Evaluation
perbandingan metrik kinerja SVM linear kernel yang kami gunakan dengan SVM kernel polynomial. Selain akurasi yang lebih tinggi, linear kernel memiliki waktu training yang lebih cepat yaitu 11ms, sedangkan polynomial kernel memiliki waktu training 16ms.
___________________________________________________
#Prototype
Chatbot pembelajaran adaptif dimulai dengan chatbot memperkenalkan diri dan menawarkan bantuan. Selanjutnya, chatbot mengumpulkan data tentang jam belajar, keterlibatan ekstrakurikuler, absensi, dan pekerjaan paruh waktu, dll. Data yang terkumpul kemudian dikirim ke model prediksi untuk menentukan performa akademik siswa. Berdasarkan hasil prediksi, chatbot memberikan saran yang sesuai: jika performa baik, chatbot memberikan pujian dan menawarkan bantuan tambahan; jika performa membutuhkan bantuan, chatbot memberikan saran spesifik untuk perbaikan. Siswa kemudian dapat mengajukan pertanyaan lebih lanjut atau menerima saran yang diberikan.

___________________________________________________
#Integration
 Model ini akan dideploy di IBM Watson dan akan diintegrasikan dengan aplikasi web front-end, memungkinkan siswa untuk memasukkan data dan menerima hasil prediksi secara real-time.

___________________________________________________
#Deployment
#Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.

___________________________________________________
#Result
Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.

___________________________________________________
#Conclusion
Disesuaikan dengan kebutuhan atau bisa ditiru dari laporan dokumentasi massive.

___________________________________________________
