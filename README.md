#lab_pemrograman
# pertama download apk git
kalian download apk git terlebih dahulu,kalau sudah kita akan menggunakan git bash yaa..
*Cara membuat akun git
Disini kalian harus membuat akun github terlebih dahulu ,untuk membuat repository server carilah digoggle git hub kemudian daftar terlebih dahulu

Membuat repositori baru

kalau sudah mendafta akun git hubnya kemudia kalian membuat repositori baru

![Screenshot (11)](https://user-images.githubusercontent.com/115714443/196077347-aa017877-f513-43c3-811d-6297595be26f.png)

Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

![Screenshot (12)](https://user-images.githubusercontent.com/115714443/196077659-0abbc672-a91c-4806-9c48-f74f0259bf77.png)

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
