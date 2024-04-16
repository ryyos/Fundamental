# INTRODUCTION TERMUX

Termux adalah sebuah aplikasi yang memungkinkanmu untuk menggunakan perintah dan menjalankan program seperti yang biasa dilakukan di komputer, tapi melalui antarmuka teks sederhana.

seperti kamu ingin membuat sebuah folder, kalau biasa nya kalian tinggal membuka file manager dan me click buat folder. tapi dengan termux kita membuat folder dengan sebuah command / perintah di terminal, jadi tidak ada lagi tampilan grafis (GUI)

## Glosarium

1.  direktory: folder
2.  package: folder yang terdapat file program
3.  terminal: tempat di mana Anda dapat memberikan instruksi/ command/ perintah menggunakan teks untuk melakukan berbagai tugas seperti membuat file, mengubah direktori (folder), atau menjalankan program. Jadi, terminal adalah tempat di mana kita berbicara dengan komputer menggunakan bahasa yang dimengerti oleh sistem operasi.
4.  flag: command tambahan contoh ( **rm -r** ) -r merupakan flag

## TERMUX PARTS

di termux ada beberapa hal yang kalian harus tau untuk mempermudah kedepannya

1. ketika kalian membuka termux semua tampilan itu merupakan terminal tempat mengetikan perintah / command

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/00.jpg"> 
</div>
<br>

2. termux memiliki manajer paket sendiri yang disebut apt/pkg. mudahnya seperti sebuah program untuk menginstall aplikasi, contoh kalau di hp kalian ingin menginstall sebuah game POU maka kalian akan men download nya di playstore dan akan otomatis terinstall. apt mirip seperti itu kalian menginstall nya dengan perintah **"apt install POU"** ( hanya contoh! bukan berarti kalian bisa menginstall POU)

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/8.jpg"> 
</div>
<br>

## BASIC COMMANDS

<br>
1. ls: Untuk menampilkan daftar file dan folder di direktori saat ini.

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/4.jpg"> 
</div>
<br>
2. cd: Untuk berpindah antara direktori.
   <br>
   <br>

- cd nama_folder | pindah ke folder yang di tuju
<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/1.jpg"> 
</div>
<br>

* cd .. | kembali 1 folder
<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/2.jpg"> 
</div>
<br>

* cd ../.. | kembali 2 folder

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/3.jpg"> 
</div>
<br>
3. mkdir: Untuk membuat direktori baru.
<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/5.jpg"> 
</div>
<br>
4. rm: Untuk menghapus file atau direktori.
<br>
<br>
* rm nama_file.txt | menghapus file
<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/7.jpg"> 
</div>
<br>
* rm -r nama_folder | menghapus folder
<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/8.jpg"> 
</div>
<br>

<br>
5. apt: Untuk mengelola paket-paket aplikasi Termux.

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/8.jpg"> 
</div>
<br>

6. touch: untuk membuat file

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/6.jpg"> 
</div>
<br>

7. nano: mengedit isi file

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/12.jpg"> 
</div>
<br>

untuk keluar click ctrl+x -> Y -> enter

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/13.jpg"> 
</div>
<br>

## PREPARE TERMUX

1. buka termux dan jalankan command `termux-setup-storage` | nanti akan muncul pop up meminta perizinan peyimpanan dan klik izinkan

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/01.jpg"> 
</div>
<br>

2. jalankan command `pkg install root-repo && pkg install x11-repo`

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/1.jpg"> 
</div>
<br>

3. jalankan command `apt update && apt upgrade`

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/2.jpg"> 
</div>
<br>

4. install git dengan command `apt install git`

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/8.jpg"> 
</div>
<br>

5. install python3 dengan command `apt install python3` | tekan y dan enter

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/9.jpg"> 
</div>
<br>

6. jalankan command `python3 --version` untuk mengecek apakah python3 sudah berhasil di install atau belum

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/10.jpg"> 
</div>
<br>

## PREPARE github

1. buka url ini https://github.com/settings/tokens | pastikan kalian sudah login ke github terlebih dahulu

2. kalian click **Generate New token** dan pilih yang **Generate New token (clasic)**

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/22.jpg"> 
</div>
<br>

3. masukan note (bebas) dan centang semua yang ada di select scopes

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/23.jpg"> 
</div>
<br>

4. kalau sudah click tombol hijau di paling bawah

5. kalau sudah kalian akan di beri sebuah **token** pastikan untuk menyimpannya dan jangan beri tahu ke orang lain, karena itu seperti sebuah kunci

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/24.jpg"> 
</div>
<br>

## Fundamental

kita akan membuat sebuah program yang sangat sederhana untuk latihan yaitu **kalkulator**

1. buat repository github dengan nama-kalkulator | contoh: ryo-kalkulator

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/19.jpg"> 
</div>
<br>

2. kalau tampilan nya sudah seperti ini berarti benar

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/git-basic/3.jpg"> 
</div>
<br>

3. buka termux dan masuk kedalam direktori **storage** -> buat direktori **fundamental** -> masuk kedalam direktori **fundamental** dan didalammnya buat direktori lagi dengan nama nama-kalkulator | contoh: ryo-kalkulator

stepnya seperti ini:

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/7.jpg"> 
</div>
<br>

4. masuk kedalam direktori ryo-kalkulator dan buat file dengan nama main.py

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/linux-basic-command/6.jpg"> 
</div>
<br>

5. edit file main.py dengan command nano dan ketikan didalammnya `print("hello you")`
   > kenapa "hello you" bukan "hello world".? karena "you" is my world ciahhhh awoakowakow

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/12.jpg"> 
</div>
<br>

<br>
<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/13.jpg"> 
</div>
<br>

#### untuk keluar click ctrl+x -> Y -> enter

6. kalau sudah kita akan me push direktori kita ke github

   1. command `git init` | untuk menginisialisasi repositori Git di dalam direktori

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/14.jpg"> 
    </div>
    <br>

   2. command `git remote` | untuk menghubungkan direktori lokal dengan repositori git
      #### kalian bisa copas dari halaman setelah kalian membuat repositori di github tadi

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/20.jpg"> 
    </div>
    <br>

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/21.jpg"> 
    </div>
    <br>

   2. command `git add .` | untuk menambahkan semua perubahan yang ada dalam direktori kerja ke dalam repositori Git

   3. command `git commit` | perintah yang digunakan untuk membuat pesan commit

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/15.jpg"> 
    </div>
    <br>

   4. kalau kalian mendapatkan pesan fatal seperti itu kalian tinggal memasukan apa yang di minta

      `git config --global user.email "emailmu@gmail.com"`
      <br>
      `git config --global user.name "namamau"`

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/17.jpg"> 
    </div>
    <br>

   6. kalau sudah bisa menjalankan command `git commit` ulang

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/18.jpg"> 
    </div>
    <br>

   7. command `git push origin master` | untuk mengirimkan semua perubahan yang telah di commit di direktori lokal ke repositori Git

      #### kalian nanti akan di minta memasukan username github dan password, untuk password masukan token yang di simpan tadi

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/25.jpg"> 
    </div>
    <br>

   8. buka github kembali dan refresh halamannya, kalau sudah terkirim berarti berhasil

    <br>
    <div style="text-align: center;">
    <img src="https://raw.githubusercontent.com/ryyos/databases/master/fundamental-pra/prepare-termux/26.jpg"> 
    </div>
    <br>

#### untuk kedepannya kalian ingin me ngedit file main.py atau apapun yang ada di dalam direktory ryo-kalkulator dan ingin me post nya ke github kalian hanya perlu menjalankan

1. `git add .`
2. `git commit -m ("pesan bebas")`
3. `git push origin master`

#### kalau di minta username dan password kalian bisa memasukannya dengan password di ganti token kalian masing2

## NGODING AJA DULUU.. JAGO MAH BELAKANGAN ;
