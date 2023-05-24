# Praktikum3_SQL

Nama    : MUHAMMAD FARHAN FAHREZA

NIM     : 312210380

Kelas   : TI.22.A.4

# SQL Constraint

- SQL Constraint digunakan untuk menentukan aturan untuk data dalam tabel

- Constraint digunakan untuk membatasi jenis data yang bisa masuk ke tabel

- Ini memastikan keakuratan dan keandalan data dalam tabel

- Constraint dapat berupa level kolom atau level tabel

- Constraint level kolom berlaku untuk kolom, dan batasan level tabel berlaku untuk seluruh tabel.

# Tugas Praktikum

1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen
 
2. Hapus satu record data pada tabel dosen yang telah dirujuk pada tabel mahasiswa
 
3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT
 
4. Lakukan perubahan data pada tabel dosen (kd_ds)
 
5. Lakukan penghapusan data pada tabel dosen
 
6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NUL
 
7. Lakukan penghapusan data pada tabel dosen

# Evaluasi dan Pertanyaan

- tulis semua perintah-perintah SQL percobaan di atas beserta outputnya laporan praktikum3 basis data.pdf

- Apa bedanya penggunaan RESTRICT dan penggunaan CASCADE

i. RESTRICT: Jika pengaturan RESTRICT diterapkan pada kunci asing, itu berarti ada pembatasan (restriction) yang diterapkan pada operasi penghapusan         atau pembaruan yang mempengaruhi baris yang dirujuk oleh kunci asing tersebut. Jika ada upaya untuk menghapus atau memperbarui baris yang memiliki referensi kunci asing, maka operasi tersebut akan gagal dan tidak ada perubahan yang akan terjadi. Dengan kata lain, RESTRICT membatasi tindakan yang melanggar integritas referensial.

ii. CASCADE: Di sisi lain, pengaturan CASCADE menghasilkan perilaku yang berbeda. Ketika kunci asing dikonfigurasi dengan CASCADE, itu berarti operasi penghapusan atau pembaruan yang dilakukan pada baris yang dirujuk oleh kunci asing akan dijejalkan (cascaded) ke baris yang terkait di tabel lain. Misalnya, jika Anda menghapus baris dari tabel utama yang memiliki referensi kunci asing di tabel terkait dengan CASCADE, maka semua baris yang berkaitan dalam tabel terkait juga akan dihapus. Ini memungkinkan perubahan yang dijejalkan (cascaded) ke seluruh database terkait dengan kunci asing tersebut.

- Berikan kesimpulan anda!

kesimpulannya adalah RESTRICT membatasi (restrict) operasi tersebut, sehingga operasi gagal jika ada referensi kunci asing yang terlibat. CASCADE memicu (cascade) operasi tersebut, menjadikan perubahan pada baris yang terkait di tabel lain.

- Buat laporan praktikum yang berisi, langkah-langkah praktikum beserta screenshot yang sudah dilakukan dalam bentuk dokumen(laporan praktikum3 basis data.pdf)

# SQL

- Mengubah data

<img width="755" alt="Jepretan Layar 2023-05-24 pukul 23 17 29" src="https://github.com/MhmmdFarhanFahrezza/Praktikum3_SQL/assets/116137842/2a411f4e-3f11-470c-b87f-ed2a12d38c21">
<img width="753" alt="Jepretan Layar 2023-05-24 pukul 23 21 41" src="https://github.com/MhmmdFarhanFahrezza/Praktikum3_SQL/assets/116137842/95de4127-2908-45ac-8473-d4174331e519">

- Menampilkan CREATE TABLE

<img width="752" alt="Jepretan Layar 2023-05-24 pukul 23 25 16" src="https://github.com/MhmmdFarhanFahrezza/Praktikum3_SQL/assets/116137842/0af269b2-132c-413a-b2e1-3d2889f25a7d">

- Mode ON UPDATE CASCADE ON DELETE CASCADE

<img width="758" alt="Jepretan Layar 2023-05-24 pukul 23 27 36" src="https://github.com/MhmmdFarhanFahrezza/Praktikum3_SQL/assets/116137842/c8e4bdb1-37e0-4452-b9ca-2bd789450f1c">

- Menghapus data

<img width="760" alt="Jepretan Layar 2023-05-24 pukul 23 29 02" src="https://github.com/MhmmdFarhanFahrezza/Praktikum3_SQL/assets/116137842/5afcd95c-3813-4d4b-a868-83ab531c07e7">

- Mode ON UPDATE CASCADE ON DELETE NOT NULL

<img width="750" alt="Jepretan Layar 2023-05-24 pukul 23 30 15" src="https://github.com/MhmmdFarhanFahrezza/Praktikum3_SQL/assets/116137842/8a4ebcd0-9cbb-477b-a700-d0a731543050">





