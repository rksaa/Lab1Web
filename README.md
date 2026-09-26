## Penjelasan tiap baris kode HTML

Berikut penjelasan dari file `index.html` yang sudah dibuat:

### 1. Deklarasi HTML
```html
<!DOCTYPE html>
```
- Menandakan bahwa dokumen ini adalah file HTML5.
- Ini wajib ada agar browser tahu tipe dokumen yang dibaca.

### 2. Elemen utama
```html
<html lang="id">
```
- `<html>` = tag pembuka halaman HTML.
- `lang="id"` = menandakan bahasa halaman adalah Indonesia.

### 3. Bagian kepala halaman
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belajar Dasar HTML</title>
```
- `<head>` = berisi informasi halaman, bukan konten utama.
- `meta charset="UTF-8"` = mengatur karakter teks agar bisa menampilkan huruf dan simbol dengan benar.
- `meta viewport` = agar halaman bisa menyesuaikan ukuran layar pada perangkat mobile.
- `<title>` = judul halaman yang muncul di tab browser.

### 4. Style CSS
```html
<style>
    body {
        font-family: Arial, sans-serif;
        background: linear-gradient(135deg, #f3f7ff, #e7f0ff);
        margin: 0;
        padding: 40px 20px;
        color: #1f2937;
    }
```
- CSS ini digunakan untuk mempercantik tampilan halaman.
- `font-family` = jenis huruf.
- `background` = latar belakang halaman.
- `margin` dan `padding` = jarak antar elemen.
- `color` = warna teks.

### 5. Container utama
```html
.container {
    max-width: 900px;
    margin: 0 auto;
    background: #ffffff;
    padding: 30px 35px;
    border-radius: 16px;
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.08);
}
```
- `.container` = class untuk membungkus isi halaman agar lebih rapi.
- `max-width` = lebar maksimal konten.
- `margin: 0 auto` = membuat konten berada di tengah.
- `background` = warna latar belakang kotak.
- `border-radius` = membuat sudut membulat.
- `box-shadow` = memberi bayangan agar tampil lebih elegan.

### 6. Judul utama
```html
<h1>Belajar Dasar HTML</h1>
```
- `<h1>` = heading paling besar, biasanya untuk judul utama.

### 7. Subjudul
```html
<h2>Paragraf pada HTML</h2>
```
- `<h2>` = heading tingkat dua, lebih kecil dari h1.

### 8. Paragraf
```html
<p>
    Kami sedang belajar <b>HTML dasar</b> pada mata kuliah <i>Pemrograman Web</i>.
    Praktikum ini digunakan untuk mengenal tag-tag dasar HTML.
</p>
```
- `<p>` = membuat paragraf.
- `<b>` = teks tebal.
- `<i>` = teks miring.

### 9. Paragraf kedua
```html
<p>
    HTML digunakan untuk menyusun struktur dan konten halaman web. Browser akan menampilkan
    hasil interpretasi dari dokumen HTML.
</p>
```
- Menjelaskan fungsi HTML dan cara browser menampilkannya.

### 10. Teks penting
```html
<p>
    HTML merupakan <strong>bahasa markup</strong> untuk menyusun struktur halaman web.
</p>
```
- `<strong>` = menandai teks penting, tampil lebih tebal dari teks normal.

### 11. Subscript dan superscript
```html
<p>
    Air ditulis sebagai H<sub>2</sub>O dan luas dapat ditulis sebagai x<sup>2</sup>.
</p>
```
- `<sub>` = subscript, untuk angka bawah, seperti H₂O.
- `<sup>` = superscript, untuk angka atas, seperti x².

### 12. Kotak gambar
```html
<div class="profile">
    <div>
        <h3>Menambahkan Gambar</h3>
        <p>Berikut adalah contoh penggunaan tag gambar pada HTML untuk menampilkan foto profil.</p>
    </div>
    <img src="images/profil.jpeg" alt="Foto profil mahasiswa" title="Foto Profil Mahasiswa">
</div>
```
- `<div>` = wadah atau blok konten.
- `class="profile"` = mengatur tampilan kotak gambar.
- `<h3>` = judul kecil untuk bagian gambar.
- `<img>` = menampilkan gambar.
- `src` = lokasi file gambar.
- `alt` = teks alternatif jika gambar tidak tampil.
- `title` = judul saat mouse diarahkan ke gambar.

### 13. Penutup dokumen
```html
</body>
</html>
```
- `</body>` = menutup bagian isi halaman.
- `</html>` = menutup dokumen HTML.

---

## Kesimpulan
Kode di atas adalah contoh halaman HTML sederhana yang berisi:
- struktur dasar HTML,
- teks dan paragraf,
- format teks,
- rumus kimia/matematika,
- dan gambar profil.

Kalau mau, saya juga bisa bantu buatkan:
- versi penjelasan yang lebih singkat untuk tugas,
- versi laporan formal,
- atau versi yang lebih lengkap dengan penjelasan per tag dan fungsinya satu per satu.