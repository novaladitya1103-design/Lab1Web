# Praktikum 1: HTML Dasar

Repository ini dibuat untuk memenuhi tugas **Praktikum 1 - HTML Dasar** pada mata kuliah Pemrograman Web.

Identitas Mahasiswa:

- **Nama:** Noval Aditya Suryawan
- **NIM:** 312510035
- **Kelas:** I253B
- **Program Studi:** Teknik Informatika
- **Dosen Pengampu:** Sufajar Butsianto, S.Kom, M.Kom
- **Kampus:** Universitas Pelita Bangsa

## Panduan Screenshot Tugas

Simpan semua file tangkapan layar (screenshot) di dalam folder `screenshots/` dengan format nama angka (`1.png` sampai `8.png`) sesuai tabel berikut:

| No File | Aplikasi / Lokasi | Yang Harus Di-Screenshot |
| :---: | :--- | :--- |
| **1.png** | VS Code (Editor) | Kode struktur dasar HTML5 pada `index.html` (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`). |
| **2.png** | Browser | Tampilan heading `<h1>`, `<h2>`, dan teks paragraf `<p>` di browser. |
| **3.png** | Browser | Tampilan hasil pemformatan teks (`<b>`, `<i>`, `<mark>`, `<sub>`, `<sup>`, `<del>`, `<ins>`). |
| **4.png** | Browser | Tampilan gambar foto profil mahasiswa (`images/profil.jpg`) dengan lebar 200px. |
| **5.png** | Browser | Tampilan file `halaman2.html` yang menunjukkan navigasi link dan anchor link. |
| **6.png** | Browser | Tampilan Unordered List (`<ul>` keahlian) dan Ordered List (`<ol>` target belajar). |
| **7.png** | Browser | Tampilan utuh satu halaman Profil Mahasiswa (`index.html`) dari atas sampai bawah. |
| **8.png** | Browser<br>([validator.w3.org](https://validator.w3.org)) | Hasil validasi W3C yang menunjukkan halaman bebas error (hijau). |

## Struktur Folder

```## Text
Lab1Web/
├── index.html
├── halaman2.html
├── images/
│   └── profil.jpg
├── screenshots/
│   ├── 1.png
│   ├── 2.png
│   ├── 3.png
│   ├── 4.png
│   ├── 5.png
│   ├── 6.png
│   ├── 7.png
│   └── 8.png
└── README.md

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Praktikum HTML Dasar</title>
</head>
<body>
</body>
</html>

<!-- Judul utama dan subjudul -->
<h1>Belajar Dasar HTML</h1>
<h2>Paragraf pada HTML</h2>

<!-- Paragraf -->
<p>
    Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
    Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
</p>
<p>
    HTML digunakan untuk menyusun struktur dan konten halaman web.
    Browser akan menampilkan hasil interpretasi dari dokumen HTML.
</p>

<p>Belajar <b>HTML dasar</b> pada mata kuliah <i>Pemrograman Web</i>.</p>
<p>HTML adalah <strong>bahasa markup</strong> untuk membuat halaman web.</p>
<p>Status: <mark>Mahasiswa Aktif</mark> | Catatan: <small>Semester Gasal</small></p>
<p>Target: <del>Malas-malasan</del> <ins>Rajin Ngoding</ins></p>
<p>Contoh rumus: H<sub>2</sub>O dan rumus kuadrat x<sup>2</sup> + y<sup>2</sup> = r<sup>2</sup></p>

<h3>Foto Profil</h3>
<img src="images/profil.jpg" width="200" height="200" alt="Foto profil mahasiswa" title="Foto Profil Mahasiswa">

<nav>
    <a href="index.html">Dasar HTML / Profil Mahasiswa</a> |
    <a href="halaman2.html">Halaman 2</a> |
    <a href="https://www.google.com" target="_blank">Website Eksternal</a>
</nav>
<hr>

<!-- Contoh Anchor Link -->
<h2 id="materi">Materi Tambahan</h2>
<p><a href="#materi">Klik untuk loncat ke judul materi ini</a></p>

<h2>Keahlian</h2>
<ul>
    <li>HTML Dasar</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>

<h2>Target Belajar</h2>
<ol>
    <li>Mempelajari struktur HTML</li>
    <li>Mempelajari tag dan atribut</li>
    <li>Membuat halaman HTML</li>
    <li>Menguji halaman pada browser</li>
</ol>

<!-- Bagian Profil Mahasiswa -->
<h2>Profil Mahasiswa</h2>

<!-- Bagian Keahlian -->
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Mahasiswa</title>
</head>
<body>

    <!-- Navigasi Halaman -->
    <nav>
        <a href="index.html">Beranda</a> |
        <a href="halaman2.html">Halaman 2</a> |
        <a href="https://www.google.com" target="_blank">Website Eksternal (Google)</a>
    </nav>
    <hr>

    <!-- Langkah 2: Judul & Paragraf Dasar -->
    <h1>Belajar Dasar HTML</h1>
    <h2>Paragraf pada HTML</h2>
    <p>
        Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
        Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
    </p>
    <p>
        HTML digunakan untuk menyusun struktur dan konten halaman web.
        Browser akan menampilkan hasil interpretasi dari dokumen HTML.
    </p>
    <hr>

    <!-- Judul dan Foto -->
    <h1>Profil Mahasiswa</h1>
    <img src="images/profil.jpg" width="200" height="200" alt="Foto profil mahasiswa" title="Foto Profil Mahasiswa">

    <!-- Data Diri -->
    <h2>Data Diri</h2>
    <p>Nama: <b>Noval Aditya Suryawan</b></p>
    <p>NIM: <b>312510035</b></p>
    <p>Kelas: <b>I253B</b></p>
    <p>Program Studi: <i>Teknik Informatika</i></p>
    <p>
        Saya sedang mempelajari dasar-dasar pengembangan aplikasi web menggunakan <strong>HTML</strong>.
        Praktikum ini melatih pemahaman mengenai struktur dokumen web standar, tag, atribut, teks formatting, hyperlink, gambar.
    </p>

    <!-- Pemformatan Teks Tambahan -->
    <h2>Eksperimen Pemformatan Teks</h2>
    <p>Status: <mark>Aktif</mark></p>
    <p><small>* Terdaftar resmi di pangkalan data kampus.</small></p>
    <p>Rencana: <del>Menunda tugas</del> <ins>Fokus belajar Pemrograman Web</ins></p>
    <p>Contoh penulisan ilmiah: H<sub>2</sub>O dan x<sup>2</sup> + y<sup>2</sup> = r<sup>2</sup></p>
    <p>Belajar HTML dasar sangat <em>penting</em> sebagai fondasi web developer.</p>

    <!-- Keahlian & Target -->
    <h2>Keahlian</h2>
    <ul>
        <li>HTML Dasar</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Target Belajar</h2>
    <ol>
        <li>Mempelajari struktur HTML dan DTD HTML5</li>
        <li>Mempelajari tag, elemen, dan atribut dasar</li>
        <li>Membuat halaman web terstruktur dan semantik</li>
        <li>Menguasai navigasi hyperlink internal dan eksternal</li>
        <li>Menguji tampilan halaman di web browser dan validasi W3C</li>
    </ol>
    
    <hr>
    <p><small>&copy; 2026 Praktikum Pemrograman Web - Lab1Web</small></p>

</body>
</html>

Jawaban Pertanyaan Evaluasi
1. Apa fungsi deklarasi <!DOCTYPE html> pada dokumen HTML?
Fungsinya untuk memberi tahu browser bahwa dokumen tersebut memakai standar HTML5. Deklarasi ini membuat browser merender halaman dalam standard mode, sehingga tampilan elemen web konsisten dan tidak mengalami masalah layout seperti pada quirks mode.

2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?
Tag: Tanda awalan dan akhiran yang ditulis di dalam tanda kurung siku, contohnya <p> (tag pembuka) dan </p> (tag penutup).

Elemen: Kesatuan utuh mulai dari tag pembuka, isi konten teks/elemen lain, sampai tag penutup. Contoh: <p>Halo Dunia</p>.

Atribut: Informasi atau konfigurasi tambahan yang diletakkan di dalam tag pembuka dengan format nama dan nilai, contohnya href="halaman2.html" pada tag <a> atau src="gambar.jpg" pada tag <img>.

3. Apa perbedaan <p> dengan <br>? Jelaskan penggunaannya.
Tag <p> (paragraph) digunakan untuk membuat paragraf baru. Tag ini bertipe blok (block-level) dan secara otomatis memiliki jarak margin atas dan bawah.

Tag <br> (line break) adalah tag tunggal yang berfungsi memindahkan teks ke baris baru tanpa membuat paragraf baru dan tanpa margin yang lebar.

Penggunaan: Gunakan <p> untuk membedakan paragraf kalimat atau topik artikel, sedangkan <br> dipakai saat butuh ganti baris langsung dalam satu paragraf, misalnya pada penulisan alamat atau bait puisi.

4. Apa fungsi atribut href pada tag <a>?
Fungsi href (Hypertext Reference) adalah menentukan alamat atau URL tujuan ke mana pengguna akan diarahkan saat link tersebut diklik, baik itu file lokal di proyek, alamat web lain di internet, ataupun posisi id tertentu di halaman yang sama.

5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?
Hyperlink internal: Menghubungkan halaman-halaman yang berada dalam satu folder/proyek web yang sama. Cukup menggunakan path relatif (contoh: halaman2.html).

Hyperlink eksternal: Mengarahkan pengunjung ke website lain di luar domain kita. Harus menyertakan alamat URL lengkap beserta protokolnya (contoh: [https://www.google.com](https://www.google.com)).

6. Apa fungsi atribut src dan alt pada tag <img>?
src (source): Menunjukkan path atau lokasi file gambar yang ingin ditampilkan.

alt (alternative text): Menyediakan teks pengganti jika gambar gagal dimuat (misal karena nama file salah atau koneksi bermasalah). Atribut ini juga membantu aksesibilitas bagi pengguna tunanetra yang memakai screen reader.

7. Apa perbedaan penggunaan <ul> dan <ol>?
<ul> (unordered list) dipakai untuk daftar yang urutannya tidak terikat nomor urut atau hierarki tertentu. Ditampilkan dengan bullet point (contoh: daftar hobi, keahlian).

<ol> (ordered list) dipakai untuk daftar yang urutan penomorannya penting (1, 2, 3...). Cocok untuk tahapan kerja, urutan langkah tutorial, atau ranking.

8. Apa yang terjadi jika path gambar pada atribut src salah?
Gambar tidak akan muncul di halaman web dan browser akan menampilkan ikon gambar rusak (broken image). Selain itu, teks yang ditulis pada atribut alt akan muncul sebagai pengganti gambar tersebut, dan pada browser console akan muncul error 404 Not Found.

9. Mengapa struktur heading <h1> sampai <h6> perlu digunakan secara terstruktur?
Supaya susunan konten halaman rapi dan memiliki hierarki informasi yang jelas dari topik utama (<h1>) sampai sub-topik (<h2> hingga <h6>). Struktur yang rapi juga sangat penting untuk membantu mesin pencari (SEO) memahami poin penting artikel serta mempermudah pengguna alat bantu screen reader saat menavigasi halaman.

10. Apa fungsi komentar <!-- ... --> dalam kode HTML?
Komentar digunakan untuk menulis catatan dokumentasi atau penanda batas antar bagian kode tanpa ikut ditampilkan oleh browser ke pengguna. Komentar juga berguna saat proses debugging untuk mematikan sementara baris kode tertentu tanpa perlu menghapusnya.

Checklist Sebelum Dikumpulkan
Berdasarkan checklist pada modul:

[x] Struktur HTML sudah lengkap.

[x] Heading dan paragraf sudah digunakan.

[x] Pemformatan teks sudah dicoba.

[x] Gambar tampil dengan benar.

[x] Hyperlink internal dan eksternal dapat digunakan.

[x] Unordered list dan ordered list sudah dibuat.

[x] Komentar HTML sudah dicoba.

[x] Screenshot setiap tahap sudah tersedia (file 1.png sampai 8.png di folder screenshots/).

[x] README.md sudah menjelaskan proses praktikum.

[x] Repository sudah dibuat dan siap dikumpulkan.
