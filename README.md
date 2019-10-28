**Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah**  *Applikasi git , akun git*. Sebelum itu saya akan kasih tutorial cara penginstalan **GIT**.
## Cara penginstalan GIT

  - Pertama anda harus mendownload Aplikasi  Git, buka website resminya Git  di **git-scm.com** .
     ![image](https://user-images.githubusercontent.com/56957725/67549327-2bfbf680-f72e-11e9-8cd7-01d077f52e97.png) *Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal*
- Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

  ![image](https://user-images.githubusercontent.com/56957725/67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8.png)

- Setelah melakukan penginstalan, buka git cmd  untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah **git --version.**  Saya memakai versi 2.23.0.windows.1

  ![image](https://user-images.githubusercontent.com/56957725/67550296-4cc54b80-f730-11e9-917c-def7dba03b26.png)
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### _Cara membuat akun git_
- Disini anda harus membuat akun git terlebih dahulu  untuk membuat repository server bukalah link tersebut *http://github.com*

   ![image](https://user-images.githubusercontent.com/56957725/67551828-0245ce00-f734-11e9-807f-7192730b13bd.png)

-  Setelah selesai mengisi user name dan user email anda klik daftar akun GitHub(nanti ada gambar hewan terbalik disitu anda cuma membenarkan posisi gambar tersebut untuk verivikasi), lalu next select a plan dan pilih yang gratisan saja :rofl: :trollface:
![image](https://user-images.githubusercontent.com/56957725/67552204-c9f2bf80-f734-11e9-946e-4fac8ae2324c.png) ![image](https://user-images.githubusercontent.com/56957725/67552228-d37c2780-f734-11e9-9c53-a2ecf3a4c125.png)

- Pada langka selanjutnya pilih sesuai keinginan anda atau boleh langsung diskip saja.
   
    ![image](https://user-images.githubusercontent.com/56957725/67553682-ef34fd00-f737-11e9-8087-f37ad1b4094f.png)


-  Kemudian  anda akan dialihkan Gmail untuk memverifikasi email, klik Verivy email address

    ![image](https://user-images.githubusercontent.com/56957725/67553596-c9a7f380-f737-11e9-8c42-a39fd14d8bf9.png)

  ### _Membuat repositori baru_

- Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori. 

   ![image](https://user-images.githubusercontent.com/56957725/67553515-936a7400-f737-11e9-9ff0-68930e75c056.png)

-  Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.

   ![image](https://user-images.githubusercontent.com/56957725/67555100-ded25180-f73a-11e9-8a67-4632153f5692.png)

### _Membuat Reposiory Local_

- Lalu kita buka file explorer pilih dilocal disk e (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih **Git Bash here** .
![image](https://user-images.githubusercontent.com/56957725/67550770-82b6ff80-f731-11e9-80b2-8634bdb54913.png)

- Lalu kita akan menambahkan Config Global Repository  pakai user name dan user email yang tadi sudah dibuat, dengan perintah : 	
      **$ git config --global user.name “nama_user”**
      **$ git config --global user.email “nama_user”**

   ![image](https://user-images.githubusercontent.com/56957725/67551007-15f03500-f732-11e9-84fe-23d82394ca23.png)
_Nb : Ingat harus melaukukan konfigurasi terlebih dahulu apabila belum nanti akan mengalami kegagalan saat melakukan perintah git   commit. “nama_user” DIGANTI, diganti dengan akun user github anda_

- Buatlah direktori baru dengan menggunakan perintah *" mkdir latihan1"*  LALU *" cd latihan1 "*.

   ![image](https://user-images.githubusercontent.com/56957725/67551270-b6def000-f732-11e9-8e47-22cc1e4f6b27.png)

 ##### _Cara penggunaan git dengan perintah daasar git init fungsi  perintahnya  untuk membuat repository local_ 

- Lalu jalankan perintah *git init* untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.
 
   ![image](https://user-images.githubusercontent.com/56957725/67551431-10471f00-f733-11e9-9332-11282f76d598.png)

-  Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo “#latihan1” >> README.md. Lalu untuk melihat file ketik perintah “ls 

    ![image](https://user-images.githubusercontent.com/56957725/67556667-c31c7a80-f73d-11e9-987a-aed6f3b31328.png)
 ##### _Cara penggunaan git dengan perintah dasar git add  fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit_
- Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah *git add*. Dengan perintah _$ git add README.md_. Kalau ingin melihat infonya ketik perintah _git status_.
  ![image](https://user-images.githubusercontent.com/56957725/67557024-71282480-f73e-11e9-8e9f-0589839218a9.png)

- Untuk menyimpan perubahan yang ada kedalam database gunakan perintah _git commit -m “komentar commit"_
  ![image](https://user-images.githubusercontent.com/56957725/67557721-cadd1e80-f73f-11e9-8f44-dc52f8676eb3.png)
##### **File berhasil tersimpan**

-  Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat.
Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ “git remote add origin [url] “ DAN PERINTAH GIT CLONE “ git clone [ url ] “_
  ![image](https://user-images.githubusercontent.com/56957725/67558013-5fe01780-f740-11e9-8051-0c56eeb82497.png)

 ##### _Cara penggunaan git dengan perintah dasar  git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)_

- Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git
   ![image](https://user-images.githubusercontent.com/56957725/67558206-c2d1ae80-f740-11e9-821b-6116ba38d739.png)

 ##### _Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository_

- Untuk  mengirim perubahan pada local repository ke server gunakan perintah “git push -u origin master”. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub.
   ![image](https://user-images.githubusercontent.com/56957725/67558342-00363c00-f741-11e9-9e86-c2e4875b1e0f.png)

 ##### _Cara penggunaan git dengan perintah dasar  git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever._

- Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/ramdhansy12/Gitlatihan1.git . Jika ingin masuk kedirektorti gunakan perintah “cd [nama direktori anda]”, dan jika ingin melihat semua isi direektori gunakan perintah _“ls -1"_
  ![image](https://user-images.githubusercontent.com/56957725/67558684-a41fe780-f741-11e9-9a45-0e41db446c4c.png)

-  Selesai Jika ingin melihat hasilnya cek di  laman gethub arahkan ke repositorinya
  ![image](https://user-images.githubusercontent.com/56957725/67558476-45f30480-f741-11e9-841b-0a86e67bbf44.png)

#### **FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas**. 
  ![image](https://user-images.githubusercontent.com/56957725/67559345-f6153d00-f742-11e9-911b-ad22c874da88.png)

#### **Selanjutnya klik write, jika sudah selesai klik saja commit change**
![image](https://user-images.githubusercontent.com/56957725/67683036-2b2fc280-f9c3-11e9-98b7-1fa6f5a9c430.png)

##### **NB : Saya meminta maaf  karena pada langkah-langkah pada gambar ada yang berbeda dikarenakan file yang pertama terhapus**
