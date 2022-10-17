*Disini saya akan menjelaskan cara pengggunaan GIT*

# *Pertama download apk git*

kalian download apk git terlebih dahulu,kalau sudah kita akan menggunakan git bash yaa..

# Cara membuat akun git

- Disini kalian harus membuat akun github terlebih dahulu ,untuk membuat repository server carilah digoggle git hub kemudian daftar terlebih dahulu,
kalau sudah mendaftar akun git hubnya kemudian kalian membuat repository baru

![Screenshot (11)](https://user-images.githubusercontent.com/115714443/196077347-aa017877-f513-43c3-811d-6297595be26f.png)

- Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

![Screenshot (12)](https://user-images.githubusercontent.com/115714443/196077659-0abbc672-a91c-4806-9c48-f74f0259bf77.png)

# Membuat file

- kita buat file dulu contoh seperti digambar

![Screenshot (13)](https://user-images.githubusercontent.com/115714443/196080310-8cb59fc2-2c5f-42ba-bd36-a35b77c9206b.png)
 
![Screenshot (14)](https://user-images.githubusercontent.com/115714443/196080325-5d633bcc-f0a9-4f09-85f8-86b4c82d93d8.png)

# Kemudian buka git bash

- Buatlah direktory baru dengan menggunakan perintah " mkdir lab pemrograman" LALU " cd lab pemrograman ",lanjut " mkdir latihan1 " LALU "cd latihan1.

- Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file     ini terbentuknya hidden.

- Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

![Screenshot (1)](https://user-images.githubusercontent.com/115714443/196081283-f14c5a1e-c1c1-4c71-ab8d-5bb6de49ce61.png)

#### **maaf ya kalau tidak rapi gambar contohnya**
#### **Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit**

- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status.

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit".(kalian akan akan disuruh masukin email dan username kalian yang
  kalian pakai untuk daftar github tadi),lalu kalian cek lagi dengan perintah commit -m “komentar commit".

![Screenshot (6)](https://user-images.githubusercontent.com/115714443/196082795-2661effb-8820-44ce-bbe2-e2cd89fc948a.png)
  
- File berhasil tersimpan
  Langkah berikutnya kita kembali ke website GitHub untuk melihat repository yang sudah dibuat.Di Quick Setup nanti ada url github kita, url tersebut untuk         perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_ image
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git image
Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. image
Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin m![Screenshot (6)](https://user-images.githubusercontent.com/115714443/196082508-45e586bd-0c68-49de-b181-6de84ec71faa.png)
elihat semua isi direektori gunakan perintah “ls -1" image

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya image

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
image

Selanjutnya klik write, jika sudah selesai klik saja commit change
image
