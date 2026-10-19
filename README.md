# Tugas Pendahuluan Modul 5 — Bootstrap

## 1. Pengertian Bootstrap

Bootstrap adalah framework CSS yang membantu kita membuat tampilan website dengan lebih mudah dan cepat. Bootstrap sudah menyediakan berbagai komponen yang bisa langsung digunakan, seperti navbar, tombol, form, card, dan grid. Dengan begitu, kita tidak perlu membuat semua desain dari awal menggunakan CSS. Bootstrap juga membantu membuat website yang responsif agar tampilannya tetap menyesuaikan ukuran layar, baik di laptop maupun HP.

## 2. Cara Memasang Bootstrap

Bootstrap dapat digunakan dengan beberapa cara, di antaranya:

1. **Menggunakan CDN**  
   Bootstrap dapat dihubungkan melalui URL CSS dan JavaScript yang disediakan. Cara ini praktis karena kita tidak perlu mengunduh file Bootstrap terlebih dahulu, tetapi membutuhkan koneksi internet.

2. **Download Bootstrap**  
   File Bootstrap dapat diunduh dari website resminya, kemudian disimpan di dalam folder proyek. Cara ini memungkinkan kita menggunakan file Bootstrap secara lokal.

3. **Menggunakan npm**  
   Bootstrap dapat dipasang menggunakan npm sebagai dependensi proyek. Cara ini biasanya digunakan ketika mengembangkan website dengan pengelolaan package dan build tool.

Pada tugas ini, Bootstrap digunakan melalui CDN karena lebih sederhana dan mudah diterapkan pada file HTML.

## 3. Grid dan Breakpoint

Grid adalah sistem yang digunakan Bootstrap untuk mengatur tata letak elemen website menjadi baris dan kolom. Sistem ini menggunakan pembagian 12 kolom sehingga kita bisa mengatur lebar setiap bagian sesuai kebutuhan.

Beberapa class grid yang sering digunakan adalah `container` untuk membungkus konten, `row` untuk membuat baris, dan `col` untuk membuat kolom.

Sementara itu, breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada perangkat yang berbeda. Contohnya, `col-md-6` membuat elemen menggunakan setengah lebar baris mulai dari ukuran layar medium, yaitu 768 piksel.

Dengan grid dan breakpoint, susunan elemen website bisa menyesuaikan ukuran layar sehingga lebih nyaman dilihat di laptop, tablet, maupun HP.

## 4. Contoh Class Bootstrap dan Kegunaannya

Berikut beberapa class Bootstrap yang sering digunakan beserta fungsinya:

| Class | Kegunaan |
|---|---|
| `container` | Mengatur area konten agar memiliki lebar yang sesuai. |
| `row` | Membuat baris untuk menyusun kolom. |
| `col-md-6` | Membuat kolom dengan lebar setengah baris mulai ukuran layar medium. |
| `navbar` | Membuat menu navigasi pada website. |
| `btn btn-primary` | Membuat tombol dengan warna utama Bootstrap. |
| `form-control` | Mengatur tampilan input, seperti username dan password. |
| `form-check` | Mengatur tampilan checkbox dan radio button. |
| `card` | Mengelompokkan konten dalam bentuk kartu. |
| `text-center` | Membuat teks rata tengah. |
| `shadow` | Memberikan efek bayangan pada elemen. |

Class-class tersebut bisa digabungkan untuk membuat tampilan website tanpa harus menulis CSS dari awal untuk setiap komponen.

## 5. Cara Membuat Gambar Responsif

Agar gambar dapat menyesuaikan ukuran layar, Bootstrap menyediakan class `img-fluid`. Class ini membuat lebar gambar mengikuti ukuran elemen induknya dengan batas maksimum 100%, sedangkan tingginya menyesuaikan secara otomatis agar proporsi gambar tetap terjaga.

Contoh penggunaannya:

```html
<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">
```

Jika gambar disimpan di dalam folder lokal bernama `images`, penulisannya menjadi:

```html
<img src="images/gambar.jpg" class="img-fluid" alt="Contoh gambar">
```

Dengan menggunakan `img-fluid`, gambar dapat menyesuaikan ukuran kontainer dan tidak mudah melampaui batas area tampilan saat dibuka di perangkat dengan ukuran layar yang berbeda.
