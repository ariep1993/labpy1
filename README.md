# Latihan-VCS
Tugas Bahasa Pemrograman

Buatlah satu repository LatihanVCS

Buat file README.md, lalu isi file tersebut dengan penjelasan (tutorial) cara penggunaan git, dan langkah-langkahnya lengkapi juga dengan screenshot prosesnya.

Nama : saripudin

Nim : 312210077

Kelas : TI.22.B1

# Langkah-Langkah Penggunaan Git
Download Git terlebih dahulu, dengan link berikut ini : ![image](https://user-images.githubusercontent.com/115473865/196014793-e5d768dc-3395-4b11-95d9-505d829e39f3.png)



Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini : ![image](https://user-images.githubusercontent.com/115473865/196014818-f4890763-6893-4981-8305-09be8b89b97e.png)


Setelah proses installasi selesai, silahkan buka software GitBash pada menu di Windows, dan lakukan pengecekan versi, dengan mengetik syntax berikut :

git --version

![2f4b30e1-6ce6-4f11-a1b2-8fc14c4cbf1e](https://user-images.githubusercontent.com/115473865/196014837-7854b32c-efe7-4f5f-9b19-ec4681cc4ee9.jpg)

Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan syntax berikut :
git config --global user.name "Masukkan Nama Anda disini" git config --global user.email "Masukkan Email Anda disini"

![441d8a6b-5f20-4c71-88d5-a12f117b78be](https://user-images.githubusercontent.com/115473865/196015350-abdaedcc-43b8-4676-a5aa-fd1bee0ca525.jpg)

Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut :

git config --global user.name git config --global user.email

![04396d73-ec7e-431b-8b8c-dda9025a6c5b](https://user-images.githubusercontent.com/115473865/196015381-7a27cb43-28eb-4de3-89a0-21cf286f64ac.jpg)

Silahkan Buat akun di GitHub , seperti contoh dibawah ini. Dan lakukan verifikasi akun melalui email yang sudah terdaftar.

![a5c4e3f4-cfa6-4c81-b729-01106b1e4efe](https://user-images.githubusercontent.com/115473865/196015444-9773c2bd-179d-4c9d-ae52-57293cd5ae7e.jpg)

Jika akun GitHub sudah selesai dibuat dan diverifikasi, Proses selanjutnya silahkan buat Repository seperti gamabr dibawah ini. Noted :
Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository Latihan-VCS)
Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)
Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)
Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda
Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.
Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan

![d65a2aa4-4488-42f3-99bf-5a44a2bed4b8](https://user-images.githubusercontent.com/115473865/196016631-37266192-9ee4-477c-8cba-04f6bbabd5c9.jpg)

Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :

![910bafc1-3e11-44d6-9cf6-305a6e7750a8](https://user-images.githubusercontent.com/115473865/196017491-8301d25b-bfc9-4afb-b86f-a1feac68a738.jpg)

Proses pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy.

![871e43a2-a525-48b2-a8ac-178f5f58e39d](https://user-images.githubusercontent.com/115473865/196017594-31f62ffd-a4c2-4ee0-ae6d-cca5bf09dabc.jpg)

Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih Git Bash Here.

![bb5efcfd-881f-481b-9e9f-8fb9a75152b1](https://user-images.githubusercontent.com/115473865/196017664-14d09b2d-85b0-4eec-bc83-e6f8ac4dec12.jpg)

Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut :

![761fd2f9-c7f4-473a-8b9b-443c4f2234a6](https://user-images.githubusercontent.com/115473865/196017725-07439c1b-b329-41da-aa4a-82bf9b720036.jpg)


Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu Latihan-VCS-Garnish dengan mengetikkan syntax berikut :

![1b85b7cf-b69d-417a-884c-4407a12a2862](https://user-images.githubusercontent.com/115473865/196017752-b9cb269e-acaa-4db4-ac0a-bf945351e489.jpg)

Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini :
git add




