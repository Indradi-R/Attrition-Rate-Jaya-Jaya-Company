# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding

Jaya Jaya Maju merupakan salah satu perusahaan multinasional yang telah berdiri sejak tahun 2000. Ia memiliki lebih dari 1000 karyawan yang tersebar di seluruh penjuru negeri. 

Walaupun telah menjadi menjadi perusahaan yang cukup besar, Jaya Jaya Maju masih cukup kesulitan dalam mengelola karyawan. Hal ini berimbas tingginya attrition rate (rasio jumlah karyawan yang keluar dengan total karyawan keseluruhan) hingga lebih dari 10%.

### Permasalahan Bisnis

Mengidentifikasi berbagai faktor yang mempengaruhi tingginya attrition rate pada perusahaan Jaya Jaya Maju.

### Cakupan Proyek

Proyek ini mencakup analisis data yang berasal dari dataset yang telah diberikan untuk diindentifikasi faktor-faktor yang mempengaruhi attrition rate pada perusahaan.
Proyek ini juga mencakup pembuatan dashboard untuk keperluan visualisasi dari analisis yang telah ditemukan pada data yang digunakan.

### Persiapan

Sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/employee/employee_data.csv

Setup environment:
- Install library yang dipakai
```
pip install -r requirements. txt
```
- Buka prediction.py dan path menjadi nama file (.csv)
```
data_to_predict = pd.read_csv('YOUR FILE') 
```
- Jalankan prediction.py
```
python prediction.py
```

## Business Dashboard

Dashboard ini dirancang untuk membantu departemen HR dalam memahami data karyawan dan memonitor tingkat attrition. Visualisasi yang dibuat meliputi:

Jumlah karyawan aktif saat ini (Current Employee): Menampilkan total karyawan yang masih bekerja.
Attrition Rate: Persentase karyawan yang keluar dibandingkan dengan total karyawan.
Total Attrition: Jumlah karyawan yang keluar selama periode tertentu.
Analisis berdasarkan Gender: Membandingkan jumlah karyawan yang tetap dan keluar berdasarkan gender.
Analisis berdasarkan Kelompok Umur dan Tingkat Pendidikan: Mengidentifikasi pola attrition berdasarkan kelompok umur dan pendidikan.

## Conclusion

Temuan Utama
Jumlah Karyawan Aktif: Perusahaan memiliki total 1.291 karyawan aktif.
Attrition Rate: Tingkat attrition adalah 12,18%, yang tergolong tinggi dibandingkan standar industri.
Faktor-faktor yang Memengaruhi Attrition:
Gender: Karyawan laki-laki memiliki jumlah attrition lebih tinggi dibandingkan perempuan.
Kelompok Umur: Karyawan di rentang usia 26-35 tahun memiliki tingkat attrition tertinggi.
Pendidikan: Karyawan dengan pendidikan Bachelor dan Master cenderung memiliki tingkat attrition lebih tinggi.

### Rekomendasi Action Items (Optional)

Berikan beberapa rekomendasi action items yang harus dilakukan perusahaan guna menyelesaikan permasalahan atau mencapai target mereka.

- Tawarkan insentif kepada karyawan laki-laki untuk meningkatkan loyalitas mereka.
- Lakukan survei kepuasan kerja secara rutin untuk karyawan dengan pendidikan Bachelor dan Master untuk mengidentifikasi penyebab utama attrition.
