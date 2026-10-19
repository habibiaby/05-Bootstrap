1. Pengertian Bootstrap
Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar lebih menarik, konsisten, dan responsif. Bootstrap menyediakan berbagai class, komponen, dan utility siap pakai, seperti navbar, tombol, form, card, serta sistem grid. Dengan Bootstrap, pengembang tidak perlu menulis seluruh kode CSS dari awal sehingga proses pembuatan antarmuka website menjadi lebih cepat dan mudah.
2. Memasang Bootstrap
Terdapat beberapa cara untuk menggunakan Bootstrap pada proyek website, yaitu:
1. Menggunakan CDN (Content Delivery Network), yaitu menghubungkan file CSS dan JavaScript Bootstrap melalui URL yang disediakan. Cara ini praktis karena tidak perlu mengunduh file Bootstrap secara manual.
2. Mengunduh file Bootstrap, yaitu mengunduh file CSS dan JavaScript dari situs resmi Bootstrap, kemudian memasukkannya ke dalam folder proyek.
3. Menggunakan package manager, seperti npm, untuk memasang Bootstrap sebagai dependensi proyek. Cara ini biasanya digunakan dalam pengembangan website yang memiliki pengelolaan dependensi.
4. Menggunakan framework atau build tool, seperti Vite, untuk mengintegrasikan Bootstrap ke dalam proyek dan mengelola aset website.
Pada tugas ini, Bootstrap digunakan melalui CDN sehingga file HTML dapat langsung menggunakan class Bootstrap dengan koneksi internet.
3. Grid dan Breakpoint
Grid adalah sistem tata letak Bootstrap yang digunakan untuk mengatur posisi dan lebar elemen website dalam bentuk baris dan kolom. Sistem grid Bootstrap menggunakan 12 kolom sehingga pengembang dapat mengatur pembagian ruang sesuai kebutuhan.

Class grid yang umum digunakan adalah:
- container: membungkus dan mengatur lebar area konten.
- row: membuat baris untuk menampung kolom.
- col: membuat kolom dengan pembagian ruang secara otomatis.
- col-md-6: membuat kolom dengan lebar 6 dari 12 kolom mulai dari breakpoint md.
Breakpoint adalah batas ukuran layar yang menentukan kapan tata letak website berubah menyesuaikan perangkat. Bootstrap 5 memiliki breakpoint bawaan berikut:
Breakpoint	Ukuran layar minimum
sm	576 px
md	768 px
lg	992 px
xl	1200 px
xxl	1400 px
Grid dan breakpoint digunakan agar tampilan website tetap rapi dan mudah digunakan pada perangkat ponsel, tablet, maupun komputer.
4. Class Bootstrap dan Kegunaannya
Berikut sepuluh contoh class Bootstrap beserta kegunaannya.
Class	Kegunaan
container	Mengatur lebar dan posisi konten website.
row	Membuat baris dalam sistem grid.
col-md-6	Membuat kolom selebar setengah baris mulai breakpoint md.
navbar	Membuat komponen navigasi website.
btn btn-primary	Membuat tombol dengan warna utama Bootstrap.
form-control	Mengatur tampilan input pada formulir.
form-check	Mengatur tampilan checkbox atau radio button.
card	Membuat komponen berbentuk kartu untuk mengelompokkan konten.
text-center	Membuat teks rata tengah.
shadow	Memberikan efek bayangan pada elemen.
Class tersebut dapat digunakan secara bersamaan untuk membangun tampilan website tanpa harus menulis CSS khusus untuk setiap elemen.
5. Gambar Responsif
Untuk membuat gambar responsif menggunakan Bootstrap, kita dapat menambahkan class img-fluid pada elemen <img>. Class tersebut menerapkan lebar maksimum sebesar 100% dari elemen induknya dan tinggi otomatis sehingga gambar dapat menyesuaikan ukuran layar tanpa mengubah proporsi aslinya.

Contoh penggunaan:
<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">


Jika gambar disimpan secara lokal dalam folder images, penggunaannya dapat ditulis sebagai berikut:
<img src="images/gambar.jpg" class="img-fluid" alt="Contoh gambar">


Dengan menggunakan class img-fluid, gambar tidak akan melampaui lebar kontainer sehingga tampilannya lebih sesuai pada berbagai ukuran layar perangkat.
