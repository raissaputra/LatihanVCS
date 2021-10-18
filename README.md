# LatihanVCS
*Repo ini untuk pembelajaran mengenai cara penggunaan git dan instalasi nya.*

# TUTORIAL PENGGUNAAN GIT DAN GITHUB
## Cara Install Git di Windows
* Download File Git di situs resmi nya :
  * link : https://git-scm.com/downloads
  * pilih sesuai OS kalian, seperti gbr di bawah ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/git-scm.png)
* Buka file unduhan dan lakukan proses instalasi.
* Ikuti intruksi dengan klik NEXT sampai tombol Install, seperti gambar di bawah ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/install-git.png)
* Tunggu Proses Installing sampai selesai, seperti gbr dibawah ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/tunggu-finish-instal.png)
* Setelah selesai install, buka cmd (command prompt) kalian
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/cmd.png) 
* Untuk Cek Versi GIT
  * Ketikan **git --version**, seperti gambar dibawah ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/git--version.png)
* ### Referensi untuk belajar dasar-dasar git dan github :
  * link resmi dokumentasi git : https://git-scm.com/book/id/v2
  * link w3schools : https://www.w3schools.com/git/default.asp?remote=github
* **Berikut adalah ringkasan dasar-dasar perintah Git :**
  * git config --global user.email "you@example.com" => menambahkan identitas user
  * git config --global user.name "YourName" => menambahkan identitas user
  * git init => membuat repository baru
  * git add . => menambahkan semua file ke repository
  * git commit -m "keterangan komit" => melakukan commit
  * git remote add origin "url repo github" => menghubungkan ke server repository
  * git push origin master => mengirim perubahan ke repository (master)
  * git pull => untuk memperbaharui repo lokal agar up to date dengan repo master di github
  * git log => untuk melihat perubahan apa saja yang telah dilakukan
  * git clone "url repo github" => untuk menyalin sebuah repo publik ke repo lokal
  * git status => untuk melihat status repo lokal kita status apa.
  * git branch => untuk membuat cabang baru
  * git merge => untuk menggabungkan branch/cabang ke master 
* LOGIN GITHUB dengan alamat email anda jika sudah punya akun github, seperti di bawah ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/sign-in-github.jpg)
* Jika belum silakan untuk membuat akun github terlebih dahulu dan ikuti instruksinya
* jika berhasil login, maka akan muncul tampilan dashboard berikut :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/dashboard-github.png)
* Buat repository baru dengan klik new repository, seperti gbr di bawah ini :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/new-repo.png)
* Isi nama Repository dengan petunjuk gambar di bawah ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/nama-repo.png)
  * isi kan nama repo yang akan dibuat
  * isi deskripsi repo jika perlu
  * pilih public agar repo anda bisa dilihat oleh orang
* Buat Folder pada komputer anda
* Klik kanan dan pilih Git Bash Here, seperti ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/buat-repo-lokal.png)
* Ubah folder menjadi repository dengan perintah **git init**, seperti gbr ini:
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/git-init.png)
* disini saya buat file TUTORIAL-GIT.txt dan simpan di Repo yang baru saja menjadi master
* ketikan **git status**, untuk melihat status nya :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/add-untrack.png)
  * nama file nya warna merah, maka harus di add, dengan perintah berikut :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/stage.png)
  * lakukan commit pertama dengan perintah di bawah ini :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/first-commit.png) 
* lakukan configurasi nama dan email dengan perintah berikut :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/identitas.png)
* ketikan perintah **git config --list**, untuk melihat configurasi nya :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/config--list.png)
* Untuk hubungkan repo lokal ke server github, lakukan perintah seperti di bawah ini :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/git-push.png)
* Untuk mengirim perubahan ke server github, seperti di bawah ini :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/git-push-final.png)
* Buka akun github, dan refresh untuk melihat hasilnya :
  * ![img](https://github.com/raissaputra/LatihanVCS/blob/main/assets/update-github.png)
