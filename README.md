# UTS-Pengenalan-Big-Data
1.	Cari dan sebutkan 3 DBMS yang bisa digunakan untuk mengelola big data
-	MySQL   
-	ORACLE
-	MICROSOFT SQL SERVER
2.	Carilah contoh masalah big data yang bisa dikelola menggunakan salah satu DBMS tersebut, jelaskan mulai dari instalasi sampai CRUD untuk data menggunakan DBMS tersebut. Asumsikan anda akan memecahkan masalah big data yang sudah anda cari contoh tadi, jelaskan kira-kira bagaimana arsitektur dari solusi big data menggunakan DBMS tersebut, gambarkan diagramnya.
a.	Menggunakan DBMS Mysql
Membuat big data “Data Barang pada sebuah Minimarket”, dalam pengelolaannya maka harus bisa untuk membuat data baru, membaca data yang telah dibuat, mengedit data yang telah dibuat, dan menghapus data yang telah dibuat (menghapus data tersebut karena stock barang telah habis).
-Pertama, menginstall XAMPP.  Apabila XAMPP sudah terdownload maka hidupkan “APACHE” dan “MYSQL”.
![](Images/1.png)<br>
-Kedua, membuka browser dan mengetik localhost/phpmyadmin. Maka tampilannya seperti dibawah ini :
![](Images/2.png)<br>
-Ketiga, membuat database. Klik Basis data, maka tampilannya seperti dibawah ini :
![](Images/3.png)<br>
-Keempat, membuat apa saja yang diperlukan dalam kolom untuk data barang tersebut.
![](Images/4.png)<br>
-Kelima, setelah itu klik simpan/kirim untuk membuat tampilan pada kolom
![](Images/5.png)<br>
-Keenam,  membuat nilai pada kolom
![](Images/6.png)<br>
Klik simpan/kirim, maka tampilannya seperti dibawah ini
![](Images/7.png)<br>
Membuat koneksi.php agar dapat terhubung denga database
![](Images/8.png)<br>
Apabila koneksi berhasil terhubung maka tampilannya kosong
![](Images/9.png)<br>
-Ketujuh, membuat index.php
![](Images/10.png)<br>
![](Images/11.png)<br>
Maka tampilannya pada browser seperti dibawah ini 
Localhost/uts/index.php
![](Images/12.png)<br>
-Kedelapan, membuat forminput.php
![](Images/13.png)<br>
![](Images/14.png)<br>
Maka tampilannya seperti dibawah ini :
![](Images/15.png)<br>
![](Images/16.png)<br>
Data barang berhasil disimpan
![](Images/17.png)<br>
![](Images/18.png)<br>
![](Images/19.png)<br>
-Kesembilan, membuat form edit.php
![](Images/20.png)<br>
![](Images/21.png)<br>
Apabila diteka edit, maka tampilannya seperti dibawah ini :
Maka tampilannya seperti dibawah ini :
![](Images/22.png)<br>
Berhasil di edit
![](Images/23.png)<br>
![](Images/24.png)<br>
-Kesepuluh, membuat form hapus.php
![](Images/25.png)<br>
setelah ditekan hapus maka tampilannya seperti dibawah ini :
![](Images/26.png)<br>
Tampilan pada PHPMYADMIN
![](Images/27.png)<br>

GAMBARAN ARSITEKTUR
![](Images/28.png)<br>
