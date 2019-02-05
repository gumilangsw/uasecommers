Laravel adalah sebuah framework PHP yang dirilis dibawah lisensi MIT, dibangun dengan konsep MVC (model view controller). Laravel adalah pengembangan website berbasis MVP yang ditulis dalam PHP yang dirancang untuk
meningkatkan kualitas perangkat lunak ,
dengan mengurangi biaya pengembangan awal dan biaya pemeliharaan,dan untuk meningkatkan pengalaman bekerja dengan aplikasi dengan menyediakan sintaks yang ekspresif, jelas dan menghemat waktu.

MVC adalah sebuah pendekatan perangkat lunak yang memisahkan aplikasi logika dari presentasi. MVC memisahkan aplikasi berdasarkan komponen- komponen aplikasi, seperti : manipulasi data, controller, dan user interface.

    Model, Model mewakili struktur data. Biasanya model berisi fungsi-fungsi yang membantu seseorang dalam pengelolaan basis data seperti memasukkan data ke basis data, pembaruan data dan lain-lain.
    View, View adalah bagian yang mengatur tampilan ke pengguna. Bisa dikatakan berupa halaman web.
    Controller, Controller merupakan bagian yang menjembatani model dan view.

Beberapa fitur yang terdapat di Laravel :

    Bundles, yaitu sebuah fitur dengan sistem pengemasan modular dan tersedia beragam di aplikasi.
    Eloquent ORM, merupakan penerapan PHP lanjutan menyediakan metode internal dari pola “active record” yang menagatasi masalah pada hubungan objek database.
    Application Logic, merupakan bagian dari aplikasi, menggunakan controller atau bagian Route.
    Reverse Routing, mendefinisikan relasi atau hubungan antara Link dan Route.
    Restful controllers, memisahkan logika dalam melayani HTTP GET and POST.
    Class Auto Loading, menyediakan loading otomatis untuk class PHP.
    View Composer, adalah kode unit logikal yang dapat dieksekusi ketika view sedang loading.
    IoC Container, memungkin obyek baru dihasilkan dengan pembalikan controller.
    Migration, menyediakan sistem kontrol untuk skema database.
    Unit Testing, banyak tes untuk mendeteksi dan mencegah regresi.
    Automatic Pagination, menyederhanakan tugas dari penerapan halaman.

database yang digunakan
XAMPP  adalah perangkat lunak bebas, yang mendukung banyak sistem operasi, merupakan kompilasi dari beberapa program.

Fungsinya adalah sebagai server yang berdiri sendiri (localhost), yang terdiri atas program Apache HTTP Server, MySQL database,
dan penerjemah bahasa yang ditulis dengan bahasa pemrograman PHP dan Perl. Nama XAMPP merupakan singkatan dari X (empat sistem operasi apapun),
Apache, MySQL, PHP dan Perl. Program ini tersedia dalam GNU General Public License dan bebas, merupakan web server yang mudah digunakan yang dapat melayani tampilan halaman web yang dinamis. 
Untuk mendapatkanya dapat mendownload langsung dari web resminya. 
tutorial laravel 5.7
dalam tutorial tersebut masih ada beberapa langkah yang mungkin hilang atau tidak terdokumentasi. sehingga membuat kita harus mencari penyebab error yang terjadi.

untuk akses webnya :
1. masukan link http://localhost/10916005_uas/10916005/public/
2. ketika sudah masuk ke halaman login masukan username : admin dan password : admin 
3. setelah memasukan username dan password tersebut secara benar maka akan masuk ke halaman utama atau home.

 proses tambah data
1. Untuk menambah data klik pada button "Tambah"
2. Lalu akan menampilkan form untuk mengisi Nama Kelas dan Jurusan. 
3. di form tersebut bisa menambahkan data Nama Kelas dan Jurusan yang sesuai kebutuhan , 
4. kemudian klik button "Simpan" untuk menyimpan ke dalam database
5. Jika salah satu form tersebut tidak diisi maka akan muncul notifikasi terjadinya error, dan harus mengisi data dengan benar dan tepat.

PROSES EDIT DATA

1. Untuk mengedit data yang ingin kita rubah, klik button yang berlambangkan seperti pensil
2. editlah data yang akan diubah
3. Setelah data tersebut benar-benar sudah di ubah dengan tepat, setelah itu klik button "Simpan" agar data yang telah diubah tersimpan

PROSES HAPUS DATA

1. Untuk menghapus data cari data yang ingin di hapus lalu mengklik button yang berlambangkan tempat sampah
2. Maka data secara otomatis akan terhapus, lalu kemudian akan muncul notifikasi bahwa data berhasil dihapus

PROSES UPLOAD

1. Masuk dahulu ke halaman "mahasiswa"
2. Kemudian klik button "Tambah"
3. Maka akan muncul beberapa form yang harus diisi, seperti 
 - NIS 
 - Nama 
 - Jenis Kelamin
 - Alamat
 - No. Telepon
 - Kelas 
 - Foto 
4. Setelah itu klik button "Simpan" agar data yang telah diisi tersimpan di database
5. Jika foto tidak di upload maka akan muncul notifikasi bahwa foto harus di upload dan data tidak akan tersimpan.

