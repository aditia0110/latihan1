#latihanVCS1: pengguna GIT

TUTORIAL CARA PENGGUNAAN GIT

NAMA  : ADITIA SEFTIAWAN

NIM   : 312210094

KELAS : TI.22.B1

Berikut ini adalah langkah-langkah dalam membuat GIT dan github:

1. Download aplikasi GIT di "https://git-scm.com". kemudian instal
2. Masuk ke GIT Bash lalu lakukan konvigurasi dengan memasukan username dan email


    `$ git config --global user.name "user_aditia"`
    
    
    `$ git config --global user.email "aditia01101999@gmail.com"`
    
<img width="451" alt="2022-10-15" src="https://user-images.githubusercontent.com/115475348/195967978-c474b4c4-a573-4b56-b633-15c71fecd9fe.png">

3. Buat direktori dengan perintah "mkdir" dan gunakan perintah "cd" untuk masuk ke direktorinya, lalu perintah "git init" membuat repository lokal. 

    `$ mkdir latihanVCS1`
    
    
    `$ cd latihanVCS1`
    
    `$ git init`

<img width="960" alt="2022-10-15 (2)" src="https://user-images.githubusercontent.com/115475348/195968133-88637026-0b12-4473-b3b4-882be10df886.png">

4. Buat file README.md menggunakan perintah "echo" atau bisa menggunakan perintah "git add(namefile)"

    `$ echo "#latihanVCS1: pengguna GIT" >>  README.md`

<img width="960" alt="2022-10-15 (3)" src="https://user-images.githubusercontent.com/115475348/195968213-55d4fec4-fc32-4810-b2a6-5bc5a8852d80.png">

5. Dan seperti inilah tampilan file jika file berhasil dibuat.

<img width="960" alt="2022-10-15 (4)" src="https://user-images.githubusercontent.com/115475348/195968275-a92e7c71-27e5-4d1c-a289-b20ef2c6fda0.png">

6. Cek filenya menggunakan "git status" dan Gunakan perintah "git commit -m(komentar commit)" untuk menyimpan perubahan kedalam repository lokal.

    `$ git status`
    
    `$ git commit -m "File README.md"`
    

<img width="960" alt="2022-10-15 (5)" src="https://user-images.githubusercontent.com/115475348/195968455-64b58496-626f-4a15-976d-2ce9f43d066a.png">

7. Buatlah akun Github. Kemudian buat repository baru dengan mengisi nama repository di "Start a new repository" atau klik ikon (+) lalu pilih new repository.

<img width="960" alt="2022-10-17" src="https://user-images.githubusercontent.com/115475348/196097639-4f3b4437-e48a-45a5-bcf1-79abe0367527.png">


8. Lalu kembali ke Git Bash, lalu ketik perintah "git remmote add origin(URL) untuk menambahkan remmote repository, yang akan di gunakan untuk menyimpan setiap perubahan pada lokal repository agar bisa diakses oleh user lain.

    `$ git remote add origin https://github.com/aditia0110/latihanVCS1.git`
    
    `$ git push -u origin master`

<img width="960" alt="2022-10-15 (7)" src="https://user-images.githubusercontent.com/115475348/195968976-1772c519-2b7b-4d6d-b74b-a1e08149e447.png">

9. Lalu liat hasil pada server repository tersebut

<img width="960" alt="2022-10-15 (8)" src="https://user-images.githubusercontent.com/115475348/195968775-f9422e53-f025-48d1-ba5b-ff07c97d2f8f.png">

10. Untuk menyalakan repository server gunakan perintah "git clone (URL)"

    `$ git clone https://github.com/aditia0110/latihanVCS1.git`

<img width="960" alt="2022-10-15 (9 2)" src="https://user-images.githubusercontent.com/115475348/195968958-e7bee41a-c294-410b-aea4-dc1404c90f24.png">

Seperti itulah langkah-langkah dalam mambuat GIT dan github, mohon maaf bila ada kesalahan. 


Terima Kasih
