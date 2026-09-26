# Penjelasan Kode HTML — Belajar Dasar HTML

Dokumen ini menjelaskan struktur dan fungsi setiap bagian dari kode HTML pada praktikum Pemrograman Web.

## 1. Struktur Dasar Dokumen

```html
<!DOCTYPE html>
<html>
<head>
<title>index</title>
</head>
<body>
</body>
</html>
```

- `<!DOCTYPE html>` — mendeklarasikan bahwa dokumen ini menggunakan HTML5.
- `<html>` — elemen root yang membungkus seluruh isi halaman.
- `<head>` — berisi informasi tentang dokumen yang tidak ditampilkan langsung di halaman, seperti judul tab browser.
- `<title>index</title>` — menentukan judul yang muncul pada tab browser, yaitu "index".
- `<body>` — bagian yang berisi seluruh konten yang akan ditampilkan di halaman web.

## 2. Judul dan Subjudul

```html
<h1>Belajar Dasar HTML</h1>
<h2>Paragraf pada HTML</h2>
```

- `<h1>` sampai `<h6>` adalah tag heading (judul), dengan `<h1>` sebagai judul terbesar/utama dan semakin besar angkanya semakin kecil ukurannya.
- Di sini `<h1>` digunakan sebagai judul utama halaman, dan `<h2>` sebagai subjudul.
**Screenshot Hasil:**  
![Langkah 1 - Struktur Dasar dan judul dan subjudul](./screenshoot/1.png)
## 3. Paragraf

```html
<p>
Kami sedang belajar HTML dasar pada mata kuliah Pemrograman Web.
Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
</p>
```

- Tag `<p>` digunakan untuk membuat paragraf teks biasa. Setiap `<p>` baru otomatis dimulai pada baris baru dengan jarak (margin) di atas dan bawahnya.
**Screenshot Hasil:**  
![Langkah 2 - Paragraf](./screenshoot/2.png)
## 4. Format Teks (Bold, Italic, Strong)

```html
<p>
Kami sedang belajar <b>HTML dasar</b> pada mata kuliah
<i>Pemrograman Web</i>.
</p>
<p>
HTML merupakan <strong>bahasa markup</strong> untuk menyusun
struktur halaman web.
</p>
```

- `<b>` — menebalkan teks secara visual saja (tanpa makna semantik khusus).
- `<i>` — memiringkan teks secara visual saja.
- `<strong>` — menebalkan teks dan sekaligus menandakan bahwa teks tersebut penting secara semantik (lebih disarankan daripada `<b>`).

## 5. Subscript dan Superscript

```html
<p>
Air ditulis sebagai H<sub>2</sub>O dan luas dapat ditulis
sebagai x<sup>2</sup>.
</p>
```

- `<sub>` — menampilkan teks sebagai subscript (turun di bawah baris teks), cocok untuk rumus kimia seperti H₂O.
- `<sup>` — menampilkan teks sebagai superscript (naik di atas baris teks), cocok untuk pangkat seperti x².
**Screenshot Hasil:**  
![Langkah 3 - Format Teks dan Subscript dan Superscript](./screenshoot/3.png)
## 6. Menambahkan Gambar

```html
<h3>Menambahkan Gambar</h3>
<img src="images/profil.jpeg"
width="200"
alt="Foto profil mahasiswa"
title="Foto Profil Mahasiswa">
```

- `<h3>` — heading level 3, digunakan sebagai sub-subjudul untuk bagian gambar.
- `<img>` — tag untuk menampilkan gambar, dan tidak memiliki tag penutup.
- `src` — lokasi/path file gambar yang akan ditampilkan (di sini `images/profil.jpeg`).
- `width` — mengatur lebar gambar dalam piksel (200px).
- `alt` — teks alternatif yang muncul jika gambar gagal dimuat, juga penting untuk aksesibilitas (pembaca layar).
- `title` — teks tooltip yang muncul saat kursor diarahkan ke gambar.
**Screenshot Hasil:**  
![Langkah 4 - Struktur Dasar](./screenshoot/4.png)
## 7. Komentar HTML

```html
<!-- navigasi halaman -->
```

- Ditulis dengan `<!-- ... -->` dan tidak ditampilkan oleh browser. Digunakan untuk memberi catatan pada kode, misalnya menandai awal suatu bagian (section) agar kode lebih mudah dibaca.

## 8. Navigasi (`<nav>` dan `<a>`)

```html
<nav>
<a href="index.html">Dasar HTML</a>
<a href="halaman2.html">Halaman 2</a>
<a href="https://www.google.com">Website Eksternal</a>
</nav>
```

- `<nav>` — menandai bagian halaman yang berisi kumpulan tautan navigasi.
- `<a href="...">` — tag hyperlink (tautan). Atribut `href` menentukan tujuan tautan.
  - Tautan ke `index.html` dan `halaman2.html` adalah tautan **internal** (menuju halaman lain dalam situs yang sama).
  - Tautan ke `https://www.google.com` adalah tautan **eksternal** (menuju situs lain di internet).
**Screenshot Hasil:**  
![Langkah 5 - Navigasi](./screenshoot/5.png)
## 9. Garis Pemisah

```html
<hr>
```

- `<hr>` — menampilkan garis horizontal sebagai pemisah antar bagian konten. Tidak memiliki tag penutup.

## 10. List Tidak Berurutan dan Berurutan

```html
<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
</ul>

<ol>
<li>Mempelajari struktur HTML</li>
<li>Mempelajari tag dan atribut</li>
</ol>
```

- `<ul>` (unordered list) — daftar tidak berurutan, ditampilkan dengan tanda bullet (•). Cocok untuk daftar yang urutannya tidak penting, seperti daftar keahlian.
- `<ol>` (ordered list) — daftar berurutan, ditampilkan dengan penomoran (1, 2, 3, ...). Cocok untuk daftar yang urutannya penting, seperti tahapan belajar.
- `<li>` (list item) — setiap item di dalam `<ul>` atau `<ol>`.

## 11. Dokumen Kedua: Halaman Profil Mahasiswa

Bagian ini adalah dokumen HTML lengkap dan terpisah (`Profil Mahasiswa`), menggabungkan semua elemen yang sudah dijelaskan di atas menjadi satu halaman utuh:

- **`<head><title>Profil Mahasiswa</title></head>`** — judul tab browser untuk halaman ini.
- **`<nav>`** — menu navigasi berisi tautan ke "Beranda" (index.html) dan "Halaman 2".
- **`<hr>`** — pemisah antara navigasi dan konten utama.
- **`<h1>Profil Mahasiswa</h1>`** — judul utama halaman.
- **`<img>`** — menampilkan foto profil mahasiswa dengan lebar 200px.
- **`<h2>Data Diri</h2>`** diikuti tiga `<p>`** — menampilkan data diri (nama, NIM, program studi) masing-masing dalam paragraf terpisah, serta satu paragraf deskripsi singkat.
- **`<h2>Keahlian</h2>` + `<ul>`** — daftar keahlian (HTML, CSS, JavaScript) sebagai list tidak berurutan karena urutannya tidak penting.
- **`<h2>Target Belajar</h2>` + `<ol>`** — daftar target belajar sebagai list berurutan karena mencerminkan tahapan/urutan pencapaian yang ingin dicapai.

Struktur ini menunjukkan bagaimana elemen-elemen dasar (heading, paragraf, gambar, list, navigasi) digabungkan untuk membentuk satu halaman web yang utuh dan terstruktur.
**Screenshot Hasil:**  
![Langkah 9 - Halaman Profil](./screenshoot/9.png)
## Ringkasan

Kode ini mendemonstrasikan elemen-elemen dasar HTML: struktur dokumen (`html`, `head`, `body`), heading (`h1`–`h3`), paragraf (`p`), format teks (`b`, `i`, `strong`, `sub`, `sup`), penyisipan gambar (`img`), komentar (`<!-- -->`), navigasi dan tautan (`nav`, `a`), garis pemisah (`hr`), serta list berurutan dan tidak berurutan (`ol`, `ul`, `li`) — yang kemudian digabungkan menjadi halaman profil mahasiswa yang utuh.
