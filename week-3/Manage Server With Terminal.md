**Manage Server**

Terminal merupakan command prompt dimana kita dapat mengontrol file, membuat folder, membaut akses, atau mengedit sebuah file. 

Bash (Bourne Again Shell) adalah Bahasa yang berjalan pada kernel (linux/unix) yang menjadi penghubung antara pengguna dan operasi system

Teks Editor adalah aplikasi yang berjalan di terminal untuk memanipulasi data pada file.

Untuk menggunakan teks editor pada terminal, kita menggunakan perintah nano. Namun pada umumnya ada dua jenis perintah yang digunakan yaitu nano dan vim. 
Pada dasarnya kedua perintah ini memiliki fungsi yang sama untuk merubah atau memanipulasi sebuah data pada file.

**NANO**

Penggunaan perintah nano cukup dengan membuka terminal atau command prompt dan ketik perintah “nano nama_file”.
Sebagai contoh dibawah ini penggunaan nano pada terminal

![image](https://user-images.githubusercontent.com/96972678/149688018-659c099b-efae-4a6b-803c-cf5447bcd1d2.png)

Setelah tekan enter, akan muncul kotak editor yang digunakan untuk mengolah data. Berikut contoh dari kotak editor nano
![image](https://user-images.githubusercontent.com/96972678/149688026-2f336d02-9a4a-417e-a6d1-9181b72924e6.png)

Didalam kotak editor, kita dapat mengisi data yang dinginkan. Setelah diisi dan dirasa cukup, dapat menyimpan dengan perintah CTRL + X – yes – Enter.
Data tersebut sudah tersimpan dalam file dumbways.

Didalam nano ada beberapa fungsi yang bis akita gunakan, dimulai dari seleksi data, mengganti sebuah kata atau mencari sebuah string. Berikut beberapa fungsi dari command pada editor nano :

•	CTRL + W adalah fungsi untuk mencari sebuah kata pada sebuah file saat editor nano aktif. Berikut contoh dari hasil CTRL + W 
![image](https://user-images.githubusercontent.com/96972678/149688070-9ba6db9b-d63b-4c87-b55a-22736c7b518f.png)

•	ALT + A adalah fungsi untuk seleksi sebuah kata pada terminal nano editor. Dengan ini kita dapat melakukan seleksi sebuah kata kalimat tanpa harus menggunakan kursor mouse.

![image](https://user-images.githubusercontent.com/96972678/149688080-9d02a3dd-c3c6-4e51-9236-d57c26768ce9.png)

•	CTRL + K berfungsi melakukan cut pada kata atau kalimat yang di pilih
![image](https://user-images.githubusercontent.com/96972678/149688096-f4605040-a6d1-4412-b5f9-54ad0fcda19b.png)

•	CTRL + U berfungsi untuk melakukan paster pada kata atau kalimat yang dipilih
![image](https://user-images.githubusercontent.com/96972678/149688104-13c72aa6-b0bb-4e24-a862-167583049649.png)

•	CTRL + A berfungsi untuk memindahkan kursor teks editor nano ke bagian awal teks. Posisi kursor yang berwarna hijau pindah dari akhir kalimat menuju awal kalimat.

![image](https://user-images.githubusercontent.com/96972678/149688111-a70ba138-9410-4e0f-900c-f0a35a132943.png)
![image](https://user-images.githubusercontent.com/96972678/149688116-03149839-0d90-401e-8d04-7c3586ec14db.png)

•	CTRL + E fungsi ini kebalikan dari CTRL + A yaitu memindahkan kursor ke akhir kata atau kalimat.
![image](https://user-images.githubusercontent.com/96972678/149688128-05c6d496-4967-409a-9d56-f84287129f01.png)

**TEXT MANIPULATION**

Text Manipulation atau melakukan perubahan data menggunakan tipe teks pada command prompt linux atau terminal. Disini terdapat beberapa perintah yang digunakan untuk melihat, menyisipkan atau menghapus data pada sebuah file seperti menggunakan nano.

•	Perintah pertama adalah cat. Perintah ini berfungsi untuk melihat isi dari sebuah file tanpa harus masuk ke editor teks. Selain itu, dapat menambahkan dan mengganti seluruh isi data file sesuai yang kita inginkan.
![image](https://user-images.githubusercontent.com/96972678/149688153-781cd291-b9f5-4309-beff-e2c28e1a454c.png)

Perintah dibawah ini kita menggunakan cat untuk membuat sebuah file kemudian mengisi file tersebut dengan kalimat “Saya adalah jagoan”

![image](https://user-images.githubusercontent.com/96972678/149688156-d188ffcf-9605-4a9a-8c46-1d0884f8d914.png)

Perintah berikutnya masih menggunakan cat namun menggabungkan dua file kedalam satu file Bernama devops .

![image](https://user-images.githubusercontent.com/96972678/149688163-8a7593be-16d5-4183-bac8-5ad72a2cb82a.png)

Tadi sudah menggabungkan dua file menjadi satu, sekarang kita akan mengubah kata pada sebuah file dengan menggunakan perintah sed. Perintah sed digunakan untuk mengubah kata saya menjadi aku pada file devops. Dengan kita tidak perlu lagi mengubah satu persatu satu.

![image](https://user-images.githubusercontent.com/96972678/149688174-4f99efe5-8ffa-423a-b59f-19c1168e8b32.png)

•	Perintah kedua adalah meggunakan grep. Perintah ini memiliki fungsi untuk mencari sebuah kata pada sebuah file. Tidak itu saja, grep juga bisa menghitung jumlah kata tertentu pada sebuah file.

![image](https://user-images.githubusercontent.com/96972678/149688182-d0e6c86e-72f6-4fe1-8eb9-bb2dce4be935.png)

Gambar diatas menggunakan perintah grep untuk mencari kata “aku” pada file devops. Berikutnya kita menggunakan perintah grep dan menghitung berapa banyak kata “aku”

![image](https://user-images.githubusercontent.com/96972678/149688188-7deb0262-8568-4e56-90e2-4d181f30ecd3.png)
Hasil dari perintah grep -c adalah sebanyak 2. Ini mengartikan kalau kata “aku” pada devops berjumlah 2 kata.

•	Sort merupakan perintah untuk mengurutkan sebuah data dari kecil ke besar atau sebaliknya. 

![image](https://user-images.githubusercontent.com/96972678/149688253-7a90695a-5f6b-46b7-8ba2-e2e2cb89c0cc.png)

Untuk mengurutkan dari besar ke kecil, kita hanya perlu menambahkan parameter pada perintah sort yaitu -r

![image](https://user-images.githubusercontent.com/96972678/149688269-2c287792-e655-4db7-999a-b4775ae298a9.png)

•	Echo adalah perintah untuk menambahkan sebuah kata atau kalimat ke dalam sebuah file tanpa harus masuk ke teks editor.

![image](https://user-images.githubusercontent.com/96972678/149688281-4da5a677-cefa-4fc7-9f03-0d9b128a83b2.png)

Pada gambar diatas, kita menggunakan tanda “>>” untuk menambahkan kalimat atau kata pada file devops. 

![image](https://user-images.githubusercontent.com/96972678/149688294-d7d7b6bd-f445-419d-bc09-fed0fe69cc25.png)

Berbeda pada perintah sebelumnya, kali ini kita menggunakan perintah echo dan tanda “>” hanya satu. Ini berfungsi untuk menganti semua isi dari file dengan “saya adalah wonderman”. Terbukti setelah kita cek dengan perintah cat, seluruh isi file yang pertama sudah hilang dan berganti dengan yang baru.


**Monitoring**

Monitoring adalah aktifitas memantau performa dari sebuah system yang langsung. Beberapa aplikasi yang digunakan untuk memonitor pada linux adalah
1.	HTOP
2.	ISOF
3.	Ps


**HTOP**

Aplikasi HTOP secara default sudah terinstall pada ubuntu server 20.04. Namun jika belum memiliki dapat melakukan instalasi aplikasi dengan perintah “sudo apt install htop -y”

![image](https://user-images.githubusercontent.com/96972678/149688585-f0c937d2-29b3-4f40-8e66-7b062750670e.png)

Pada gambar diatas merupakan tampilan pada HTOP di ubuntu server. Untuk menjalankannya cukup ketik htop pada terminal dan enter. Berikut beberapa bagian HTOP yang memberikan informasi performa dari sebuah system operasi :

•	Mem adalah memory yang menunjukkan performa dari penggunakan memori pada server. Dapat kita lihat berwarna hijau merupakan jumlah memory yang sudah di gunakan dan kuning adalah sisanya.

•	Swap adalah memori cadangan yang digunakan apabila memori utama habis.

•	PID adalah Proceses ID setiap layanan yang berjalan pada linux.

•	USER adalah pengguna yang sedang aktif menjalan sebuah layanan atau aplikasi

•	CPU% menunjukkan ujumlah penggunaan cpu pada layanan yang berjalan dalam satuan persen

•	TIME adalah waktu yang sudah berjalan pada aplikasi. Dapat kita lihat aplikasi tertentu sudah berjalan berapa lama

•	Command adalah perintah yang berjalan pada layanan di linux. Seperti gambar diatas terdapat perintah mysqld yang menandakan layanan database sedang berjalan.


