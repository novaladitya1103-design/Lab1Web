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

```text
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

## Langkah Pengerjaan Praktikum

### 1. Struktur Dasar HTML5

Membuat file `index.html` dengan kerangka dokumen HTML5: deklarasi `<!DOCTYPE html>`, tag `<html>`, `<head>` untuk judul tab browser, dan `<body>` untuk tempat konten diletakkan.

```html
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Praktikum HTML Dasar</title>
</head>
<body>
</body>
</html>

![Deskripsi Gambar](./screenshots/1.png)