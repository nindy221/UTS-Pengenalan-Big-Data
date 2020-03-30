# UTS-Pengenalan-Big-Data
1.	Cari dan sebutkan 3 DBMS yang bisa digunakan untuk mengelola big data
-	MySQL   
-	ORACLE
-	MICROSOFT SQL SERVER
2.	Carilah contoh masalah big data yang bisa dikelola menggunakan salah satu DBMS tersebut, jelaskan mulai dari instalasi sampai CRUD untuk data menggunakan DBMS tersebut. Asumsikan anda akan memecahkan masalah big data yang sudah anda cari contoh tadi, jelaskan kira-kira bagaimana arsitektur dari solusi big data menggunakan DBMS tersebut, gambarkan diagramnya.
a.	Menggunakan DBMS Mysql
Membuat big data “Data Barang pada sebuah Minimarket”, dalam pengelolaannya maka harus bisa untuk membuat data baru, membaca data yang telah dibuat, mengedit data yang telah dibuat, dan menghapus data yang telah dibuat (menghapus data tersebut karena stock barang telah habis).
1.	Pertama, menginstall XAMPP.  Apabila XAMPP sudah terdownload maka hidupkan “APACHE” dan “MYSQL”.
![](Images/1.png)<br>
2.	Kedua, membuka browser dan mengetik localhost/phpmyadmin. Maka tampilannya seperti dibawah ini :
 
 
3.	Ketiga, membuat database. Klik Basis data, maka tampilannya seperti dibawah ini :
 
4.	Keempat, membuat apa saja yang diperlukan dalam kolom untuk data barang tersebut.
 
 
5.	Kelima, setelah itu klik simpan/kirim untuk membuat tampilan pada kolom
 
6.	Keenam,  membuat nilai pada kolom
 
Klik simpan/kirim, maka tampilannya seperti dibawah ini
 
7.	Membuat koneksi.php agar dapat terhubung denga database
 
 
8.	Membuat index.php
 
 
Maka tampilannya pada browser seperti dibawah ini 
Localhost/uts/index.php
 
9.	
