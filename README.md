# Study-Case-Data-Analyst-Nafiasya


A. Project Overview
Project ini untuk mengidentifikasi karyawan yang berpotensi tinggi berdasarkan berbagai dimensi assestment dan berdasarkan talent benchmarking. Project ini memungkinkan evaluasi talenta yang objektif.

B. Tujuan Utama
Mengidentifiksi talenta terbaik berdasarkan kriteria benchmark.
Memungkinkan pengambilan keputusan HR berbasis data

C. Hasil Data
1. Employee_id yang digunakan sebagai benchmark talent adalah EMP100667.
2. Nilai final_match_rate masing-masing employee dibandingkan dengan benchmark talent.
3. Perhitungan gap_rate untuk setiap employee terhadap benchmark talent.
4.  Daftar 10 karyawan dengan nilai final_match_rate tertinggi.
5. Daftar 10 karyawan dengan nilai final_match_rate terendah.
6. Tiga tipe MBTI yang paling dominan pada kelompok 25% karyawan dengan final_match_rate tertinggi.
7. Tiga tema (Theme) yang paling dominan pada kelompok 25% karyawan dengan final_match_rate tertinggi.
8. Tiga nilai Directorate_ID yang paling sering muncul pada kelompok 25% karyawan dengan final_match_rate tertinggi.
9. Tiga nilai Area_ID yang paling sering muncul pada kelompok 25% karyawan dengan final_match_rate tertinggi.

D. Insight Data

1. Daftar 10 karyawan dengan nilai final_match_rate tertinggi.
   <img width="686" height="603" alt="image" src="https://github.com/user-attachments/assets/d8dde810-3286-4d32-adb4-fbb8abf108bd" />

2. Daftar 10 karyawan dengan nilai final_match_rate terendah
   <img width="673" height="592" alt="image" src="https://github.com/user-attachments/assets/1b25d088-804d-4ec2-93b7-fcd81bcbdd85" />

3. Top 3 Theme pada Top 25% final_match_rate
   <img width="677" height="270" alt="image" src="https://github.com/user-attachments/assets/17d25341-288b-4574-98b2-1ad33606d479" />

4. Top 3 MBTI pada Top 25% final_match_rate
   <img width="756" height="275" alt="image" src="https://github.com/user-attachments/assets/347e75ca-8a1e-462e-be2a-d6fdf85ae8a1" />

5. Top 3 directorate_id pada Top 25% final_match_rate
  <img width="655" height="295" alt="image" src="https://github.com/user-attachments/assets/9eaa131b-d17b-41ba-a71c-205d65562254" />

6. Top 3 area_id pada Top 25% final_match_rate
   <img width="641" height="263" alt="image" src="https://github.com/user-attachments/assets/b64e7f54-55bc-470b-a1c3-f0d817d5a1d9" />

E. Dampak Bisnis
1. Metrik objektif untuk keputusan promosi
2. Pendekatan terstandarisasi untuk evaluasi talenta
3. Insight berbasis data untuk pengembangan karyawan

F. Final Sucess Formula
Final Match Rate dihitung untuk mengukur tingkat kesesuaian seorang karyawan terhadap benchmark talent berdasarkan tiga dimensi utama: Trait Values (TV), Trait Govern Values (TGV), serta Employee Profile Fit.
Nilai akhir dihitung menggunakan formula:
<img width="582" height="65" alt="image" src="https://github.com/user-attachments/assets/50b843b0-fef4-4ebe-9352-862e0abf1dcd" />
Masing-masing komponen disusun menggunakan aturan penilaian yang menggabungkan indikator numerik dan indikator kategorikal sesuai standar benchmark talent.

1. TV Match Rate

TV Match Rate disusun dari dua kelompok penilaian: (a) indikator numerik dan (b) indikator kategorikal.
Semua indikator diberikan bobot yang sama sebesar 14,2857% (1/7), sehingga total bobot adalah 100%.

a. Indikator Numerik 
Empat variabel numerik dievaluasi dengan prinsip:
- Jika nilai memenuhi atau melampaui benchmark → skor 100%
- Jika tidak memenuhi → skor proporsional
- 
  <img width="405" height="97" alt="image" src="https://github.com/user-attachments/assets/85bacf45-34eb-4fa0-a32a-b9da798d44d7" />
  
  Indikator numerik yang digunakan:
  
  <img width="669" height="255" alt="image" src="https://github.com/user-attachments/assets/74a56c9e-ca93-4394-9849-a9fb4d530eb3" />


b. Indikator Kategorikal (Exact Match)
Tiga variabel kategorikal diberikan skor 100% apabila exact match dengan benchmark talent, dan 0% bila tidak cocok.

Indikator kategorikal:

<img width="605" height="204" alt="image" src="https://github.com/user-attachments/assets/0aa9ce7b-dcf6-4c18-aaa6-d58991e73d11" />


maka dari itu didapatkan formula tv_match_rate sebagai berikut

<img width="941" height="291" alt="image" src="https://github.com/user-attachments/assets/6d573237-4239-4efa-bf88-7cf77e6c5ff6" />


2. TGV Match Rate

TGV Match Rate dihitung dari tiga indikator kategorikal yang masing-masing mewakili dimensi psikologis lain.
Setiap indikator bernilai 100% jika cocok, dan 0 jika tidak:

<img width="782" height="205" alt="image" src="https://github.com/user-attachments/assets/6eed83fe-a56c-4b5e-aac8-45fc2dc3a1cd" />


TGV Match Rate dihitung dengan rata-rata:

<img width="612" height="79" alt="image" src="https://github.com/user-attachments/assets/8075d93d-665c-49ef-ba99-8f67aff4cc7a" />

<img width="941" height="166" alt="image" src="https://github.com/user-attachments/assets/78cbb922-19f8-4f82-8097-22b73285e091" />

3. Employee Match Rate
Employee Match Rate menggunakan empat variabel, masing-masing memiliki bobot 25%.

a. Variabel Numerik
Years of service mempunyai Benchmark: ≥ 109 bulan
Skor dihitung proporsional apabila di bawah benchmark.

b. Variabel Kategorikal
Diberikan skor 100% jika cocok, dan 0 jika tidak:

<img width="924" height="290" alt="image" src="https://github.com/user-attachments/assets/e775bc04-1a48-47aa-8692-8d1af62be35d" />


<img width="587" height="413" alt="image" src="https://github.com/user-attachments/assets/ebd399c0-0c1e-490a-ba46-9a6001f2c8cc" />



   Ketiga match rate — TV, TGV, dan Employee — dirancang untuk mengukur kesesuaian karyawan terhadap benchmark talent pada aspek:
- Trait Value (TV) → gabungan indikator psikometrik numerik & kategorikal
- Talent Group Values (TGV) → kecocokan terhadap karakteristik perilaku dan kognitif
- Employee Profile → kesesuaian terhadap data employee termasuk masa kerja employee
Final Match Rate memberikan penilaian komprehensif dengan pendekatan multi-dimensi yang mempertimbangkan psikometrik, perilaku, data employee secara seimbang.

F. EDA, SQL dan Algoritma
1. Data Preparation
   
a. Normalisasi Data Rating
Pada tahap awal, dilakukan proses normalisasi terhadap variabel rating untuk memastikan data berada dalam rentang nilai standar yaitu 1 hingga 5. Hal ini diperlukan karena ditemukan adanya outlier, yaitu nilai rating 6 dan 99, yang berada jauh di luar kisaran yang valid dan berpotensi mengganggu kualitas analisis.

<img width="340" height="216" alt="image" src="https://github.com/user-attachments/assets/fc4171ee-446b-47f6-9a1f-1fa1680cbdad" />


Untuk menangani outlier tersebut, digunakan metode median imputation, di mana nilai–nilai rating yang berada di luar rentang valid diganti dengan nilai median dari distribusi rating. Pendekatan ini dipilih karena median lebih robust terhadap pencilan (robust to extreme values) dibandingkan mean, sehingga menghasilkan distribusi data yang lebih representatif.

Setelah proses imputasi dilakukan, distribusi rating menjadi lebih stabil dan konsisten dengan rentang nilai standar. Berikut adalah distribusi nilai rating setelah dilakukan outlier handling menggunakan median imputation

<img width="447" height="200" alt="image" src="https://github.com/user-attachments/assets/d60edf35-25ad-4482-a7bc-f7a52b063259" />

b. Penanganan Missing Values dan Encoding Variabel Kategorikal
Sebelum dilakukan analisis korelasi antarvariabel, dilakukan proses data cleaning tambahan untuk memastikan kualitas data sebagai berikut:

1. Imputasi Missing Values
   Kolom iq dan gtq memiliki nilai hilang (nulls), sehingga dilakukan imputasi menggunakan nilai mean, karena kedua variabel ini bersifat numerik dan berdistribusi relatif stabil.
   Kolom mbti memiliki nilai hilang, sehingga diimputasi menggunakan nilai modus (frekuensi terbanyak), karena mbti adalah variabel kategorikal.

2. Encoding Variabel Kategorikal
   Kolom disc_word dan mbti, yang merupakan variabel kategorikal, kemudian dilakukan proses label encoding untuk mengonversi nilai kategori menjadi format numerik.
   Encoding diperlukan agar variabel tersebut dapat digunakan dalam analisis numerik, seperti korelasi, modelling machine learning, atau perhitungan match rate.

  <img width="941" height="339" alt="image" src="https://github.com/user-attachments/assets/ef81e12c-b5da-47d2-8044-31ab9a1d262a" />

  
variabel scale_code dan theme juga terlebih dilakukan proses label encoding untuk mengubah data kategorikal menjadi numerik sehingga dapat diolah dalam perhitungan korelasi.

<img width="904" height="247" alt="image" src="https://github.com/user-attachments/assets/6452f0fe-f94d-48a7-b409-3e861cefbfc8" />


c. Pembuatan Kolom Category
Untuk keperluan analisis klasifikasi sederhana, dibuat sebuah kolom baru bernama category dengan aturan sebagai berikut:
- Jika rating = 5, maka category = 1
- Jika rating ≠ 5, maka category = 0
Kategori ini digunakan untuk mengelompokkan karyawan berdasarkan performa tertinggi (rating 5) dan bukan performa tertinggi.

<img width="409" height="399" alt="image" src="https://github.com/user-attachments/assets/eb350434-ee63-4601-97d2-d9ded52b59fb" />

2. Analisa Korelasi

a. Korelasi Employee dengan performance
Tahap selanjutnya adalah melakukan analisis korelasi antara data employee dan data performance menggunakan heatmap correlation matrix. Visualisasi ini memberikan gambaran mengenai kekuatan hubungan antara masing-masing variabel dan kategori employee dengan rating terbaik (category = 1).

<img width="886" height="634" alt="image" src="https://github.com/user-attachments/assets/08073641-3e8b-460e-bdcf-b0236e24590d" />


Berdasarkan hasil analisis, diperoleh bahwa variabel-variabel employee yang memiliki kontribusi paling signifikan terhadap probabilitas seorang karyawan masuk kategori performa tertinggi adalah sebagai berikut (diurutkan berdasarkan skor probabilitas terbesar):
1.years_of_service_months
2. education_id
3. directorate_id
4. company_id
5. area_id

Variabel-variabel tersebut memiliki korelasi positif yang lebih kuat dibanding variabel lainnya, sehingga berpotensi menjadi faktor penting dalam pembentukan performa employee.


b.	Analisa korelasi data profiles_psych dengan data performance 
Selanjutnya dilakukan analisis korelasi antara data profile_psych dengan performance setelah seluruh variabel kategorikal melalui proses label encoding. Analisis ini bertujuan untuk mengidentifikasi variabel psikologis yang paling berpengaruh terhadap probabilitas karyawan memperoleh category = 1 (rating tertinggi).

<img width="783" height="699" alt="image" src="https://github.com/user-attachments/assets/7e261329-64ea-4076-b9da-0e8e18d1dd01" />


Berdasarkan hasil evaluasi korelasi, variabel–variabel dalam profile_psych yang memiliki tingkat pengaruh terbesar terhadap kategori kinerja (category = 1), secara berurutan dari yang paling signifikan hingga yang paling rendah adalah sebagai berikut:
1. Tiki
2. MBTI
3. Pauli
4. Faxtor
5. Disc_word

c. Analisis Korelasi antara PAPI Score, Strengths, dan Performance

<img width="841" height="775" alt="image" src="https://github.com/user-attachments/assets/1c5d86b5-5ec4-44eb-8fce-d4713295677a" />


Berdasarkan hasil analisis, variabel–variabel dari kelompok papi_score dan strengths yang memberikan kontribusi paling besar terhadap kategori = 1, dari yang paling berpengaruh hingga paling rendah, adalah sebagai berikut:
1. Rank
2. PAPI Score
3. Theme

3. Analisa Heatmap per variabel
Analisis heatmap per variabel dilakukan untuk memperoleh pemahaman yang lebih mendalam mengenai pola hubungan antara masing-masing variabel dengan kategori rating = 5 (category = 1). Pendekatan ini memungkinkan identifikasi yang lebih terperinci terhadap rentang nilai variabel yang memiliki probabilitas tinggi dalam memengaruhi peluang seorang karyawan masuk ke kategori rating 5.

Melalui visualisasi heatmap, setiap variabel dianalisis secara individual untuk melihat intensitas korelasinya dan menentukan nilai-nilai spesifik yang berpotensi memberikan kontribusi signifikan terhadap pencapaian category = 1. Pendekatan ini membantu memastikan bahwa evaluasi dilakukan tidak hanya pada tingkat agregat, tetapi juga mempertimbangkan variasi nilai di dalam setiap variabel, sehingga menghasilkan insight yang lebih akurat dan actionable untuk pengambilan keputusan berbasis data.

a. years_of_service_months

<img width="692" height="369" alt="image" src="https://github.com/user-attachments/assets/1ea33414-2811-4638-9754-d178db2250e7" />

<img width="570" height="499" alt="image" src="https://github.com/user-attachments/assets/7ebee7bf-2d7c-45ac-aac3-13cdf6cb463e" />

<img width="523" height="279" alt="image" src="https://github.com/user-attachments/assets/ba49ca2c-8a42-4d2e-a1f9-74b015d8be34" />

b. education_id

<img width="572" height="356" alt="image" src="https://github.com/user-attachments/assets/2194d1f9-e7f7-42d9-9efb-d5042361d59b" />

<img width="367" height="365" alt="image" src="https://github.com/user-attachments/assets/7bdb169d-398e-4780-88a1-464cb6ed346b" />


c. directorate_id


<img width="651" height="340" alt="image" src="https://github.com/user-attachments/assets/f6c3d41e-66fe-4db7-865a-5616bb92af4d" />


<img width="357" height="286" alt="image" src="https://github.com/user-attachments/assets/d3b7809b-705e-4bbf-b390-408fa00f279c" />

d. area_id


<img width="569" height="259" alt="image" src="https://github.com/user-attachments/assets/01589eef-c38e-4660-894d-29cbc9ed56a0" />


<img width="315" height="359" alt="image" src="https://github.com/user-attachments/assets/a802b162-0efb-457f-99e0-bb242de63226" />

e. company_id


<img width="637" height="333" alt="image" src="https://github.com/user-attachments/assets/7063369a-35da-4bfb-ad4a-5b04b29f3954" />


<img width="814" height="245" alt="image" src="https://github.com/user-attachments/assets/bccb25f7-649c-4f67-917e-00535268c4d7" />

e. tiki


<img width="632" height="333" alt="image" src="https://github.com/user-attachments/assets/8e7886d9-5d95-408a-9a11-f837b7ac3a7f" />


<img width="685" height="358" alt="image" src="https://github.com/user-attachments/assets/ee38c451-99e5-4521-9c42-de68b1dbec01" />


<img width="318" height="284" alt="image" src="https://github.com/user-attachments/assets/644459d2-1aa6-4ac8-be55-c28bec06b757" />

f. mbti


<img width="657" height="413" alt="image" src="https://github.com/user-attachments/assets/7af504be-f6e2-4d54-8a81-ae8c6b8a9c48" />


<img width="319" height="720" alt="image" src="https://github.com/user-attachments/assets/2874c7b5-e49c-4ccc-baf3-93a09c34740b" />


g. pauli


<img width="622" height="471" alt="image" src="https://github.com/user-attachments/assets/1a22334d-94fd-40ac-a878-4f39e410e60c" />


<img width="314" height="273" alt="image" src="https://github.com/user-attachments/assets/a8309340-672b-46e4-bdcc-dac640eba5b9" />

h. faxtor

<img width="569" height="513" alt="image" src="https://github.com/user-attachments/assets/96227487-d600-4f06-b6ed-53754129c1a2" />


<img width="399" height="149" alt="image" src="https://github.com/user-attachments/assets/9296098d-9222-44f5-890a-309ab5316dc2" />

i. rank


<img width="701" height="370" alt="image" src="https://github.com/user-attachments/assets/571a800e-ccff-4928-937c-0e6b454623c1" />


<img width="579" height="532" alt="image" src="https://github.com/user-attachments/assets/2a8daaff-769d-40a5-92cb-713f0f3d320d" />


<img width="412" height="157" alt="image" src="https://github.com/user-attachments/assets/e56f8b75-97e2-4d1b-bc6e-608d9e30e9d8" />

j.papi_score


<img width="633" height="333" alt="image" src="https://github.com/user-attachments/assets/63cd06d1-acce-4639-b5c5-81afa0e04450" />


<img width="628" height="552" alt="image" src="https://github.com/user-attachments/assets/5bab3cb5-e9d6-4fe1-bfa3-f2116624af42" />


<img width="449" height="193" alt="image" src="https://github.com/user-attachments/assets/cf88f022-6351-471f-aa8f-900afa6eafff" />


k. theme


<img width="941" height="657" alt="image" src="https://github.com/user-attachments/assets/f3c96327-2f30-47f3-ae60-8a367f8210be" />


<img width="515" height="772" alt="image" src="https://github.com/user-attachments/assets/4456cdbd-6749-448b-99ac-4b8284f92d91" />

<img width="502" height="76" alt="image" src="https://github.com/user-attachments/assets/ee598e53-01d2-49cb-bc29-51381157c69c" />
























































