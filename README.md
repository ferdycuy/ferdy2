#lab_pemrograman
# DOWNLOAD APK GIT
pertama kalian download apk git terlebih dahulu
Cara membuat akun git
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com

image

Setelah selesai mengisi user name dan user email anda klik daftar akun GitHub(nanti ada gambar hewan terbalik disitu anda cuma membenarkan posisi gambar tersebut untuk verivikasi), lalu next select a plan dan pilih yang gratisan saja 🤣 :trollface: image image

Pada langka selanjutnya pilih sesuai keinginan anda atau boleh langsung diskip saja.

image

Kemudian anda akan dialihkan Gmail untuk memverifikasi email, klik Verivy email address

image

Membuat repositori baru
Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.

image

Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

image

Membuat Reposiory Local
Lalu kita buka file explorer pilih dilocal disk e (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . image

Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.name “nama_user” $ git config --global user.email “nama_user”

image Nb : Ingat harus melaukukan konfigurasi terlebih dahulu apabila belum nanti akan mengalami kegagalan saat melakukan perintah git commit. “nama_user” DIGANTI, diganti dengan akun user github anda

Buatlah direktori baru dengan menggunakan perintah " mkdir latihan1" LALU " cd latihan1 ".

image

Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.

image

Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls

image

Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git status. image

Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m “komentar commit" image

File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_ image
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git image
Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. image
Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah “ls -1" image

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya image

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.
image

Selanjutnya klik write, jika sudah selesai klik saja commit change
image
