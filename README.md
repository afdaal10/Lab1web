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

<!DOCTYPE html>
Menandakan dokumen ini adalah HTML5. Wajib ditempatkan di baris pertama agar browser merender sesuai standar modern.

<html lang="id">
Atribut lang="id" memberi tahu browser dan pembaca layar (screen reader) bahwa bahasa utama halaman ini adalah Bahasa Indonesia.

<head>
Bagian metadata: charset, viewport, title, meta description, dan style minimal untuk preview.

meta charset="utf-8" memastikan karakter non-ASCII tampil benar.

meta name="viewport" penting untuk tampilan responsif pada perangkat mobile.

<title> teks yang muncul pada tab browser.

meta description membantu SEO / ringkasan halaman.

<style> (opsional di head)
Styling singkat agar contoh terlihat rapi saat dilihat tanpa file CSS terpisah. Untuk proyek nyata, lebih baik buat file CSS terpisah.

<body> — struktur semantik:

<header>: area atas halaman (navigasi + judul).

<nav>: link navigasi internal/eksternal. Atribut target="_blank" untuk membuka link eksternal di tab baru, rel="noopener noreferrer" untuk keamanan.

<main>: konten utama (paragraf, section). Gunakan elemen semantik (section, article) untuk struktur yang jelas.

<footer>: informasi footer.

Teks & format:

<h1>, <h2>, <h3> untuk judul/heading (hierarki penting untuk aksesibilitas/SEO).

<p> untuk paragraf. Hindari atribut HTML lama seperti align="center"; gunakan CSS (style="text-align:center;" atau file CSS).

<strong> untuk teks tebal (penting), <em> untuk miring (penekanan).

<code> untuk menampilkan kode/tag di dalam paragraf.

Gambar:

<img src="Logo_UPB.png" alt="..." width="200" title="...">
alt wajib untuk aksesibilitas (pembaca layar dan bila gambar gagal dimuat). src harus path benar (perhatikan nama file — jangan Logo_UPB.png.png kecuali memang begitu nama filenya).


## 📖 Tabel Ringkasan Tag Dasar

| Tag         | Fungsi                       | Contoh                                   |
| ----------- | ---------------------------- | ---------------------------------------- |
| `<h1>–<h6>` | Judul dengan tingkat berbeda | `<h1>Judul</h1>`                         |
| `<p>`       | Paragraf teks                | `<p>Teks</p>`                            |
| `<a>`       | Hyperlink                    | `<a href="https://example.com">Link</a>` |
| `<img>`     | Menampilkan gambar           | `<img src="gambar.png" alt="deskripsi">` |
| `<strong>`  | Teks tebal                   | `<strong>Teks</strong>`                  |
| `<em>`      | Teks miring                  | `<em>Teks</em>`                          |
| `<footer>`  | Bagian bawah halaman         | `<footer>Footer</footer>`                |

