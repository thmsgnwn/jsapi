

API adalah mekanisme yang memungkinkan dua komponen perangkat lunak untuk saling berkomunikasi menggunakan serangkaian definisi dan protokol. Misalnya, sistem perangkat lunak badan meteorologi, klimatologi, dan geofisika (BMKG) berisi data cuaca harian. Aplikasi cuaca di ponsel Anda “berkomunikasi” dengan sistem ini melalui API dan menampilkan pembaruan cuaca harian di ponsel Anda.
# Apa kepanjangan dari API?

API merupakan kepanjangan dari Application Programming Interface (Antarmuka Pemrograman Aplikasi). Kata Aplikasi pada API merujuk pada perangkat lunak dengan fungsi yang berbeda. Kata Antarmuka dapat diartikan sebagai kontrak layanan antara dua aplikasi. Kontrak ini menjelaskan cara keduanya saling berkomunikasi dengan menggunakan permintaan (request) dan respons (response). Dokumentasi API keduanya berisi informasi cara developer menyusun permintaan dan respons tersebut.
# Bagaimana cara kerja API?

Arsitektur API biasanya dijelaskan dalam kaitannya dengan klien dan server. Aplikasi yang mengirimkan permintaan disebut sebagai klien dan aplikasi yang mengirimkan respons disebut sebagai server. Sehingga untuk contoh cuaca di atas, basis data cuaca BMKG adalah servernya sedangkan aplikasi seluler adalah kliennya. 

Berdasarkan waktu dan alasan pembuatan, terdapat empat cara kerja API.
### API SOAP 

API ini menggunakan Simple Object Access Protocol. Klien dan server saling bertukar pesan menggunakan XML. API yang kurang fleksibel ini populer di masa lalu.
### API RPC

API ini disebut sebagai Panggilan Prosedur Jarak Jauh (Remote Procedure Calls) Klien menjalankan fungsi (atau prosedur) pada server, dan server akan mengirimkan output kembali ke klien.
### API Websocket

API Websocket adalah pengembangan API web modern lain yang menggunakan objek JSON untuk meneruskan data. API WebSocket mendukung komunikasi dua arah antara aplikasi klien dan server. Server dapat mengirimkan pesan callback ke klien yang terhubung, menjadikannya lebih efisien daripada API REST.
API REST

API REST merupakan API yang paling populer dan fleksibel di web saat ini. Klien akan mengirimkan permintaan ke server sebagai data. Server akan menggunakan input klien untuk memulai fungsi internal dan mengembalikan data output ke klien. Lihat API REST selengkapnya di bawah ini.
# Apa itu API REST?

REST merupakan kepanjangan dari Representational State Transfer. REST mendefinisikan fungsi-fungsi seperti GET, PUT, DELETE, dll. yang dapat digunakan klien untuk mengakses data server. Klien dan server saling bertukar data dengan menggunakan HTTP.

Fitur utama API REST adalah sifat stateless-nya. Bersifat stateless berarti server tidak menyimpan data klien di antara permintaan. Permintaan klien ke server mirip dengan URL yang Anda ketik di peramban untuk mengunjungi sebuah situs web. Respons dari server berupa data plain tanpa rendering grafis umum halaman web.
# Apa itu API web?

API Web atau API Layanan Web merupakan sebuah antarmuka pemrosesan aplikasi antara server web dan peramban web. Semua layanan web merupakan API, tetapi tidak semua API merupakan layanan web. API REST merupakan tipe khusus API Web yang menggunakan gaya arsitektur standar seperti yang dijelaskan di atas.

Perbedaan istilah-istilah dalam API, seperti API Java atau API layanan, muncul karena secara historis API telah dibuat sebelum world wide web ada. API web modern adalah API REST dan istilah-istilah tersebut dapat digunakan bergantian.
# Apa itu integrasi API?

Integrasi API adalah komponen perangkat lunak yang secara otomatis memperbarui data antara klien dan server. Beberapa contoh integrasi API terjadi saat sinkronisasi data otomatis ke cloud dari galeri gambar ponsel Anda, atau sinkronisasi waktu dan tanggal secara otomatis di laptop Anda saat Anda berada di zona waktu lain. Korporasi juga dapat menggunakannya untuk mengotomatisasi berbagai fungsi sistem secara efisien.

 

# Apa saja keuntungan REST API?

API REST menawarkan empat keuntungan utama:
- 1. Integrasi 

API digunakan untuk mengintegrasi aplikasi baru dengan sistem perangkat lunak yang sudah ada. Hal ini meningkatkan kecepatan pengembangan, karena masing-masing fungsionalitas tidak harus ditulis dari scratch. Anda dapat menggunakan API untuk memanfaatkan kode yang ada.
- 2. Inovasi 

Dengan datangnya aplikasi baru, seluruh industri dapat mengalami perubahan. Bisnis harus segera merespons dan mendukung deployment cepat layanan inovatif. Bisnis dapat melakukannya dengan membuat perubahan pada tingkat API tanpa harus menulis ulang seluruh kode.
- 3. Ekspansi

API memberikan peluang yang unik bagi bisnis untuk memenuhi kebutuhan kliennya di seluruh platform. Misalnya, API peta memungkinkan integrasi informasi peta melalui situs web, Android, iOS, dll. Bisnis dapat memberikan akses serupa ke basis data internal mereka dengan menggunakan API gratis atau berbayar.
- 4. Kemudahan dalam pemeliharaan

API bertindak sebagai gateway antara dua sistem. Masing-masing sistem wajib melakukan perubahan internal agar API tidak terpengaruh. Dengan cara ini, perubahan kode apa pun di kemudian hari yang dilakukan oleh salah satu pihak tidak akan berdampak pada pihak lainnya.
# Apa saja tipe yang API miliki?

API digolongkan berdasarkan arsitektur dan ruang lingkup penggunaannya. Kita telah mengetahui tipe-tipe utama arsitektur API, jadi mari kita lihat ruang lingkup penggunaannya.
### API Privat

API ini bersifat internal di korporasi dan hanya digunakan untuk menghubungkan sistem serta data dalam bisnis.
### API Publik 

API ini bersifat terbuka bagi publik dan dapat digunakan oleh siapa saja. Ada yang menerapkan otorisasi dan biaya yang terkait dengan jenis API ini, tetapi ada juga yang tidak.
### API Partner 

Hanya dapat diakses oleh developer eksternal resmi untuk membantu kemitraan bisnis ke bisnis.
### API Komposit 

API ini menggabungkan dua atau beberapa API yang berbeda untuk menangani persyaratan atau perilaku sistem yang kompleks. 
Apa itu titik akhir API dan mengapa hal tersebut penting?

Titik akhir API merupakan titik kontak terakhir dalam sistem komunikasi API. Titik akhir API mencakup URL server, layanan, dan lokasi digital spesifik lainnya tempat informasi tersebut dikirim dan diterima antarsistem. Titik akhir API sangat penting bagi korporasi karena dua alasan utama: 
- 1. Keamanan

Titik akhir API membuat sistem menjadi rentan terhadap serangan. Pemantauan API sangat penting untuk mencegah terjadinya penyalahgunaan.
- 2. Performa

Titik akhir API, terutama yang memiliki lalu lintas tinggi, dapat menyebabkan kemacetan (bottleneck) dan memengaruhi performa sistem.
# Bagaimana cara mengamankan API REST?

Seluruh API harus diamankan dengan autentikasi dan pemantauan yang tepat. Dua cara untuk mengamankan API REST meliputi:
- 1. Token autentikasi 

Ini digunakan untuk mengizinkan pengguna melakukan panggilan API. Token autentikasi memeriksa bahwa pengguna adalah pengguna yang sebenarnya dan bahwa mereka memiliki hak akses untuk panggilan API tersebut. Misalnya, saat Anda masuk ke server email, klien email Anda menggunakan token autentikasi untuk mengamankan akses.
- 2. Kunci API 

Kunci API memverifikasi program atau aplikasi yang membuat panggilan API. Kunci-kunci ini mengidentifikasi aplikasi dan memastikan bahwa aplikasi tersebut memiliki hak akses yang diperlukan untuk melakukan panggilan API tertentu. Kunci API tidak seaman token, tetapi kunci API ini memungkinkan pemantauan API untuk mengumpulkan data berdasarkan penggunaan. Anda mungkin pernah memperhatikan string panjang berisi karakter dan angka di URL peramban saat Anda mengunjungi situs web. String ini merupakan kunci API yang digunakan situs web untuk membuat panggilan API internal.
