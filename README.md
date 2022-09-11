# Writing-and-Presentation-1
(Unix Command Lind, Git and Github, HTML, CSS dan Algoritma &amp;Pseudocode)
 

pada pertemuan minggu pertama ini peserta BOOTCAMP mendapatkan 5 materi pembelajaran, sebagai berikut:

- Unix Comman Lind
- Git and Github
- HTML
- CSS
- Algoritma dan Pseudocode

## 1. Unix Command Lind

materi unix comman lind berkaitan dengan terminal. Terminal merupakan tools wajib yang harus dikuasai oleh pragramer. hal ini berkaitan dengan deployment ketika membuat sebuah aplikasi agar terlihat lebih hidup. Terminal Basic merupakan proses menampilkan file/folder dengan pengetikkan di Command Prompt atau Windows Powershell. Terdapat beberapa perintah atau navigation pada terminal basic yang digunakan oleh programer, sebagai berikut:
  - perintah ls untuk menampilkan list folder/file
  - perintah ls-la untuk menampilkan folder yang disembuyikan
  - perintah cd untuk memindahkan folder ke dokumen yang diinginkan
  - perintah cd+.. untuk kembali ke folder sebelumnya
  - perintah ni nama_file.extensi untuk membuat file baru didalam folder
  - perintah clear untuk membersihkan tampilan terminal
  - perintah cp untuk mengkopi atau menggandakan file/folder
  - perintah rm untuk meremove atau menghapus file/folder
  - perintah mkdir untuk membuat folder baru
  
  
## 2.  Git and Github  
       Git merupakan tools yang dapat melacak perubahan yang terjadi pada suatu file atau folder. git bersifat sebagai version control system dikarenakan   mempunyai kemampuan untuk mencatat setiap perubahan yang terjadi pada suatu file projek yang telah dibuat.
       
       Github adalah salah satu vendor atau penyedia git.
       
 
 GIT dan Github dapat memudahkan programer untuk bekerja sama dalam sebuat tim. manfaat menggunakan git dan github sebagai berikut:
- mampu berkolaborasi mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate.
- bisa bekerja secara bersamaan tanpa harus menunggu rekan dalam satu tim menyelesaikan suatu program.
- bisa membuat file didalam projek yang sama atau membuat code di file yang sama dan menyatukannya saat sudah selesai.
- sebagai tempat menyimpan file projek yang lebih efektiv tanpa harus membuat berbagai macam duplikat file.
- file-file yang disimpan menggunakan git akan terdeteksi setiap perubahannya dan siapa orang yang telah mengubah file tersebut.

  #### a. Install Git, Github dan VSCode

Berikut link Download
- git http://git-scm.com/download/win2. Pilih -> 64-bit for Windows Setup3
- Github desktop https://desktop.github.com/4
- Visual Studio Code https://code.visualstudio.com/

cara mengecek versi git di terminal
- git --version cara mengecek setup awal git di terminal
- git config --global user.name "nama_terdaftar"
- git config --global user.email "email_terdaftar"
- git config --list (untuk mengecek setup berhasil). jika pendaftaran berhasil maka nama dan email yang terdaftar akan muncul di terminal. Note: nama dan email harus sama dengan yang di setup pada github.

  #### b. Membuat repository Git

Repository adalah sebuah file/folder/directory proyek yang dibuat oleh programer. Cara membuat repository github sebagai berikut:
- masuk ke akun github
- klik Repositories
- klik New

![image](https://user-images.githubusercontent.com/109327181/189514952-f23418f2-496b-49e4-9e49-65c404b44484.png)  
- isi username lalu create repository

berikut beberapa perintah git yang dapat digunakan oleh programer:
- git init => inisialisasi untuk membuat repository lokal di dalam folder
- git remote add origin "link repository github yang telah dibuat => mendaftarkan repository yang telah dibuat di github
- git status => untuk melihat perubahan git baik yang ditambahkan atau di commit
- git add => untuk menambahkan 1 file
- git add . => untuk menambahkan lebih dari 1 file
- git commit => untuk menyimpan perubahan pada version control
- git push -u origin master => untuk mengirimkan proyek ke version control
- git log => untuk mengetahui siapa pembuat dan waktu pembuatan/edit directory
- git branch => untuk mengecek cabang

## 3.  HTML
#### Pengenalan HTML
HTML (Hyper Text Markup Language) digunakan untuk membuat kerangka atau struktur dari halaman website di internet. HTML bertujuan untuk menampilkan konten pada browser seperti text, image, video, link dll. HTML sama seperti microsoft word bersifat statis. HTML bukan lah sebuah bahasa pemrograman. 

#### Tools HTML
- Web browser
- code editor (code editor yang sering digunakan oleh depelover adalah visual studio code)

#### Dasar-dasar HTML
untuk menjalankan HTML dengan baik dibutuhkan HTML struktur. struktur dasar HTML sebagai berikut:

![image](https://user-images.githubusercontent.com/109327181/189515649-0776f91c-d937-423b-9277-585af2135ebb.png)

ket:
1. Tag Doctype adalah tag yang menyatakan bahwa kode dibawah adalah dokumen html. Berfungsi untuk memberitahu akan dokumen yang akan dijalankan pada browser.

2. Tag html adalah tag pembuka dan penutup dari keseluruhan sebuah dokumen html

3. Tag head umumnya berisi elemen yang tidak tampak pada browser, seperti memanggil css, membuat judul website, dan lain-lain. intinya di dalam tag head tidak akan tampil di browser.

4. Tag body sebaliknya, berisi elemen yang akan tampak pada browser. Seperti paragraf, memasukkan gambar, dan lain-lain.

### HTML Anatomy
Komponen atau anatomy HTML terdiri dari opening tag, closing tag, dan konten. Keseluruhan dari opening tag, closing tag dan konten dinamakan HTML Element. Contoh dibawah ini:

![image](https://user-images.githubusercontent.com/109327181/189515774-50dd1291-1423-4703-87ac-f2fbd0db1005.png)

### HTML Atribut
adalah informasi tambahan kepada sebuah element. beberapa atribut, seperti id, title, class, style, dan lain lain. Contoh pengguanaan sebagai berikut:

![image](https://user-images.githubusercontent.com/109327181/189516488-0842fcf1-10e4-4c71-86bc-10b48773e0e4.png)

### membaca dokumentasi
Untuk melihat seluruh element yang disediakan oleh HTML, kita bisa cek dokumentasi yang disediakan.

Cek dokumentasi :
Resource by Mozilla https://developer.mozilla.org/en-US/docs/Web/HTML/Element#:~:text=The%20HTML%20element%20contains,or%20part%20of%20a%20document.&text=The%20HTML%20Title%20element%20(%20%3Ctitle,bar%20or%20a%20page's%20tab.
Documentation by W3schools https://www.w3schools.com/tags/default.asp

### Deploy HTML
Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang. 
1. Gunakan tools bernama netlify
2. Masuk ke netlify.com
3. Register menggunakan akun github jika telah memiliki akun github
4. masuk ke tab sites lalu drop and drug file yang akan di deploy

## 4. CSS



** Copywright By Khairunnisah - 2022**
