Nama: Izaz Falih
NIM: H1D024034
Shift: B

# SISTEM PAKAR DIAGNOSA PENYAKIT THT BERBASIS CONSOLE

## 1. Pendahuluan

Sistem pakar merupakan salah satu cabang dari kecerdasan buatan yang dirancang untuk meniru kemampuan seorang pakar dalam menyelesaikan suatu permasalahan. Dalam bidang kesehatan, sistem pakar dapat dimanfaatkan untuk membantu proses diagnosa penyakit berdasarkan gejala yang dialami oleh pengguna.

Pada tugas ini dibuat sebuah sistem pakar sederhana berbasis console menggunakan bahasa pemrograman Python untuk mendiagnosa penyakit THT (Telinga, Hidung, Tenggorokan).

## 2. Tujuan

Tujuan dari pembuatan program ini adalah:

1. Mengimplementasikan konsep sistem pakar dalam bentuk program Python.
2. Membantu pengguna dalam mengetahui kemungkinan penyakit berdasarkan gejala yang dipilih.
3. Menerapkan teknik pencocokan gejala menggunakan metode scoring.

## 3. Metode

Metode yang digunakan dalam sistem ini adalah metode pencocokan berbasis aturan (rule-based) dengan pendekatan scoring.

Langkah-langkah metode:

1. Pengguna memasukkan gejala yang dialami dalam bentuk kode.
2. Sistem mencocokkan gejala pengguna dengan setiap penyakit yang ada.
3. Setiap kecocokan gejala akan menambah nilai skor.
4. Penyakit dengan skor tertinggi akan dipilih sebagai hasil diagnosa.

## 4. Struktur Data

Program menggunakan struktur data dictionary untuk menyimpan data gejala dan penyakit.

### 4.1 Data Gejala

Data gejala disimpan dalam bentuk pasangan key dan value, di mana key merupakan kode gejala dan value merupakan deskripsi gejala.

### 4.2 Data Penyakit

Data penyakit disimpan dalam bentuk dictionary yang berisi nama penyakit sebagai key dan daftar kode gejala sebagai value.

## 5. Cara Kerja Program

1. Program menampilkan seluruh daftar gejala beserta kodenya.
2. Pengguna memasukkan kode gejala yang dialami dengan dipisahkan oleh spasi.
3. Input pengguna diubah menjadi list untuk memudahkan proses pencocokan.
4. Program melakukan perhitungan skor untuk setiap penyakit.
5. Program menentukan penyakit dengan skor tertinggi.
6. Hasil diagnosa ditampilkan kepada pengguna.

## 6. Contoh Penggunaan

Contoh input:
G34 G9

Contoh output:
Hasil diagnosa: ('Osteosklerosis', 2)

## 7. Kelebihan Program

1. Menggunakan struktur data yang sederhana dan mudah dipahami.
2. Menggunakan fungsi modular sehingga mudah dikembangkan.
3. Menggunakan metode scoring sehingga lebih fleksibel dibandingkan pencocokan langsung.

## 8. Kekurangan Program

1. Tidak memiliki validasi input yang kuat.
2. Tidak menampilkan solusi atau penanganan penyakit.
3. Tampilan masih berbasis console sehingga kurang interaktif.

## 9. Kesimpulan

Program sistem pakar diagnosa penyakit THT ini dapat membantu pengguna dalam mengetahui kemungkinan penyakit berdasarkan gejala yang dialami. Dengan menggunakan metode scoring, sistem dapat memberikan hasil yang lebih fleksibel dan mendekati kondisi nyata.

## 10. Cara Menjalankan Program

1. Pastikan Python sudah terinstall.
2. Jalankan program menggunakan perintah:
   python nama_file.py
3. Masukkan kode gejala sesuai yang ditampilkan.
4. Lihat hasil diagnosa yang diberikan oleh sistem.
