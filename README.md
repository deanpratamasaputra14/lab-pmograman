Hallo nama saya dean pratama saputra. Disini saya akan menjelaskan cara penggunaan Git yang kita perlukan aialah Applikasi git , akun git. Sebelum itu saya akan kasih tutorial cara penginstalan GIT.

Cara penginstalan GIT
Pertama anda harus mendownload Aplikasi Git, buka website resminya Git di git-scm.com .
![195978004-f83ef297-525c-4675-8d1e-61391bcb8a78](https://user-images.githubusercontent.com/116070492/196392279-4d4a23e2-0115-4581-8bcd-7c458a76fe68.png)
 Download lah sesuai dengan bit (32 bit atau 64 bit)laptop anda agar support. Setelah selesai download klik instal

Lalu klik next simpan file lokasi instal di C:\ProgramFiles\Git(sesuai keinginan anda) , lalu di next saja semua sampai ke step install, TUNGGU SAMPAI SELESAI.

![67549597-d8d67380-f72e-11e9-9387-456db6ca1fb8](https://user-images.githubusercontent.com/116070492/196392420-b9cd0b65-6624-4af5-a61a-8e70e9cba9cc.png)


Setelah melakukan penginstalan, buka git cmd untuk mengetahui apakah sudah bisa melakukan proses atau belum jika muncul git version berarti sudah siap melakukan proses. Untuk mengetahui versinya ketikan perintah git --version. Saya memakai versi 2.38.0.windows.1![195978194-04778e47-f0cd-4d03-9ceb-23394a12b588](https://user-images.githubusercontent.com/116070492/196394641-b89a1005-d885-4ca8-bdac-3483afa6355c.png)



Cara membuat akun git
Disini anda harus membuat akun git terlebih dahulu untuk membuat repository server bukalah link tersebut http://github.com
![195978233-065cd98e-8f18-4b11-ab55-3ebec7a60813](https://user-images.githubusercontent.com/116070492/196393777-b08ddf65-1042-438e-bb8c-f612cb437a93.png)


Pada langka selanjutnya anda boleh langsung diskip saja.

Membuat repositori baru
Ini adalah tampilan pertama setelah kalian selesai membuat akun git
![195978469-53789f6c-4d88-4b94-ac44-77d8c05be1f0](https://user-images.githubusercontent.com/116070492/196395441-1bd58257-c026-4c5a-a44b-110d6df90a84.png)


Langkah selanjutnya nanti anda akan dialihkan ke tab baru untuk membuat repositori baru, isi susuai inspirasi anda setelah selesai klik buat repositori.
![195978342-860c1ebf-98a0-470c-8586-272e72bfc79d](https://user-images.githubusercontent.com/116070492/196397578-44585637-8d76-4b6a-9c02-f24821ad2bee.png)





Lalu nanti di tab baru ada url, url ini akan digunakan untuk remote GitHub.
![195978391-435ade62-7139-47d7-b50b-073c6c000bdb](https://user-images.githubusercontent.com/116070492/196398236-2380e79e-4214-4c8e-8e54-e828500ca458.png)


Membuat Repository Local
Lalu kita buka file explorer pilih dilocal disk (c) (atau dmana saja sesuai keinginan anda), lalu klik kanan pilih Git Bash here . Screenshot (20)

Lalu kita akan menambahkan Config Global Repository pakai user name dan user email yang tadi sudah dibuat, dengan perintah : $ git config --global user.email ???email_user??? $ git config --global user.name ???nama_user???

![195978607-35aa8e50-d7fd-4451-b5a6-754d887eb31f](https://user-images.githubusercontent.com/116070492/196398765-d49a2c3a-694e-4142-9699-852b450faa4d.png)


Buatlah direktori baru dengan menggunakan perintah " mkdir lab_pemrograman1 " LALU " cd lab_pemrograman.
![p1](https://user-images.githubusercontent.com/116070492/196401603-91150713-56c5-4296-a2f6-ca32b60a9022.png)


Cara penggunaan git dengan perintah daasar git init fungsi perintahnya untuk membuat repository local
Lalu jalankan perintah git init untuk membuat membuat file kosong berformat GIT. File ini fungsinya untuk menyimpan semua perubahan pada working directory dan file ini terbentuknya hidden.




Lalu buat 1 file baru bernama README.md, dengan memasukan perintah _echo ???#latihan1??? >> README.md. Lalu untuk melihat file ketik perintah ???ls

![p2](https://user-images.githubusercontent.com/116070492/196402444-b22d6185-0451-439a-a317-8c8fdb180814.png)


Cara penggunaan git dengan perintah dasar git add fungsi perintahnya untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit
Untuk menambahkan file yang baru saja dibuat tersebut gunakan perintah git add. Dengan perintah $ git add README.md. Kalau ingin melihat infonya ketik perintah git ![p3](https://user-images.githubusercontent.com/116070492/196403086-335cbbe9-8a2e-4bdf-9dc0-df7a81000943.png)

![p4](https://user-images.githubusercontent.com/116070492/196403553-3a8d5a7b-49c8-416f-ac6f-f847aaf4351a.png)

Untuk menyimpan perubahan yang ada kedalam database gunakan perintah git commit -m ???komentar commit" 

File berhasil tersimpan
Langkah berikutnya kita kembali ke website GitHub untuk melihat repositori yang sudah dibuat. Nah di Quick Setup nanti ada url github kita, url tersebut untuk perintah_ ???git remote add origin [url] ??? DAN PERINTAH GIT CLONE ??? git clone [ url ] ???_
Cara penggunaan git dengan perintah dasar git remote add origin [url], perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
Sudah mengetahui url githubnya lalu ketik perintah git remote add origin [url],urlnya diganti dengan url github anda https://github.com/deanpratamasaputra14/lab-pmograman.git 
![p5](https://user-images.githubusercontent.com/116070492/196405629-2140184a-86d8-4a9e-99e6-39b034eaca85.png)

Cara penggunaan git dengan perintah dasar git push -u origin master, perintah untuk mengirim perubahan pada repository local menuju server repository
Untuk mengirim perubahan pada local repository ke server gunakan perintah ???git push -u origin master???. Ingat pada langkah ini kita harus memasukan usernam dan pasword gethub. git_push
![p6](https://user-images.githubusercontent.com/116070492/196406313-7ff130f0-e933-4063-8184-cd3f907a37ab.png)

Cara penggunaan git dengan perintah dasar git clone [url], perintah untuk membuat working directory yang diambil dari repositry sever.
Kalau ingin melakukan cloning, gunakan perintah git clone [url], urlnya diganti dengan url github anda https://github.com/deanpratamasaputra14/lab-pmograman.git . Jika ingin masuk kedirektorti gunakan perintah ???cd [nama direktori anda]???, dan jika ingin melihat semua isi direektori gunakan perintah ???ls -1" 
![p7](https://user-images.githubusercontent.com/116070492/196406646-a00806a9-1269-4635-8fd6-673eade153dd.png)

Selesai Jika ingin melihat hasilnya cek di laman gethub arahkan ke repositorinya

FILE README.md tersebut masih kosong jikalau anda ingin mengisi kekosongan file tersebut silahkan klik saja icon pensil yang berada di kanan atas.


Terimakasih
