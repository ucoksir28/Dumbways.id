
DevOps merupakan prinsip yang menghubungkan antara tim development dan operation agar efektif dan efisien dalam setiap perubahan dimasa mendatang.
Manfaat DevOps
•	Devlivery software berkelanjutan
•	Memudahkan koordinasi antara tim development dan operation
•	Memiliki waktu untuk terus berinovasi 
•	Dapat berjalan secara otomatis dalam system
•	Mengurangi resiko kerusakan aplikasi sebelum di rilis ke public
Alur Kerja DeveOps
-	Plan
-	Code
-	Build
-	Test
-	Release
-	Deploy
-	Operate
-	Monitor
Pada DevOps terdaapat proses Continuous Integration (CI) adalah proses code merging and unit testing, yang akan memeriksa code sebelum di deploy ke server,  sedangkan Continuous Deployment (CD) adalah deployment perubahan code ke server sesuai dengan kebutuhan (Staging / Production).
Tools DevOps yang dapat digunakan untuk CI/CD adalah sebagai berikut :
-	Jenkins
-	GitLab CI
-	GitHub Actions
-	BitBucket Pipeline
 



Keuntungan CI/CD
-	Mendeteksi bug lebih cepat
-	Maintenance code lebih cepat sebelum produksi
-	Otomatis deploy ke server
-	Dapat dikembalikan ke versi sebelumnya jika terjadi kegagalan dengan cepat
Tool CI/CD
-	Jenkins
-	Git
-	Terrafom
-	Nginx
Source Code Management
DevOps perlu mengetahui source code management / version control system seperti git. Dan beberapa platform yang menggunakan git adalah sebagai berikut :
-	GitHub
-	GitLab
-	BitBucket
 
Pada Struktur DevOps kita mengambil contoh pada  Bhinneka.com. Pada Tim CRM ingin  mendapatkan feedback dari kostumer yang telah berbelanja dengan bhinneka.com. Salah saatu fitur yang diinginkan adalah rating dari  konsumen. Pada tahap ini tim development membuat rancang untuk tambahan rating pada bhinneka.com, dimulai dari tombol, posisi, bentuk rating, dan proses pembuatan fiturnya sendiri. 
Ketika proses pembuatan fitur telah selesai, tim development akan memberikan ke tim operasi untuk mengecek apakah ada bug dalam fitur tersebut. Ketika tidak terdapat bug atau error pada fitur rating, selanjutnya akan diteruskan ke public agar dapat di terapkan secara langsung. Apabila terdapat kekurangan, langsung dikembalikan ke tim development untuk di perbaiki.

Dasar Jaringan & Topologi
Jaringan merupakan interkoneksi antara 2 komputer atau lebih, yang saling terhubung dengan media transmisi kabel atau tanpa kabel (wireless). Komputer saling terkoneksi apabila komputer tersebut bisa saling bertukar data / informasi, berbagi resource yang dimiliki seperti file, printer, hard disk, dll.
Pada jaringan terdapat beberapa jenis, diantaranya 
-	PAN (Personal Area Network)
-	LAN (Local Area Network)
-	MAN (Middle Area Network)
-	WAN (Wide Area Network)
Sedangkan jaringan terdapat dua jenis, yaitu :
-	Client Server adalah komputer yang menyediakan fasilitas atau layanan untuk komputer-komputer lain dalam satu jaringan
-	Peer to peer adalah komputer yang saling terhubung dalam satu jaringan yang dapat bertindak sebagai server atau client.
 
Topologi Jaringan rancangan untuk Menyusun sebuah jaringan agar perangkat satu dengan yang lain saling terhubung. Topologi jaringan sendiri terdiri beberapa jenis, diantaranya :
-	Topologi star
-	Topologi ring
-	Topologi bus
-	Topologi tree
IP Address adalah Internet Protocol Address, serangkaian angka unik milik perangkat yang terhubung ke jaringan yang lebih luas. IP Address diperlukan agar perangkat dan server dapat bertukar informasi satu sama lain.
Pada IP Address tedapat dua tipe, yaitu :
-	IP Public adalah Alamat yang di berikan ISP (Internet Service Provider) agar dapat terhubug dengan jaringan yang lebih luas
-	IP Private adalah alamat sebuah perangkat yang akses terbatas hanya pada area tertentu dan tidak terhubung dengan jaringan luar
Didalam jaringan terdapat sebuah referensi atau rujukan yang kita kenal dengan istilah OSI Layer. Osi Layer adalah model referensi yang diciptakan dari sebuah kerangka yang bersifat konseptual. Namun, saat ini telah berkembang dan menjadi sebuah standarisasi khusus berkaitan dengan koneksi komputer.

 
 
Dalam jaringan terdapat sebuah standar atau protokol yang digunakan. TCP adalah Transmission Control Protocol, IP adalah Internet Protocol. Keduanya dijadikan satu karena fungsinya saling bekerja sama dalam komunikasi data.
 

Virtualization adalah teknologi yang memungkinkan kita untuk membagi sebuah resource menjadi lebih kecil dari perangkat yang memiliki resource besar. Secara sederhana kita dapat menjalankan beberapa sistem operasi secara bersamaan.
Virtual Machine adalah sistem komputer yang berjalan di atas sistem lain, memiliki akses ke beberapa sumber daya yang ada di bawahnya. Seperti CPU, Memory dan Storage. Selain itu dapat mengakses USB, Network Card dan sebagainya. 
Untuk membuat virtual machine harus menggunakan hypervisor. Hypervisor adalah program untuk membuat dan menjalankan virtual machine. Contoh aplikasi yang menggunakan hypervisior diantaranya 
-	VmWare
-	Virtualbox
-	KVM
 
Selain virtualisasi dengan hypervisior, Cointainer menjadi salah satu alternatif . Container adalah aplikasi yang mengandalkan isolasi virtual untuk menjalankan aplikasi yang dapat menjalankan sistem operasi kernel secara simultan tanpa memerlukan virtual machine.
Container dapat langsung berjalan diatas induk sistem operasi (OS) tanpa menggunakan hypervisor, sehingga container lebih ringan dibandingkan menggunakan virtual machine.
Contoh aplikasi menggunakan cointainer :
-	Docker
-	Podman
Dengan perkembangan teknologi jaringan virtualisasi maka lahir layanan Bernama Cloud Computing.
Cloud Computing adalah Teknologi yang menjadikan internet sebagai pusat pengolahan data dan aplikasi.
Teknologi cloud computing terbagai 2 tipe, yaitu
-	Public cloud : cloud computing yang dapt diakses oleh siapa saja tanpa Batasan
-	Private cloud : layanan cloud yang hanya di akses oleh user tertentu atau hanya diakses organisasi tertentu.






Dalam Cloud Computing terdapat 3 jenis, yaitu Software As A Service (SaaS), Platform As A Service (PaaS) dan Infrastructure As A Service (IaaS)
 
Keuntungan menggunakan Cloud Computing diantaranya :
-	Akses di mana saja
-	Lebih efisien dan efektif
-	Tidak ada Batasan akses
-	Bayar hanya Ketika dipakai

