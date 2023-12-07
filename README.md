## GOOGLE COLAB

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/roniwahyu/dicoding-machine-learning-pemula/blob/main/rockscisorpaper.ipynb)

## GITPOD
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/roniwahyu/dicoding-machine-learning-pemula)

## CODESPACE
[![Open in Codespace](https://github.com/roniwahyu/python-twitter-pilpres2024/blob/main/codespace300x100.png)](https://github.com/codespaces/new?skip_quickstart=true&machine=standardLinux32gb&repo=728480807&ref=main&geo=SoutheastAsia)


# dicoding-machine-learning-pemula
Machine Learning Pemula DICODING

## Pengantar
Selamat, Anda telah berada di akhir pembelajaran dalam akademi ini. Anda sudah mempelajari dasar-dasar machine learning dan bagaimana jaringan saraf bekerja. Untuk bisa lulus dari akademi ini, Anda harus mengirimkan submission berupa program jaringan saraf tiruan menggunakan TensorFlow. Program Anda harus mampu mengenali bentuk tangan yang membentuk gunting, batu, atau kertas.

## Kriteria
#### Berikut kriteria submission yang harus Anda penuhi:

-   Dataset yang dipakai haruslah dataset berikut : [rockpaperscissors](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip), atau gunakan link ini pada wget command: [https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip).
-   Dataset harus **dibagi** menjadi **train set** dan **validation set**.
-   Ukuran validation set harus **40%** dari total dataset (data training memiliki 1314 sampel, dan data validasi sebanyak 874 sampel).
-   Harus mengimplementasikan **augmentasi gambar.**
-   Menggunakan image **data generator**.
-   Model harus menggunakan **model sequential**.
-   Pelatihan model tidak melebihi **waktu 30 menit**.
-   Program dikerjakan pada **Google Colaboratory**.
-   **Akurasi** dari model minimal **85%**.
-   Dapat **memprediksi gambar** yang diunggah ke Colab seperti gambar di bawah.
![enter image description here](https://d17ivq9b7rppb3.cloudfront.net/original/academy/202004302318257ec23b834046174a7d426680e488905e.png)
- Manambahkan **data diri** (sesuai profil Dicoding) pada **submission/project** yang dikirimkan.

## KRITERIA

Submission Anda akan dinilai oleh reviewer dengan **penilaian bintang** **ber****skala 1-5** berdasarkan dari parameter yang ada.

Anda dapat menerapkan beberapa **saran** untuk mendapatkan nilai tinggi, berikut sarannya:

-   Akurasi dari model di atas 85%
-   Anda menggunakan lebih dari 1 hidden layer.
-   Menerapkan lebih banyak augmentasi gambar.
-   Anda menggunakan optimizer dan loss-function yang tidak diajarkan di kelas.

Detail penilaian submission:

![rating-default-1](https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/submission-rating-badge/rating-default-1.png "rating-default-1")

Semua ketentuan terpenuhi, namun terindikasi melakukan plagiat.

![rating-default-2](https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/submission-rating-badge/rating-default-2.png "rating-default-2")

Semua ketentuan terpenuhi, namun penulisan kode masih perlu diperbaiki.

![rating-default-3](https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/submission-rating-badge/rating-default-3.png "rating-default-3")

Semua ketentuan wajib terpenuhi, namun tidak terdapat improvisasi atau persyaratan opsional yang dipenuhi.

![rating-default-4](https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/submission-rating-badge/rating-default-4.png "rating-default-4")

Semua ketentuan terpenuhi dan akurasi dari program di atas 95%.

![rating-default-5](https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/submission-rating-badge/rating-default-5.png "rating-default-5")

Semua ketentuan terpenuhi, akurasi di atas 96%, dan menggunakan tiga atau lebih teknik yang tidak diajarkan di modul seperti penggunaan Callback.

Jika **submission Anda ditolak** maka **tidak ada penilaian**. Kriteria penilaian bintang di atas hanya berlaku **jika submission Anda lulus**.

## KETENTUAN LAIN

### Submission yang Tidak Sesuai Kriteria

Jika submission Anda tidak sesuai dengan kriteria, maka akan ditolak oleh reviewer, berikut poin-poinnya:

-   Akurasi dari model Anda di bawah 85%.
-   Proses pelatihan model Anda memakan waktu lebih dari 30 menit.
-   Tidak menambahkan **data diri** (sesuai profil Dicoding) pada **submission/project** yang dikirimkan.

  

### Resources dan Tips

Berikut **T****ips** yang dapat Anda terapkan untuk mempermudah Anda menyelesaikan submission:

-   Model merupakan klasifikasi multi kelas sehingga loss function yang digunakan bukan binary_crossentropy.
-   Pastikan Anda membagi direktori untuk image data generator sesuai dengan jumlah label.
-   Untuk export project yang Anda kerjakan di Colaboratory sebagai berkas .ipynb, klik tombol file yang berada di **pojok kiri atas** Colaboratory dan pilih **download** .ipynb.  
    ![20200501002401b773f40df397fb5aed15666f519e0e49.png](https://d17ivq9b7rppb3.cloudfront.net/original/academy/20200501002401b773f40df397fb5aed15666f519e0e49.png)

  

### Forum Diskusi

Jika mengalami kesulitan, Anda bisa menanyakan langsung ke forum diskusi. [https://www.dicoding.com/academies/184/discussions](https://www.dicoding.com/academies/184/discussions?query=&query_criteria=&sort=&sort_direction=&title=&tutorial=8547&keywords=&creator=).

Beberapa diskusi berikut ini dapat digunakan untuk membantu submission Anda:

-   [diskusi1](https://www.dicoding.com/academies/184/discussions/68117),[](https://www.dicoding.com/academies/184/discussions/50629)
-   [diskusi2](https://www.dicoding.com/academies/184/discussions/50629), atau[](https://www.dicoding.com/academies/184/discussions/51999)
-   [diskusi3](https://www.dicoding.com/academies/184/discussions/51999).

  

### Ketentuan Berkas Submission

Beberapa poin yang perlu diperhatikan ketika mengirimkan berkas submission:

-   Menggunakan bahasa pemrograman **Python**.
-   Dataset menggunakan data yang disediakan di **resource**.
-   Mengirimkan pekerjaan Anda dalam bentuk berkas **.ipynb**.
-   Program yang Anda kirim pastikan adalah **berkas .ipynb yang sudah dieksekusi/dijalankan**. Sederhananya, jalankan semua cell pada submission Anda. Ketika seluruh output telah keluar, baru simpan program anda dalam format .ipynb.

  

### Ketentuan Proses Review

Beberapa hal yang perlu Anda ketahui mengenai proses review:

-   Tim penilai akan mengulas submission Anda dalam waktu **selambatnya 3 (tiga) hari kerja**, tidak termasuk hari sabtu, minggu dan libur nasional.
-   Tidak disarankan untuk melakukan submit berkali-kali karena akan memperlama proses penilaian yang dilakukan tim penilai.
-   Anda akan mendapat notifikasi hasil pengumpulan submission Anda via email, atau Anda dapat mengecek status submission pada akun Dicoding Anda.