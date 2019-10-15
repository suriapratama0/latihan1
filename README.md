# latihanVCS

## Mengenal Version Control System (VCS) pengertian:
Merupakan Suatu paket software dimana ketika kita meninisialisasi, VCS akan memonitor file kita untuk setiap perubahan dan mengizinkan kita untuk menandai perubahan tersebut pada setiap level perubahan , Sehingga kita dapat meninjau ulang tahapan yang ditandai kapan pun ketika dibutuhkan .

## Tujuan Version Control
Berdasarkan pengertian Version Control di atas, tujuan dari Version Control (Kontrol Versi) adalah memastikan bahwa perubahan konten yang sedang dikembangkan berjalan sesuai rencana. Sementara Version Control (Kontrol Versi) sering dilakukan oleh aplikasi terpisah, itu juga dapat tertanam ke dalam program-program seperti lingkungan pengembangan terintegrasi (IDE), Text Editor, spreadsheet dan, terutama, dokumen dan halaman web kolaboratif. Version Control (Kontrol Versi) memungkinkan server di beberapa lokasi menjalankan versi yang berbeda di situs yang berbeda, walaupun versi tersebut sedang diperbarui secara bersamaan.

## Manfaat Version Control
Mengembangkan perangkat lunak tanpa menggunakan Version Control (Kontrol Versi) berisiko, seperti tidak memiliki cadangan. Version Control (Kontrol Versi) juga dapat memungkinkan pengembang untuk bergerak lebih cepat dan memungkinkan tim perangkat lunak untuk menjaga efisiensi dan ketangkasan saat tim berskala untuk memasukkan lebih banyak pengembang.

## Konfigurasi awal harus di lakukan
Ada beberapa konfigurasi yang harus dupersiapakan sebelum mulai menggunakan Git, seperti name dan email.
##### Silahkan lakukan konfigurasi dengan perintah berikut ini.

## Langkah-langkah menggunakan git
#### lakukan config global repository nama dan alamat email dengan cara:
###### $ git config --global user.name "nama_user"
###### $ git config --global user.email "nama_email"


![Screenshot (10)](https://user-images.githubusercontent.com/56243275/66699309-eee83b00-ed0f-11e9-9777-a3101618b711.png)


####  lalu masuklah ke partisi D: atau selain partisi C: lalu buatlah file baru "lab_pemrograman" masuklah ke file baru tersebut dan buatlah lagi file baru "latihan1" dengan cara:
###### $ cd d:
###### $ mkdir lab_pemrograman
###### $ cd lab_pemrograman
###### $ mkdir latihan1
###### $ cd latihan1


![Screenshot (11)](https://user-images.githubusercontent.com/56243275/66699564-2fe14f00-ed12-11e9-81d1-2fe7331212fc.png)


###### 1. Membuat repository dengan perintah $ git init
###### 2. Membuat file dengan perintah $ echo "#latihan1" >> README.md
###### 3. Mengedit isi file tersebut dengan perintah $ nano README.md
###### 4. Gunakan perintah $ git add setelah melakukan perubahan
###### 5. Jika yakin berikan catatan dengan perintah $ git commit -m "file pertama saya"
###### 6. Membuat sambungan antara repository lokal dengan server git.hub dengan perintah $ git remote add origin (link)
###### 7. Mengirim file ke server atau mengirim perubahan keserver dengan perintah $ git push -u origin master


![Screenshot (12)](https://user-images.githubusercontent.com/56243275/66703089-f112bf80-ed38-11e9-9ed3-2c73e47d1e77.png)

