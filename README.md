# Pengenalan HTML

HTML adalah bahasa markah standar untuk membuat halaman web.

## Apa itu HTML?

- HTML adalah kependekan dari Hyper Text Markup Language.
- HTML adalah bahasa markah standar untuk membuat halaman web.
- HTML menjelaskan struktur halaman web.
- HTML terdiri dari serangkaian elemen.
- Elemen HTML memberi tahu peramban cara menampilkan konten.
- Elemen HTML memberi label pada bagian konten seperti "ini adalah judul", "ini adalah paragraf", "ini adalah tautan", dan sebagainya.

## Dokumen HTML Sederhana

## Contoh

```html
<!DOCTYPE html>
<html>
<head>
<title>Judul Halaman</title>
</head>
<body>

<h1>Judul Pertama Saya</h1>
<p>Paragraf pertama saya.</p>

</body>
</html>
```

## Penjelasan Contoh

- Deklarasi ```<!DOCTYPE html>``` mendefinisikan bahwa dokumen ini adalah dokumen HTML5.
- Elemen ```<html>``` adalah elemen akar dari halaman HTML.
- Elemen ```<head>``` berisi informasi meta tentang halaman HTML.
- Elemen ```<title>``` menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul peramban atau di tab halaman).
- Elemen ```<body>``` mendefinisikan isi dokumen dan merupakan wadah untuk semua konten yang terlihat, seperti judul, paragraf, gambar, tautan, tabel, daftar, dan lain-lain.
- Elemen ```<h1>``` mendefinisikan judul besar.
- Elemen ```<p>``` mendefinisikan sebuah paragraf.

## Apa yang dimaksud dengan Elemen HTML?

Elemen HTML terdiri dari tag awal, beberapa konten, dan tag akhir:

```<namatag>``` Konten ada di sini... ```</namatag>```

Elemen HTML adalah segalanya mulai dari tag awal hingga tag akhir:

```<h1>```Judul Pertama Saya```</h1>```

```<p>```Paragraf Pertama Saya```</p>```

| Tag awal | Konten elemen | Tag akhir  |
|:--:|:--:|:--:|
| ```<h1>```  | Judul pertama Saya | ```</h1>```   |
| ```<p>```  | Paragraf pertama Saya | ```</p>```   |
| ```<br>``` | *Tidak ada* | *Tidak ada* |

> **Catatan:**
> Beberapa elemen HTML tidak memiliki konten (seperti elemen ```<br>```). Elemen-elemen ini disebut elemen kosong. Elemen kosong tidak memiliki tag akhir!

## Peramban web

Tujuan peramban web (Chrome, Edge, Firefox, Safari) adalah membaca dokumen HTML dan menampilkannya dengan benar.

Peramban tidak menampilkan tag HTML, tetapi menggunakannya untuk menentukan cara menampilkan dokumen.

![](https://github.com/FII14/Bootstrap5/blob/main/gambar/20230709_003853.jpg)
