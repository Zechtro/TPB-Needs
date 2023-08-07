# TPB-Needs

## Table of Contents

1. Deskripsi Masalah dan Solusi
2. Program Requirement
3. Cara Penggunaan Program
4. Identitas Pembuat dan Kontribusi

## 1. Deskripsi Masalah dan Solusi
Masalah yang diangkat oleh kelompok kami adalah terkait dengan terlalu tersebarnya informasi dalam jumlah yang banyak terkait dengan kebutuhan perkuliahan, khususnya buku, di masa TPB untuk para mahasiswa baru. Hal ini menyebabkan beberapa permasalahan, seperti hilangnya waktu, kurangnya rasa kenyamanan dan keamanan, serta pembelian untuk kebutuhan yang kurang tepat. 

Dengan demikian, kelompok kami mencoba menawarkan sebuah solusi berupa platform tersentralisasi informasi komunitas, transaksi jual beli, dan donasi untuk kebutuhan perkuliahan di masa TPB. Sebagai tahap awal, solusi sementara dibangun dalam bentuk website statik.

## 2. Program Requirement

### User Requirement
Berdasarkan hasil design thinking yang sudah dilakukan sebelumnya, target pasar kami sementara terbatas pada mahasiswa ITB, terlebih mahasiswa baru yang akan menjalani masa TPB. Ditemukan pula melalui hasil kuesioner mahasiswa ITB bahwa sebanyak 82,4% dari 34 responden merasa membutuhkan program yang dapat membantu mereka untuk mempermudah pencarian, pembelian, penjualan, dan pendonoran kebutuhan perkuliahan.

### Feature Requirement
Terdapat tiga fitur utama dan mendasar yang kami kembangkan untuk program TPB-Needs, yakni: media informasi komunitas, pencarian/pembelian kebutuhan perkuliahan dengan fokus untuk produk buku, serta penjualan sebagai pusat informasi listing penjual produk. Dengan ini, kelompok merumuskan dan membuat dengan total lima web page, antara lain: welcoming page, product page, search result page, sign up page, dan sign in page.

Untuk welcoming page, terdapat informasi berupa toko terbaik dan rekomendasi buku. Selain itu, kita bisa mengetik di kolom search bar untuk mencari keperluan yang dibutuhkan. Di samping itu, ada menu bar yang secara konsisten menampilkan tombol untuk berpindah ke page lain, yaitu: beranda, komunitas, kategori, dan daftar sebagai penjual, keranjang pembelian, notifikasi, informasi kontak, sign in, dan log in. Masing-masing tombol tersebut akan membawa user ke page yang berkaitan, terkecuali untuk tombol komunitas, kategori, daftar sebagai penjual, keranjang pembelian, notifikasi, dan informasi kontak, yang belum dapat diselesaikan karena adanya keterbatasan waktu dan sumber daya manusia. 

Untuk product page, terdapat informasi berupa kebutuhan TPB yang dipilih oleh user. Saat ini, kami baru hanya menampilkan informasi untuk buku Kalkulus Purcell, karena keterbatasan waktu yang tidak memungkinkan untuk kami membuat product page untuk setiap item yang saat ini sudah tersebar di kalangan mahasiswa ITB. Pada page ini, terdapat informasi berupa judul buku, informasi buku, harga, penambahan produk ke dalam keranjang, dan opsi untuk membuat produk sebagai favorit user. Dengan dua fitur terakhir belum mampu kami kembangkan secara lebih lanjut.

Untuk search result page, terdapat informasi berupa produk-produk yang dicari berdasarkan kebutuhan user pada kolom search bar. Kami menyediakan fitur tambahan berupa filter supaya produk dapat lebih terkurasi sesuai dengan keadaan dan keinginan user. Pada page ini pula, terdapat beberapa pilihan produk dengan masing-masing memiliki informasi berupa judul, keterangan singkat, dan harga, yang secara ide dapat membawa kami ke product page. Namun, seperti sebelumnya, kami belum mampu untuk membuat banyak product page.

Untuk sign up dan sign in memiliki tampilan dan fungsionalitas yang kurang lebih sama, meski dengan tujuan yang berbeda. Kedua page ini akan meminta user untuk memasukkan username dan password untuk masuk ke page utama dan mengakses seluruh fitur yang ada, baik sebagai pengguna yang sudah pernah daftar atau pengguna baru. Akan tetapi, sampai dengan saat ini, user hanya bisa mengetik saja informasi terkait tanpa secara konkret data tersebut tersimpan dalam database sistem, karena adanya keterbatasan waktu dan sumber daya. 

Terkait dengan tampilan, fungsionalitas, dan sebagainya, hyperlink page akan dicantumkan dalam bab 3 terkait dengan panduan penggunaan program.

## 3. Cara Penggunaan Program
Guide untuk masing-masing page:

### Welcoming Page (index.html)
Page awal yang akan menavigasi user ke berbagai fitur atau bisa dikatakan main pagenya
<br>https://zechtro.github.io/TPB-Needs/</br>

### Product Page (product.html)
Berisikan informasi produk yang di klik oleh user
<br>https://zechtro.github.io/TPB-Needs/product.html</br>

### Search Result Page (search.html)
Berisikan informasi produk yang sesuai dengan kata kunci pencarian yang dimasukkan user
<br>https://zechtro.github.io/TPB-Needs/search.html</br>

### Sign Up Page (login/index.html)
Halaman untuk membuat akun bagi user yang belum memiliki akun. Pada halaman ini, user perlu memasukkan username dan password baru. 
<br>https://zechtro.github.io/TPB-Needs/login/index.html</br>

### Sign In Page (login/register.html)
Halaman untuk masuk ke akun bagi user yang sudah memiliki akun. Pada halaman ini, user perlu memasukkan username dan password akun mereka.
<br>https://zechtro.github.io/TPB-Needs/login/register.html</br>

*Catatan: Karena keterbatasan Github Pages, halaman masih berbentuk static dan belum bisa dikembangkan menjadi dynamic* 

## 4. Identitas Pembuat dan Kontribusi
Berikut identitas pembuat milestone dan kontribusinya:
<br>NIM      - Nama                         - Kontribusi</br>
<br>19622249 - Justin Aditya Putra Prabakti - Product page dan Search page</br>
<br>19622221 - Steven Tjhia                 - Home Page (Header, Navbar, Toko)</br>
<br>19622166 - Muhammad Neo Cicero Koda     - Login dan Register page</br>
<br>19622165 - Farhan Nafis Rayhan          - Backend dan Database</br>
<br>19622014 - Jonathan Wiguna              - Data Toko dan Produk</br>
<br>19622240 - Gracya Tio Damena Sidabutar  - Data Toko dan Produk, Penjelasan Cara Penggunaan Program</br>
<br>19622250 - Jonathan Emmanuel Saragih    - Data produk dan Pencarian Inspirasi</br>
<br>19622107 - Richie Leonardo              - Pembuatan dan Penyuntingan file README</br>
<br>19622220 - Kezia Caren Cahyadi          - Data Toko dan Produk</br>
<br>19622109 - Willhemlmina Rachel Silalahi - Pembuatan dan Penyuntingan file doc</br>
<br>19622125 - Arvyno Pranata Limahardja    - Pembuatan dan Penyuntingan file README</br>
<br>19622178 - Muhammad Syarafi Akmal       - Register Page</br>
