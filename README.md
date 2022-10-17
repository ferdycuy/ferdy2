*Disini saya akan menjelaskan cara pengggunaan GIT*

# *Pertama download apk git*

kalian download apk git terlebih dahulu,kalau sudah kita akan menggunakan git bash yaa..

## Membuat akun github.

- Disini kalian harus membuat akun github terlebih dahulu ,untuk membuat repository server carilah digoggle git hub kemudian daftar terlebih dahulu,
kalau sudah mendaftar akun git hubnya kemudian kalian membuat repository baru

![Screenshot (11)](https://user-images.githubusercontent.com/115714443/196077347-aa017877-f513-43c3-811d-6297595be26f.png)

- Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

![Screenshot (12)](https://user-images.githubusercontent.com/115714443/196077659-0abbc672-a91c-4806-9c48-f74f0259bf77.png)

## Membuat file

- kita buat file dulu contoh seperti digambar

![Screenshot (13)](https://user-images.githubusercontent.com/115714443/196080310-8cb59fc2-2c5f-42ba-bd36-a35b77c9206b.png)
 
![Screenshot (14)](https://user-images.githubusercontent.com/115714443/196080325-5d633bcc-f0a9-4f09-85f8-86b4c82d93d8.png)

## Buka git bash

- Buatlah direktory baru dengan menggunakan perintah " mkdir lab pemrograman" LALU " cd lab pemrograman ",lanjut " mkdir latihan1 " LALU "cd latihan1.

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file     ini terbentuknya hidden.

- Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

![Screenshot (1)](https://user-images.githubusercontent.com/115714443/196081283-f14c5a1e-c1c1-4c71-ab8d-5bb6de49ce61.png)
#### *NB:maaf ya kalau tidak rapi contoh gambarnya*
#### *Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit*

- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit".(kalian akan akan disuruh masukin email dan username kalian yang
  kalian pakai untuk daftar github tadi),lalu kalian cek lagi dengan perintah commit -m “komentar commit".

![Screenshot (6)](https://user-images.githubusercontent.com/115714443/196082795-2661effb-8820-44ce-bbe2-e2cd89fc948a.png)
  ##### *file berhasil tersimpan*
  
- Langkah berikutnya kita kembali ke website GitHub untuk melihat repository yang sudah dibuat.Di Quick Setup nanti ada url github kita, url tersebut untuk         perintah_ “git remote add origin [url] 
 
- Sudah mengetahui url githubnya lalu ketik perintah "git remote add origin [url]",urlnya diganti dengan url github anda https://github.com/ferdy2/Gitlatihan1.git

- Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan username dan pasword github kita ya.

- Jika ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/ferdy2/Gitlatihan1.git . Jika ingin masuk kedirectory gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direktori gunakan perintah “ls -1" image

![Screenshot (7)](https://user-images.githubusercontent.com/115714443/196121644-a9691fe8-f88e-4678-8be3-0fe95b4100a6.png)
##### *maaf kalo contoh gambarnya berantakan*

- Selesai ,Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

![Screenshot (15)](https://user-images.githubusercontent.com/115714443/196122774-9d5f09a5-ec81-4c46-b363-37af8e8e8534.png)
##### *klik code,maka akan berubah menjadi file README,md*

- FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
image

- Selanjutnya klik write, jika sudah selesai klik saja commit change

![Screenshot (16)](https://user-images.githubusercontent.com/115714443/196122988-de2c9a54-da66-4798-be2d-625843a834ac.png)

    # finish,terimakasi 
