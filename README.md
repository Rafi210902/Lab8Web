                                                                  LAPORAN PRAKTIKUM 8
                                                                    PEMROGRAMAN WEB
                                                                 PHP DAN DATABASE MYSQL
Nama		: Rafi Hanif R.
NIM		: 312010358
Kelas		: TI.20.A.2
Mata Kuliah	: Pemrograman Web 

PENDAHULUAN
Segala Puji bagi Tuhan Semesta Alam yang telah memberikan kita nikmat seperti Nikmat Iman, Nikmat Islam, serta Nikmat sehat yang telah diberikan-Nya karena atas Rahmat-Nya saya dapat menyusun Laporan Praktikum 8 ini. Dan tak lupa pula kepada Bapak Dosen Pak Agung Nugroho yang telah memberikan Materi dan Instruksi Praktikum agar mahasiswa dapat mengikuti yang diberikan oleh Bapak Dosen. Pada Laporan Praktikum ini saya akan memaparkan cara-cara dalam membuat database tabel barang seperti dibawah ini.
TUJUAN
-	Mahasiswa mampu membuat program CRUD sederhana menggunakan PHP. 
-	Mahasiswa mampu membuat database pada Xampp dengan menggunakan Apache dan MySQL
-	Mahasiswa dapat membuat tabel dengan menggunakan phpmyadmin dan Visual Studio Code

LANDASAN TEORI
Teori ini dilandasi dengan materi PHP dan Database disertai Instruksi Praktikum yang memudahkan Mahasiswa, sehingga Mahasiswa dapat mengikuti Instruksi Praktikum dari Dosen Pengampu agar tidak terjadi kesalahan.

ALAT DAN BAHAN
-	Xampp
-	Visual Studio Code
-	Google Chrome

CARA-CARA 
Berikut merupakan cara-cara yang saya ikuti dalam Instruksi Praktikum 8 yang telah diberikan oleh Dosen Pengampu:

1.	Pertama-tama saya membuka Xampp dan mengaktifkan Apache dan MySQL seperti dibawah ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701104-3e3956e5-abb2-43be-94f3-0ade95eab5f2.png)


2.	Kemudian saya mengetik link http://localhost/phpmyadmin dan saya membuat database baru dengan nama seperti ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701124-8f9df5b3-1fb9-46d4-bcc0-8b8a9c6c03d1.png)


3.	Dan saya membuat tabel pada menu SQL di phpmyadmin seperti ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701141-528f5d90-e83d-4648-8a91-cc649e853f63.png)


4.	Klik Go pada bagian kanan bawah tersebut dan hasilnya akan seperti dibawah ini, lalu klik data_barang.
    ![image](https://user-images.githubusercontent.com/102600434/169701177-1498b9ee-809c-461d-97fa-03982c9f2778.png)
    ![image](https://user-images.githubusercontent.com/102600434/169701187-9d4d0739-d2be-4d59-9cd4-239e7d8e8249.png)

5.	Kemudian klik menu Insert dan tambahkan secara manual seperti dibawah berikut.
 ![image](https://user-images.githubusercontent.com/102600434/169701205-f8f8c9c9-8fae-4c3e-88f3-033050883745.png)

![image](https://user-images.githubusercontent.com/102600434/169701216-ff18219f-8610-4fc0-8482-3817c6abb85c.png)

![image](https://user-images.githubusercontent.com/102600434/169701225-2b641f8c-f619-4863-9169-069675b503b5.png)

 

6.	Lalu klik Go pada bagian kanan bawah tersebut.
![image](https://user-images.githubusercontent.com/102600434/169701241-6e7cad5e-56b8-48f2-bc0a-5d55d2d2fd55.png)
 

7.	Setelah itu data akan bertambah seperti berikut.
 ![image](https://user-images.githubusercontent.com/102600434/169701252-3b8779ec-9ba9-40d4-87b7-a3049db885dd.png)


8.	Tampilan pada tabel di phpmyadmin nya akan seperti ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701262-0fcf3860-cf35-4a89-94a2-aadac8d04b11.png)


MEMBUAT PROGRAM CRUD
9.	Saya membuat folder dengan nama lab8_php_database pada file htdocs di Xampp seperti ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701269-256ea1bf-cd4b-4341-baed-2956eb6e9beb.png)


10.	Lalu saya mengetik link http://localhost/lab8_php_database dan akan muncul seperti ini.
![image](https://user-images.githubusercontent.com/102600434/169701277-10448c9c-7a14-420d-821a-74359088f5a5.png)
 
 
MEMBUAT FILE KONEKSI DATABASE
11.	Saya membuat file baru dengan nama koneksi.php seperti langkah-langkah dibawah ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701282-3d9d42c0-63d2-4589-9d5a-301521212b47.png)

![image](https://user-images.githubusercontent.com/102600434/169701295-bfb19cf5-1d87-4294-b6c0-dcec14605af9.png)

![image](https://user-images.githubusercontent.com/102600434/169701302-6b50de4f-fc1b-4194-bde6-8d2485b8c613.png)

 
 

12.	Untuk menampilkan kata “Koneksi berhasil” saya menghapus kata #else seperti ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701313-4962a894-b412-4def-bd86-3bf9e1a0cc7f.png)


13.	Lalu save pada Visual Studio Code dan refresh pada Browser Google seperti ini.
 ![image](https://user-images.githubusercontent.com/102600434/169701320-fd63938b-798b-4c7d-80f6-499c83f2b85b.png)



MEMBUAT FILE INDEX UNTUK MENAMPILKAN DATA(READ)
14.	Saya membuat file baru dengan nama index.php dengan langkah-langkah berikut.
 ![image](https://user-images.githubusercontent.com/102600434/169701333-ba2fbebb-82ab-446d-8edd-97920a8520bf.png)

![image](https://user-images.githubusercontent.com/102600434/169701360-0fa31bc5-5f74-41ae-84a7-09de7cb1ad82.png)

![image](https://user-images.githubusercontent.com/102600434/169701369-df144a7e-282b-4d88-a767-640985519b60.png)

![image](https://user-images.githubusercontent.com/102600434/169701376-b794c93a-131a-4d5b-9aac-15ba7a45c846.png)


     
                 
15.	Setelah itu save pada Visual Studio Code dan refresh pada Browser Google maka hasilnya akan seperti berikut.
 ![image](https://user-images.githubusercontent.com/102600434/169701394-0e248532-67e4-48bd-bec5-65ea6113cc13.png)


KESIMPULAN
Jadi, pada Praktikum ini saya membuat table data barang pada phpmyadmin dan Visual Studio Code. Mahasiswa jadi mudah mempelajari Materi dan Instruksi ini sekaligus diberikan tugas yang telah diberikan oleh Dosen Pengampu agar bisa membuat tabel dengan menggunakan Xampp dan Visual Studio Code.
