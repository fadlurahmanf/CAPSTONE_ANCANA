# BangkitCapstone B21 CAP-0252

Projek ini dikembangkan sebagai salah satu capstone project dariBangkit Academy. Deliverables yang diharapkan dari projek ini adalah pembuatan aplikasi (ANCANA) yang memiliki fitur dalam memprediksi bencana Alam yang terjadi. Untuk melihat model Machine Learning yang dibuat oleh kelompok kami dapat dilihat dengan mengakses Hyperlink berikut [Google Colab](https://colab.research.google.com/drive/12gzc5PqxnKfWn4LO_S5XKL2BXNCBWIDN?usp=sharing"). Kita juga akan memanfaatkan flask dashboard sederhana sebagai perantara untuk deploy dalam google cloud platform.

FILE DOWNLOAD APK : https://drive.google.com/drive/folders/1nH9zyz4rr_88fy1i8S7hvMzU8ARNo0ea?usp=sharing


## Dependencies
Jika Bapak/Ibu menggunakan Google Collaboratory secara langsung maka tidak perlu melakukan instalasi library, namun jika menggunakan jupyternotebook pastikan beberapa library ketika running setiap cell code nya sudah terpenuhi. Ada diantaranya :

- pandas
- flask
- matplotlib

Atau Bapak Ibu cukup menginstall requirements.txt dengan cara berikut untuk kebutuhan Flask nya

```python
pip install -r requirements.txt
```

## Rubics

- Environment preparation 
- Saving model dengan bentuk .h5 untuk dapat dikonsumsi oleh backend service Flask
- Implementing it on flask dashboard
- Deploy to GCP

## What You Need to Do

* Memulai dengan memahami model di machine learning yang berada di google collab atau ipynb yang sudah kelompok kami buat
* Bapak/Ibu dapat meng-clone repo ini.
* Silahkan buka notebook template pada capstone ini dan isi sesuai dengan arahan yang ada. Pastikan Bapak/Ibu memberikan analisa yang dibutuhkan pada notebook tersebut.
* File di repo ini adalah skeleton yang dapat digunakan untuk membuat flask dashboard sederhana.


### ANDROID

Aplikasi Ancana terbagi menjadi 2, yang pertama adalah aplikasi untuk _user_ dan yang kedua aplikasi pengguna.

## APLIKASI USER

Aplikasi user terbagi menjadi 4 menu utama, yang pertama adalah menu home. pada menu home, user dapat melihat daftar kontak kontak penting instansi terkait bencana alam. pada menu utama juga terdapat informasi terkait langkah langkah pertama ketika terjadinya bencana alam. menu kedua adalah menu lapor, menu ini adalah menu pengambilan gambar dari pengguna, hasil gambar yang sudah diambil oleh pengguna, akan diprediksi tipe bencananya sebelum dikirimkan menuju admin. menu yang ketiga adalah menu activity, pada menu ini akan ditampilkan semua daftar laporan bencana alam dari pengguna lainnya. menu yang keempat adalah menu notification, menu ini akan memberitahukan laporan progress dari laporan yang sudah dilaporkal oleh pengguna

## APLIKASI ADMIN

Aplikasi Admin terdiri dari 3 menu utama, menu waiting, menu onProgress, dan menu Complete. Menu waiting adalah menu yang berisi daftar laporan dari user yang belum diproses oleh petugas. Menu onProgress adalah menu yang berisi daftar kasus yang sudah mulai di proses oleh petugas tetapi belum selesai. menu complete berisi detail laporan yang sudah diselesaikan oleh petugas__

### The Final Mission

Happy learning! 
