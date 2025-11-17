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


















