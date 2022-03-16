| Ahmad Alfian Chandra | 312010336         |
|--------------------- |-----------------  |
|       TI.20.A.2      | PEMROGRAMAN WEB   |
|          HTML        |        CSS        |

# 1 Judul Lab2Web
### Pertemuan 3
Untuk Matakuliah hari ini yang di pelajarkan yaitu mata kuliah Pemrograman Web tentang CSS dasar
# Dokumen HTML
### Contoh code dan Hasil nya
![Dokumen_HTML](img/Dasar_HTML.png)
Disini sudah terdapar file Dokumen HTML yang belom terdapat file css nya

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Dasar</title>

</head>

<body>
    <header>
        <h1>CSS Internal dan <i>Inline CSS</i></h1>
    </header>
    <nav>
        <a href="lab2_css_dasar.html">CSS Dasar</a>
        <a href="lab2_css_eksternal.html">CSS Eksternal</a>
        <a href="lab1_tag_dasar.html">HTML Dasar</a>
    </nav>
    <!-- CSS ID Selector -->
    <div id="intro">
        <h1>Hello World</h1>
        <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
                Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
            adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
            dan CSS.</p>
        <!-- CSS Class Selector -->
        <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
    </div>
</body>

</html>
```
## 2). MENDEKLARASIKAN CSS INTERNAL
### Contoh code beserta hasilnya dan juga penempatan CSS nya
![menambahkan_CSS_Internal](img/CSS_Internal.png)
CSS internal adalah css yang filenya di letakan dalam html dengan pendeklarasian style.

## Source Code

```css
<style>
    body{
        font-family: 'Times New Roman', Times, serif;
    }
    header{
        min-height: 100px;
        border-bottom: 4px solid #0a9396;
    }
    h1{
        font-size: 25px;
        color: #e07a5f;
        text-align: center;
        padding: 20px 15px;
    }
    h1 i{
        color: #f9c74f;
    }
</style>
```
## 3). MENAMBAHKAN INLINE CSS
### Contoh code beserta hasil nya dan juga penempatan CSS nya!
![menambahkan_Inline_CSS](img/Menabahkan_inline.png)

CSS inline adalah css yang pendeklarasiannya di dalam elemen HTML dengan code style inline memiliki prioritas lebih kuat di banding internal dan external.
```html
<p style="text-align: center; color: black;">Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
                Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
            adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
            dan CSS.</p>
```
## 4). MEMBUAT CSS EKSTERNAL
### Contoh code dan penempatan CSS internal
![code_dan_hasilnya_CSS_eksternal](img/CSS_Eksternal.png)
CSS ekternal adalah CSS yang file di tempatkan di luar file HTML dengan menambahkan link dalam HTML agar tertaut dengan file CSS

```css
nav{
    background: #ff595e;
    color: white;
    padding: 15px;
}
nav a{
    color: white;
    text-decoration: none;
    padding: 15px 20px;
}
nav .active,
nav a:hover{
    background: black;
}

```
## 5). MENAMBAHKAN CSS SELECTOR 
### Contoh code dan juga selector
![menambahkan_CSS_selector](img/CSS_Selector.png)
CSS Selector terdiri atas selector ID, Selector Class, Dan Selector elemen Selector ID pendeklarasiannya yaitu dengan (#), Sedangkan Class pendeklarasiannya yaitu dengan (.), Dan Selector elemen pendeklarasiannya dengan elemen HTML sebagai contoh (p) yang akan di beri gaya pada CSS.

## Source Code
```css
/* Id Selector */
#intro{
    background: #80ffdb;
    border: 1px solid black;
    min-height: 100px;
    padding: 10px;
}
#intro h1{
    text-align: left;
    border: 0;
    color: #7400b8;
}
/* Class Selector */
.button{
    padding: 15px 20px;
    background: #8ac926;
    color: white;
    display: inline-block;
    margin: 10px;
    text-decoration: none;
}
.btn-primary{
    background: black;
}
```
### Sekian TerimaKasih Mohon maaf apabila pejelas saya kurang jelas.