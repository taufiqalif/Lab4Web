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

## membuat tampilan layout sederhaman

1.  kita buat dokumen `HTML` terlebih dahulu

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

2.  tulis kode berikut ini

![09.png](img/09.png)

maka akan menampilkan

![10.png](img/10.png)

menambahkan style

![11.png](img/11.png)

menampilkan

![12.png](img/12.png)

3. membuat navigasi

![13.png](img/13.png)

refres browser maka akan menampilkan

![14.png](img/14.png)

4. Membuat Hero Panel

tulis code HTML dan CSS sebagai berikut

![15.png](img/15.png)

![16.png](img/16.png)

maka akan menampilkan

![016.png](img/016.png)

5. Mengatur Layout Main dan Sidebar

tambahkan css float

![17.png](img/17.png)

6. Membuat Sidebar Widget

menambahkan element lain dalam sidebar

![18.png](img/18.png)

menambahkan style

![19.png](img/19.png)

maka akan menampilkan sebagai berikut

![20.png](img/20.png)

7.  membuat footer

        <footer>
          <p>&copy; 2021 - Universitas Pelita Bangsa</p>
        </footer>

tambahkan CSS untuk footer

![21.png](img/21.png)

![22.png](img/22.png)

8. Menambahkan Elemen lainnya pada Main Content

![23.png](img/23.png)

menambahkan style

![24.png](img/24.png)
![25.png](img/25.png)

maka akan menampilkan

![26.png](img/26.png)

9. Menambahkan Content Artikel
   Selanjutnya membuat content artikel. Tambahkan HTML berikut pada main content

![27.png](img/27.png)

menambahkan style

![28.png](img/28.png)

![29.png](img/29.png)

### about

1. buat file HTML baru

2. membuat halaman about singgel layout

![30.png](img/30.png)

menambahkan style

![31.png](img/31.png)

maka akan memapilkan sebagai berikut

![32.png](img/32.png)

### kontak

1. buat file HTML baru

2. membuat form

![33.png](img/33.png)

menambahkan style

![34.png](img/34.png)

style untuk tombol

![35.png](img/35.png)

maka akan menampilkan form

![36.png](img/36.png)
