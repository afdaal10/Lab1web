# Identitas Mahasiswa

**Nama :** Afdhal Agislam  
**NIM :** 312410445  
**Kelas :** TI.24.A5  

---

## HASIL OUTPUT

<img width="959" height="539" alt="image" src=Gambar.png />

# Belajar HTML

Proyek ini merupakan latihan **HTML dasar** pada mata kuliah *Pemrograman Web* di Prodi **Teknik Informatika Universitas Pelita Bangsa**.  
Tujuan utama dari latihan ini adalah agar mahasiswa mampu:

- Memahami konsep dasar **struktur HTML**.  
- Menggunakan tag-tag HTML untuk menampilkan konten di halaman web.  
- Membuat halaman web sederhana yang rapi, terstruktur, dan mudah dipahami.  

---


<h2>Deskripsi</h2>
<p>Halaman web ini menampilkan beberapa elemen dasar HTML, di antaranya:</p>
<ul>
  <li><em>Heading</em> (&lt;h1&gt;, &lt;h2&gt;, dll.)</li>
  <li><em>Paragraf</em> (&lt;p&gt;)</li>
  <li><em>Teks dengan format khusus</em> (tebal, miring, mark / highlight)</li>
  <li><em>Gambar</em> (&lt;img&gt;)</li>
  <li><em>Hyperlink</em> (&lt;a&gt;)</li>
</ul>

## PENJELASAN CODE
- <!DOCTYPE html>
<html>
<head>
    <title>Tag HTML Dasar</title>
    <meta charset="UTF-8">
</head>
<body>

    <!-- Judul utama -->
    <h1>Belajar Dasar HTML</h1>

    <!-- Paragraf pertama dengan format teks -->
    <p>
        Kami sedang belajar <mark>HTML dasar</mark>, pada mata kuliah 
        <b>Pemrograman Web</b> di Prodi <i>Teknik Informatika</i> 
        <a href="https://www.pelitabangsa.ac.id">Universitas Pelita Bangsa</a>. 
        Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana 
        dalam rangka mengenal tag-tag dasar HTML.
    </p>

    <!-- Sub Judul -->
    <h2>Paragraf pada HTML</h2>

    <!-- Paragraf kedua -->
    <p>
        Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling 
        mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan 
        tag dasar html.
    </p>

    <!-- Sub Judul untuk gambar -->
    <h3>Menambahkan Gambar</h3>

    <!-- Menampilkan gambar -->
    <img src="Logo upb.png" width="200" alt="Logo Universitas Pelita Bangsa" title="Logo Universitas Pelita Bangsa">

    <nav> 
        <a href="lab1_tag_dasar.html">Dasar HTML</a> 
        <a href="lab1_halaman2.html">Halaman 2</a> 
        <a href="http://www.google.com">Halaman Web Eksternal Google</a> 
    </nav> 
    <hr> 

</body>
</html>


## 📖 Tabel Ringkasan Tag Dasar

| Tag          | Fungsi                                           | Contoh |
|--------------|--------------------------------------------------|--------|
| `<!DOCTYPE>` | Menentukan tipe dokumen HTML                     | `<!DOCTYPE html>` |
| `<html>`     | Elemen root/utama dokumen HTML                   | `<html lang="id"> ... </html>` |
| `<head>`     | Berisi metadata dokumen (tidak tampil di halaman)| `<head><title>Judul</title></head>` |
| `<title>`    | Judul halaman (muncul di tab browser)            | `<title>Belajar HTML</title>` |
| `<meta>`     | Informasi tambahan (charset, viewport, SEO)      | `<meta charset="UTF-8">` |
| `<body>`     | Isi utama halaman (konten yang terlihat)         | `<body>Konten</body>` |
| `<h1>–<h6>`  | Heading/judul dengan tingkatan 1–6               | `<h2>Subjudul</h2>` |
| `<p>`        | Paragraf teks                                    | `<p>Ini paragraf.</p>` |
| `<a>`        | Hyperlink / tautan ke halaman lain               | `<a href="https://example.com">Link</a>` |
| `<img>`      | Menampilkan gambar                               | `<img src="gambar.png" alt="Gambar">` |
| `<hr>`       | Garis horizontal pemisah                         | `<hr>` |
| `<br>`       | Line break (pindah baris)                        | `Teks<br>Baru` |
| `<strong>`   | Teks penting / ditebalkan                        | `<strong>Important</strong>` |
| `<b>`        | Teks tebal (tanpa makna semantik)                | `<b>Teks Tebal</b>` |
| `<em>`       | Teks miring (emphasis)                           | `<em>Penekanan</em>` |
| `<i>`        | Teks miring (tanpa makna semantik)               | `<i>Teks Miring</i>` |
| `<span>`     | Inline container (bisa diberi style)             | `<span style="color:red;">Teks</span>` |
| `<div>`      | Block container untuk mengelompokkan elemen      | `<div>Konten</div>` |
| `<header>`   | Bagian kepala halaman / section                  | `<header>Judul</header>` |
| `<nav>`      | Bagian navigasi link                             | `<nav><a href="#">Menu</a></nav>` |
| `<section>`  | Bagian konten/section tertentu                   | `<section>Isi Section</section>` |
| `<footer>`   | Bagian bawah halaman                             | `<footer>Hak Cipta</footer>` |
| `<ul>`       | Daftar tidak berurutan (bullet list)             | `<ul><li>Item</li></ul>` |
| `<ol>`       | Daftar berurutan (angka/huruf)                   | `<ol><li>Item</li></ol>` |
| `<li>`       | Item dalam daftar                                | `<li>List item</li>` |
| `<table>`    | Membuat tabel                                    | `<table>...</table>` |
| `<tr>`       | Baris dalam tabel                                | `<tr><td>Data</td></tr>` |
| `<th>`       | Header kolom pada tabel                          | `<th>Judul Kolom</th>` |
| `<td>`       | Data sel pada tabel                              | `<td>Isi</td>` |
| `<form>`     | Membuat form input                               | `<form>...</form>` |
| `<input>`    | Elemen input (teks, tombol, checkbox, dll.)      | `<input type="text">` |
| `<button>`   | Tombol interaktif                                | `<button>Klik</button>` |
| `<label>`    | Label untuk elemen form                          | `<label for="nama">Nama:</label>` |
| `<textarea>` | Input teks multi-baris                           | `<textarea></textarea>` |
| `<select>`   | Dropdown pilihan                                 | `<select><option>A</option></select>` |
| `<option>`   | Opsi dalam dropdown                              | `<option>Opsi 1</option>` |
| `<script>`   | Menyisipkan JavaScript                           | `<script>alert("Hi")</script>` |
| `<link>`     | Menghubungkan file eksternal (CSS, favicon, dll.)| `<link rel="stylesheet" href="style.css">` |
| `<style>`    | Menyisipkan CSS langsung di HTML                 | `<style>p {color: red;}</style>` |



