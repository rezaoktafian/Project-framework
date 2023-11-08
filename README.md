
<html>
<body>
<div align="right"><h1> Software Requirements Spesification</h1></div>

<p align="right"><b>Version 1.7 </b><br>
<p align="right">30 Oktober 2023</b>
<p align="center">


<p align="right"><b>Data Absensi Smp 25 Pekanbaru <br>
</b>
<p align="right">Kelompok 9 <br>
 Reza Oktafian            (2157301079)<br>
 Pendawa Maulana    (2257301110)<br>
 Ramadhan Pasaribu       (2257301111)<br><br><br>

<p align="right"><b>Jurusan Sistem Informasi</b><br>
<p align="right"><b>Politeknik Negeri Caltex Riau</b>
<p align="right"><b>2023</b>
</p>
</body>
</html>
 

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen   spesifikasi perangkat lunak untuk membangun "Data Absensi Siswa Smp 25 Pekanbaru". Dokumen ini dibangun untuk memudahkan Sekolah Smp 25 Pekanbaru untuk menginput data-data Siswa yang ada di Kelas. Sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Data Absensi Siswa Smp 25 Pekanbaru".

1.2   Lingkup
----------
Data Absensi Siswa Smp 25 Pekanbaru merupakan aplikasi yang kami bangun untuk mempermudah Guru Sekolah Smp 25 Peknabaru dalam melihat perkembangan yang ada di sekolahnya yaitu perkembangan pendidikan, Data Siswa, Alfa, Sakit, Izin. dan memudahkan Guru dalam menginput data-datanya.

1.3    Akronim, singkatan, definisi
----------

| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses aplikasi |
| Software Requirement Specification | perangkat lunak yang akan dibuat dan sebagai penyembatani komunikasi pembuat dengan pengguna |
| Use Case | situasi dimana sistem anda digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian anda |

1.4   Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software  Requirements Specifications. IEEE Computer Society, 1998. 1.5  Overview 
- _SRSExample-webapp.pdf_

1.5   Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang di terapkan pada aplikasi. Menjelaskan gambaran umum dari aplikasi, sistem interface aplikasi dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada aplikasi yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari .Dalam studi kasus ini kami menganalisis kebutuhan suatu sekolah di daerah Pekanbaru tepatnya di Marpoyan Damai .kasus yang kami peroleh pembuatan Data Absensi Siswa. Maka dari itu kami sebagai software engineering merancang sebuah sistem sesuai dengan kebutuhan Sekolah dengan menerapkan Sistem Informasi di sekolah Smp 25 Pekanbaru. Sehingga memudahkan Guru dalam menginputkan data-data Siswa. Software yang kami buat ini berbasis website dimana website sebagai admin, kepala sekolah dan Guru . Sistem yang kami buat di dalamnya terdapat angka kelahiran, angka kematian, pekerjaan, agama, laporan ( untuk admin/guru ), grafik dan laporan ( untuk kepala sekolah ). Berikut akan kami jelaskan  sistem software kami,  admin fungsi utama yaitu :
   - Input Nama Siswa
   - Input Nomor Induk Sekolah Nasional
   - Input Kelas
   - Input Alfa
   - Input Hadir
   - Laporan
   
   Berikut ini fungsi user dalam bentuk grafik :
   - View Kehadiran Siswa
   - View Alfa
   - View Izin
   - View Laporan

2.1   Perspektif produk
----------
Data Absensi Siswa Smp 25 Pekanbaru adalah sebuah sistem Informasi data absensi siswa yang di aplikasiskan pada website. Terdapat 3 jenis yaitu admin, Kepala Sekolah dan Guru. Pengolahan data di kelola oleh admin dan guru pada website dan Kepala Sekolah hanya melihat grafik dan laporan pada website.

Pada sistem informasi data absensi siswa ini akan menampilkan grafik data absensi siswa yang sudah di inputkan oleh admin

**2.1.1 Antarmuka sistem**

![reza](https://github.com/rezaoktafian/Project-framework/assets/149589325/cc72e38c-ae97-4608-aafd-2d221f0facbf)

Sistem aplikasi Data Absensi Siswa Smp 25 Pekanbaru memiliki 3 user yaitu guru, admin dan kepala sekolah. Kepala sekolah mempunyai fungsi yaitu melakukan view grafik dan bisa view laporan. Admin bertugas untuk mengelola data, supaya data bisa di akses oleh kepala sekolah.

**2.1.2 Antarmuka pengguna**

   - **Mockup Admin ( Website )**

|  |  |
|--|--|
| [LOGIN]![Screenshot 2023-11-08 212320](https://github.com/rezaoktafian/Project-framework/assets/149589325/18e13871-a2bf-4402-870f-3f6d51359af6) Pada halaman login admin diminta untuk mengisi username dan password.| 
|[Dashboard]!![Screenshot 2023-11-08 212453](https://github.com/rezaoktafian/Project-framework/assets/149589325/3eba0c62-d78b-487b-92f8-c3a361bcc951) Dashboard|
| [Absensi Siswa]![Screenshot 2023-11-08 212712](https://github.com/rezaoktafian/Project-framework/assets/149589325/79b9620d-dc86-4031-a4b0-0d451eb7dab3)Pada Halaman Absensi dapat menginputkan Data Absensi Siswa|
|.[Data Siswa]![Screenshot 2023-11-08 212843](https://github.com/rezaoktafian/Project-framework/assets/149589325/5ce05d9b-cc3a-416a-b6b8-0a55d274c4e4)
|
|[Laporan]![Screenshot 2023-11-08 213442](https://github.com/rezaoktafian/Project-framework/assets/149589325/1fdf56ec-07c6-43a3-8f1e-e520e39f1d68)
 
**2.1.3 Antarmuka perangkat keras**

![pp](https://github.com/rezaoktafian/Project-framework/assets/149589325/39a99638-5038-47a6-8553-5e4dbc1c8ba3)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Data Absensi Siswa Smp 25 Pekanbaru antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka perangkat lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Data Absensi Siswa Smp 25 Pekanbaru antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. wifi

**2.1.6 Batasan memori**

Tidak ada

**2.1.7 Operasi-operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses aplikasi |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |
| Cetak | Digunakan untuk mencetak laporan |

**2.1.8 Kebutuhan adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan fungsional
----------
![](https://raw.githubusercontent.com/)
   
**2.2.1 Kepala Sekolah Login**

Use Case: Login

Diagram : 
![](https://raw.githubusercontent.com/)

Deskripsi Singkat
Kepala Sekolah melakukan login terlebih dahulu sebelum masuk ke tampilan home, apabila tidak dapat mengakses atau gagal kepala desa dapat meminta kepada admin untuk di dibuatkan akunnya.
Deskripsi langkah-langkah
1. Kepala Sekolah melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Login Kepala Sekolah
   

**2.2.2 Kepala sekolah melihat laporan data siswa**

Use Case: View laporan siswa

Diagram: 
![](https://raw.githubusercontent.com/)

Deskripsi Singkat
Kepala sekolah dapat melihat laporan siswa secara bulanan di data siswa.
Deskripsi Langkah-langkah
1. Kepala sekolah mengklik navbar laporan
2. Kepala sekolah memilih combobox tersebut dan klik tombol cetak laporan
3. Sistem akan menampilkan hasil laporan.

Xref: Bagian 3.2.2, View laporan siswa

**2.2.3 Admin login**

Use Case: Login

Diagram :
![](https://raw.githubusercontent.com/)

Deskripsi Singkat
Admin melakukan login dengan memasukan username password.
Deskripsi Langkah-langkah
1. Admin melakukan login dengan username dan password
2. Sistem melakukan validasi login
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.3, Login admin
      
**2.2.4 Admin input data siswa**

Use Case: Input data siswa

Diagram:
![](https://raw.githubusercontent.com/)
      
Deskripsi Singkat
Admin melakukan input data siswa dan sistem menyimpan data pada database.
Deskripsi Langkah-langkah
1. Admin melakukan input data siswa, Nisn, dan lain-lain.
2. Admin mengklik tombol simpan.
3. Sistem menyimpan data siswa.
4. Bila data sudah ada sistem akan menampilkan peringatan

Xref: Bagian 3.2.4, Input data siswa

**2.2.5 Admin melihat data siswa**

Use Case: View data siswa

Diagram:
![](https://raw.githubusercontent.com/)

Deskripsi Singkat
Admin dapat melihat data kependudukan setelah di inputkan.
Deskripsi Langkah-langkah
1. Sistem akan menampilkan data kependudukan desa Lohbener.
2. Admin melihat data dan dapat mengedit atau menghapusnya.
3. Sistem menampilkan edit data kependudukan
4. Admin  mengedit data kependudukan yang baru atau yang sudah ada
5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan

Xref: Bagian 3.2.5, View data kependudukan
   
**2.2.6 Generate Laporan**

Use Case: Laporan

Diagram:
![](https://raw.githubusercontent.com/)

Deskripsi Singkat
Sistem akan mengirimkan data kependudukan dan yang lainnya ke fungsi laporan
Deskripsi Langkah-langkah
1. Sistem menampilkan laporan kependudukan
2. Admin memilih combobox tersebut dan klik tombol cetak
3. Sistem akan menampilkan hasil laporan.
4. Admin mencetak laporan 

Xref: Bagian 3.2.6, Cetak Laporan

**2.2.7 Admin mengelola user**

Use Case: Mengelola user

Diagram:
![enter image description here](https://raw.githubusercontent.com/)

Deskripsi Singkat
Sistem akan menampilkan form user dan admin dapat menambah user sesuai kebutuhan.
Deskripsi Langkah-langkah
1. Admin mengklik manajemen user, lalu memilih nik dan hak akses user kemudian klik tambah
2. Sistem akan menyimpan data user ke database dan menampilkan data user yang dipilih.
3. Admin bisa menghapus hak akses user.

Xref: Bagian 3.2.7, Mengelola user



2.3   Spesifikasi Kebutuhan non-fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( Admin, sekdes dan kepala desa ) 
 
2.4   Karakteristik pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6   Asumsi-asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7   Kebutuhan Penyeimbang
----------
Tidak ada


BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses aplikasi ini yaitu dengan hak akses yang di berikan oleh admin, login melalui aplikasi ini dengan mencantumkan username kemudian sistem akan mencocokkan username guru dan kepala sekolah smp 25 pekanbaru. Setelah login berhasil kepala sekolah dapat melihat grafik data absensi siswa dan laporan siswa smp 25 pekanbaru di aplikasi tersebut.
      
3.2 Functional Requirement
----------
Logika Struktur terdapat pada bagian 3.3.1
      
**3.2.1 Kepala sekolah Login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.1, Login Kepala sekolah |
| Trigger | Membuka aplikasi Data Absensi Siswa Smp 25 Pekanbaru|
| Precondition | Halaman login |
| Basic Path | 1. Kepala sekolah mengisi form login dengan username dan password <br> 2.Kepala desa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Kepala desa dapat login dan mengakses aplikasi Manajemen Administrasi Data Kependudukan Desa Lohbene |
| Exception Push | Username dan password salah |
      
**3.2.2 Kepala sekolah melihat laporan data siswa**

|  |  |
|--|--|
| Nama Fungsi | View laporan data siswa |
| Xref | Bagian 2.2.2, View laporan data siswa |
| Trigger | Membuka aplikasi Data Absensi Siswa Smp 25 Pekanbaru|
| Precondition | Membuka halaman grafik data siswa |
| Basic Path | 1. Kepala sekolah mengklik navbar laporan <br> 2. Sitem akan menampilkan combobox pilihan bulan dan tahun <br>3. Kepala sekolah memilih combobox tersebut dan klik tombol lihat <br> 4. Sistem akan menampilkan hasil laporan. |
| Alternative | Tidak ada |
| Post Condition | Kepala sekolah melihat laporan data siswa |
| Exception Push | Tidak ada koneksi |
   
**3.2.3 Admin login**

|  |  |
|--|--|
| Nama Fungsi | Login |
| Xref | Bagian 2.2.3, Login admin |
| Trigger | Membuka aplikasi Data Absensi Siswa Smp 25 Pekanbaru |
| Precondition | Halaman login admin |
| Basic Path | 1. Admin melakukan login dengan username dan password <br> 2. Sistem melakukan validasi login <br> 3. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 4. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Admin berhasil login dan mengakses aplikasi Data Absensi Siswa Smp 25 Pekanbaru |
| Exception Push | Username dan password salah |
   
**3.2.4 Admin input data siswa**

|  |  |
|--|--|
| Nama Fungsi | Input data siswa |
| Xref | Bagian 2.2.4, Input data siswa |
| Trigger | Membuka aplikasi Data Absensi Siswa Smp 25 Pekanbaru |
| Precondition | Halaman utama admin |
| Basic Path | 1. Admin melakukan input data Nama Siswa, Nisn, Alfa, Hadir dan lain-lain <br> 2. Admin mengklik tombol simpan <br> 3. Sistem menyimpan data kependudukan <br> 4. Bila data sudah ada sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Halaman form input data absensi siswa |
| Exception Push | Tidak ada koneksi |
   
**3.2.5 Admin melihat data Absensi Siswa**

|  |  |
|--|--|
| Nama Fungsi | View data Absensi Siswa |
| Xref | Bagian 2.2.5, View data Absensi Siswa |
| Trigger | Membuka Data Absensi Siswa Smp 25 Pekanbaru |
| Precondition | Halaman form input data |
| Basic Path | 1. Sistem akan menampilkan data Absensi Siswa Smp 25 Pekanbaru. <br> 2. Admin melihat data dan dapat mengedit atau menghapusnya. <br> 3. Sistem menampilkan edit data absensi siswa  <br>4. Admin  mengedit data absensi yang baru atau yang sudah ada<br>5. Sistem melakukan validasi jika data sudah ada maka muncul peringatan jika belum sistem akan menyimpan|
| Alternative | Tidak ada |
| Post Condition | Halaman data absensi |
| Exception Push | Tidak ada koneksi |
   
**3.2.6 Cetak Laporan**

|  |  |
|--|--|
| Nama Fungsi | Laporan |
| Xref | Bagian 2.2.6, Cetak Laporan |
| Trigger | Membuka Data Absensi Siswa Smp 25 Pekanbaru |
| Precondition | halaman utama admin |
| Basic Path | 1. Admin mengklik tombol laporan <br> 2. Sistem menampilkan laporan kependudukan <br> 3. Admin memilih combobox tersebut dan klik tombol lihat <br>4. Sistem akan menampilkan hasil laporan. <br>5. Admin mencetak laporan  |
| Alternative | Tidak ada |
| Post Condition | Halaman Laporan |
| Exception Push | Tidak ada koneksi, data belum diinput |

**3.2.7  Admin mengelola user**

|  |  |
|--|--|
| Nama Fungsi | Mengelola user |
| Xref | Bagian 2.2.7, Mengelola user |
| Trigger | Membuka Data Absensi Siswa Smp 25 Pekanbaru | 
| Precondition | halaman utama admin |
| Basic Path | 1. Sistem menampilkan form.<br>2. Admin mengisi form user dengan jabatan, tanggal mulai, tanggal berakhir, dll kemudian klik tombol simpan.<br>3. Sistem akan menyimpan data user ke database.  |
| Post Condition | Halaman user |
| Exception Push | Tidak ada koneksi, data belum diinput |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada sistem Aplikasi presensi menggunakan kehadiran terdapat struktur Database yang dijelaskan menggunakan ERD.

![enter image description here](https://raw.githubusercontent.com/jakariaaa27/RPL-D-1/master/Image%20SRS/erd_proyek2.png)

**Tabel User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_user| int | Nomer auto increment Id_user|
| Username | varchar | berisikan Nik untuk akses login user dan username untuk akses admin |
| Password | varchar | berisikan password untuk login admin dan user |
| level | varchar | untuk membedakan level saat login antara admin dan user

**Tabel Siswa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| NISN | varchar | nomer induk siswa negeri |
| Nama | varchar | nomer induk siswa negri|
| jns_kelamin | varchar | Identifikasi jenis kelamin|
| Tgl_lahir | date | tanggal lahir siswa |
| Agama | varchar | Identifikasi agama |

**Tabel Guru**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_guru| int | Nomer auto increment Id_bioadmin|
| Id_user| int | untuk mengambil username dan password admin pada tabel user|
| nik| varchar | nik guru|
| jabatan | varchar | mendefinisikan level user |
| tgl_masuk | date | awal jabatan|
| tgl_keluar | date | akhir jabatan|


**Tabel Laporan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| Id_laporan| int | Nomer auto increment Id_laporan|
| Id_siswa| int | foreignt key tabel siswa |
| laporan | varchar | berisi laporan data absensi |





