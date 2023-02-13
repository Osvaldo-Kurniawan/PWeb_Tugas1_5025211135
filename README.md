# PWeb_Tugas1_5025211135

Nama : Gabrielle Immanuel Osvaldo Kurniawan

NRP  : 5025211135

# Tugas HTML
HTML (HyperText Markup Language) adalah bahasa markup yang digunakan untuk membuat halaman web. Ini adalah bahasa standar industri yang digunakan untuk menentukan bagaimana halaman web akan tampil dan berfungsi. HTML menggunakan tag untuk menentukan bagian-bagian dari halaman web, seperti judul, paragraf, gambar, link, dan banyak lagi. Dalam pengerjaan tugas kali ini HTML akan dipergunakan untuk menampilkan teks, tabel dan gambar. Berikut adalah source code HTML CV saya :
```
<!DOCTYPE html>
<html>
  <head>
    <title>CV Saya</title>
  </head>
  <body bgcolor="#000000" text="#FFFFFF">
    <header>
      <center><h1>Gabrielle Immanuel Osvaldo Kurniawan</h1></center>
    </header>
    <main>
    <center><section>
        <img src="images\Foto.png" width="180" height="240" style="border: 2px solid whitesmoke;">
        <h2>Tentang Saya</h2>
        <p>Saya yang kerap dipanggil dengan panggilan Valdo saat ini sedang menempuh studi saya di ITS.<br>Saat ini saya belajar pemrogramman web bersama dengan teman teman di semester 4.<br>Saya memilih jurusan informatika karena ingin belajar banyak mengenai teknologi AI dan IoT.<br>Harapan saya studi saya dapat berjalan dengan lancar dan mendapat hasil yang memuaskan.</p>
    </section>
    <section>
        <h2>Biodata Diri</h2>
        <table border="1" cellpadding="10">
        <tr>
            <td>Nama</td>
            <td>:</td>
            <td>Gabrielle Immanuel Osvaldo Kurniawan</td>
        </tr>
        <tr>
            <td>Umur</td>
            <td>:</td>
            <td>21</td>
        </tr>
        <tr>
            <td>Alamat</td>
            <td>:</td>
            <td>Jl. Kenjeran 356 A</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>:</td>
            <td>osvaldo.giok@gmail.com | 5025211135@mhs.its.ac.id</td>
        </tr>
        </table>
      </section>
      <section>
        <h2>Pendidikan</h2>
        <p>
            <h3>SMAK St. Louis 1 Surabaya</h3>
            <img src="images\Sinlui.png" width="150" height="150">
            <br>Bidang Studi: MIPA
            <br>Tahun Lulus: 2019
            <h3>Institut Teknologi Sepuluh Nopember</h3>
            <img src="images\ITS.png" width="150" height="150">
            <br>Jurusan: Teknik Informatika
            <br>Tahun Lulus: 2025 (diperkirakan)
        </p>
      </section>
      <section>
        <h2>Kemampuan</h2>
          Pemrograman C++, java, phyton<br>
          Office Software<br>
          Database SQL<br>
          Desain Grafis dengan Adobe Photoshop
      </section>
    </center>
    </main>
  </body>
</html>
```
# Bagian HTML
Ketika dibedah struktur diatas dibagi menjadi 2 bagian yaitu head dan body dalam tugas ini semua elemen HTML diposisikan *allignment* center
1. Bagian head
```
<head>
    <title>CV Saya</title>
</head>
 ```
 Bagian ini menjadi judul dari halaman web yang dibuat yaitu 'CV Saya'
 
2. Bagian body

Bagian body sendiri saya bagi menjadi banyak bagian (section) sebagai berikut :

* Section 1 (Head) adalah tempat highlight dari CV saya yaitu nama saya sendiri
```
<header>
      <center><h1>Gabrielle Immanuel Osvaldo Kurniawan</h1></center>
</header>
```
* Section 2 berisi foto dan profil singkat saya
```
<main>
    <center><section>
        <img src="images\Foto.png" width="180" height="240" style="border: 2px solid whitesmoke;">
        <h2>Tentang Saya</h2>
        <p>Saya yang kerap dipanggil dengan panggilan Valdo saat ini sedang menempuh studi saya di ITS.<br>Saat ini saya belajar pemrogramman web bersama dengan teman  teman di semester 4.<br>Saya memilih jurusan informatika karena ingin belajar banyak mengenai teknologi AI dan IoT.<br>Harapan saya studi saya dapat berjalan dengan lancar dan mendapat hasil yang memuaskan.</p>
    </section>
```
* Section 3 berisi tabel biodata saya yang lebih lengkap
```
<section>
        <h2>Biodata Diri</h2>
        <table border="1" cellpadding="10">
        <tr>
            <td>Nama</td>
            <td>:</td>
            <td>Gabrielle Immanuel Osvaldo Kurniawan</td>
        </tr>
        <tr>
            <td>Umur</td>
            <td>:</td>
            <td>21</td>
        </tr>
        <tr>
            <td>Alamat</td>
            <td>:</td>
            <td>Jl. Kenjeran 356 A</td>
        </tr>
        <tr>
            <td>Email</td>
            <td>:</td>
            <td>osvaldo.giok@gmail.com | 5025211135@mhs.its.ac.id</td>
        </tr>
        </table>
      </section>
```
* Section 4 dan 5 berisi latar belakang pendidikan diikuti dengan gambar
```
<section>
        <h2>Pendidikan</h2>
        <p>
            <h3>SMAK St. Louis 1 Surabaya</h3>
            <img src="images\Sinlui.png" width="150" height="150">
            <br>Bidang Studi: MIPA
            <br>Tahun Lulus: 2019
            <h3>Institut Teknologi Sepuluh Nopember</h3>
            <img src="images\ITS.png" width="150" height="150">
            <br>Jurusan: Teknik Informatika
            <br>Tahun Lulus: 2025 (diperkirakan)
        </p>
      </section>
      <section>
        <h2>Kemampuan</h2>
          Pemrograman C++, java, phyton<br>
          Office Software<br>
          Database SQL<br>
          Desain Grafis dengan Adobe Photoshop
      </section>
    </center>
    </main>
```
