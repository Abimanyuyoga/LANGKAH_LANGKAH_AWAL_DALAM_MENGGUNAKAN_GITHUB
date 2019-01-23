# latihan01
# LANGKAH LANGKAH AWAL DALAM MENGGUNAKAN GITHUB

# Membuat akun pada layanan github
untuk menggunakan git, dibutuhkan sebuah layanan. Layanan yang tersedia sangat banyak namun saya menggunakan github, tidak masalah kalau nanti misalnya mau pindah ke layanan lain seperti gitlab seperti yang saya lakukan sekarang, karena saya tetap menggunakan keduanya.

![1111](https://user-images.githubusercontent.com/46512870/51582177-85b06580-1efd-11e9-8759-adbacbcfc414.png)

Setelah terbuat akun-nya, login dengan akun baru (kalau langsung diarahkan ke halaman utama), setelah itu pada pojok kanan atas terdapat tombol “+”, klik button tersebut dan pilih “new repository”.

# Membuat Repository online
![99](https://user-images.githubusercontent.com/46512870/51588545-24958b80-1f17-11e9-9451-415f398805de.png)


![zz](https://user-images.githubusercontent.com/46512870/51589496-c7e7a000-1f19-11e9-9bb6-b68ad3ac1572.png)

Lalu kalian akan diarahkan ke halaman pembuatan repository, pembuatan repositori ini tergantung dari project kalian yang mau kalian upload, jadi saya harapkan kalian sudah punya proyek yang ingin di upload ke repository.

Untuk mengisi, ada beberapa hal yang perlu di perhatikan :

•	Repository name : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga contohnya “Android/test” atau “js/test”.

•	Description : deskripsi repository (bisa kisah project dan siapa yang terlibat)

•	Public/Private : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup)

•	Intiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan, saya sarankan tidak usah di centang karena mempermudah praktek untuk mengelola git.

Setelah di isi sesuai dengan keinginan, klik saja tombol “create repository”, maka pada halaman selanjutnya akan menampilkan repository yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.

![untitled](https://user-images.githubusercontent.com/46512870/51589749-85729300-1f1a-11e9-9477-3a782131e9e0.png)


Mengupload folder (repository lokal)

Sebelum melakukan upload pastikan di PC atau laptop sudah tersedia git, untuk Windows bisa menggunakan cmder yang sempat saya tulis disini untuk memudahkan proses penggunaan git, sedangkan untuk pengguna linux bisa menginstall dengan menggunakan perintah “sudo apt-get install git” jika menggunakan OSX install dengan brew, jika sudah file siap di upload ke repository online.


jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line, atau jika belum terbiasa di command line (nanti belajar command line) buka saja folder tersebut menggunakan file exploler dan klik kanan “open terminal/cmder here”. Ada beberapa perintah dasar yang akan digunakan, perintah ini sudah tersedia kok saat membuat repo tadi (lihat gambar atas) 

git init 

git add .

git commit -m "first commit" 

git remote add origin https://github.com/AbimanyuYoga/Latihan1.git

git push -u origin master
 
