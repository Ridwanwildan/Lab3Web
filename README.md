# Latihan membuat Table, List, dan Form HTML

* Nama          : Hizbullah Ridwan
* NIM           : 312110055
* Kelas         : TI.21.B.1
* Mata Kuliah   : Pemrograman Web

Dalam latihan menggunakan CSS ini, saya menggunakan [Google Chrome](https://www.google.com/intl/id_id/chrome/) sebagai web browser dan [visual studio code](https://code.visualstudio.com/) sebagai teks editornya.     

## Membuat Ordered List

Pertama adalah membuat list, untuk membuat list caranya adalah dengan membuat tag `<ol>`         
dan didalamnya ditambahkan tag `<li>`. Daftar list akan ditulis dalam tag `<li>` dan akan otomatis        
ada angkanya.          

```bash
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>
</body>

```         

![Gambar 1](Screenshoots/Capture1.PNG)       

## Membuat Unordered List

Unordered list adalah list tetapi tanpa adanya angka seperti ordered list, untuk membuatnya adalah         
dengan menambahkan tag `<ul>` dan didalamnya ditambahkan tag `<li>`. Nantinya list akan ditandai dengan     
tanda dot.               

```bash
<section id="unorder-list">
    <h2>Unordered List</h2>
    <ul type="square">
        <li>Jaringan Komputer</li>
        <li>Struktur Data</li>
        <li>Algoritma &amp; Pemrograman</li>
    </ul>
</section>
```         

![Gambar 2](Screenshoots/Capture2.PNG)       