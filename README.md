# Lab4Web

Latihan membuat layout....

**Web Layout**
Web layout merupakan kerangka yang mengatur penempatan tata letak sebuah elemen pada halaman web. Tata letak element seperti navigasi, header, tombol CTA (Call to Action), dan elemen lainnya pada halaman web, sehingga tampilan web dapat disesuaikan dengan desain yang ada. Dengan layout website yang tepat, informasi akan tampil dengan lebih menawan dan fungsional.

Halaman web sering kali dibagi menjadi header, menu, konten, dan footer: Ada banyak sekali desain tata letak yang dapat dipilih.

## Membuat Box Element

**Box Element**
Element HTML dapat dianggap sebagai sebuah Box atau kotak. Box tersebut digunakan untuk membuat layout web. Pada dasarnya semua element HTML adalah box dengan beberapa perbedaan. Ada yang floating ada juga yang tanpa floating.

Tag yang biasanya digunakan dalam merancang layout web adalah tag div dengan konsep box element. Konsep box element terdiri dari Margin, Border, Padding, dan Content.

1.  pertama buat dokumen HTML terlebih dahulu

        <!DOCTYPE html>
        <html lang="en">
        <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
        </head>
        <body>

        </body>
        </html>

2.  kemudian membuat box element menggunakan tag `div`

![01.png](img/01.png)

3. menambahkan style untuk box element

![02.png](img/02.png)

maka akan menampilkan sebagai berikut

![03.png](img/03.png)

4. Mengatur Clearfix Element
   Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk mengaturnya.
   Tambahkan element div lainnya seteleah div3 seperti berikut.

![04.png](img/04.png)

kemudian atur properti clear pada css sebagai berikut

![05.png](img/05.png)

kemudian buka browser dan refresh

`clear: left;`
maka akan tampil seperti gambar di bawah

![06.png](img/06.png)

`clear: right;`
maka akan tampil seperti gambar di bawah

![07.png](img/07.png)

`clear: both;`
maka akan tampil seperti gambar di bawah

![08.png](img/08.png)
