# Lab1Web.

# Pratikum 1 - HTML Dasar
### NAMA : Richie Pranata
### NIM : 312410451
### KELAS : TI.24.A5

## 📍LANGKAH - LANGKAH PENGERJAAN

### 1. MEMBUAT FILE DASAR HTML.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Lab 1 – HTML Dasar</title>
  </head>
  <body>
    <!-- Konten HTML akan ditambahkan di sini -->
  </body>
</html>
```

📸 **SCREENSHOOT VSCODE DAN BROWSER/TAMPILAN**

<img src="vscode1.png" width="700">

<br>

<img src="tampilan.png" width="700">


## 2. CARA MEMBUAT PARAGRAF

```html
<!-- Ini adalah paragraf pertama --> 
<p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi 
Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat 
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar 
HTML.</p> 
<!-- Ini adalah paragraf kedua --> 
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling 
mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan 
tag dasar html.</p>
```

### 3️. MENAMBAHKAN JUDUL & ISI

Tambahkan heading **h1** dan **h2** sebelum paragraf:

```html
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>
```

**CONTOH TAMPILAN JUDUL DAN ISI**

<img src="vscode2.png" width="700">


### 4. MEMFORMAT TEKS

Lakukan pemformatan teks pada paragraf, misalnya:

```html
<p align="center"><b>Teks ini tebal</b> dan <i>teks ini miring</i></p>
<p align="right">Ini adalah <sub>subscript</sub> dan <sup>superscript</sup></p>
```
**CONTOH TAMPILAN PEMFORMATAN TEKS**

<img src="vscode3.png" width="700">

### 5. MENAMBAHKAN GAMBAR

Simpan gambar pada folder yang sama, lalu tambahkan:

```html
<h3>Menambahkan Gambar</h3>
<img
  src="logo_UPB.png"
  width="250"
  title="Logo Universitas Pelita Bangsa"
  alt="Logo UPB"
/>
```

**CODE TAMPILKAM GAMBAR**

<img src="vscode4.png" width="700">

<img src="logo_UPB.png" width="700">


### 6️. MENAMBAHKAN HYPERLINK

Tambahkan link navigasi sebelum heading h1:

```html
<nav>
  <a href="lab1_tag_dasar.html">Dasar HTML</a>
  <a href="lab1_halaman2.html">Halaman 2</a>
  <a href="http://www.google.com" target="_blank"
    >Halaman Web Eksternal Google</a
  >
</nav>
<hr />
```

Buat file baru **`lab1_halaman2.html`** sebagai halaman kedua.

click bagian yang di tandai untuk berpindah ke halaman lain

<img src="tampilan - Salin.png" width="700">

**Halaman Kedua**

<img src="tampilan2.png" width="700">

**Halaman Web Eksternal**

<img src="tampilan 3.png" width="700">


### 7. HASIL PRAKTIKUM

<img src="tampilan.png" width="700">


##  PERTANYAAN PRAKTIKUM & JAWABANNYA 

Oke, aku buatkan versi **jawaban yang sama tapi dengan kata-kata berbeda** supaya tetap jelas, namun tidak terkesan copy–paste.

---

## **JAWABAN PRAKTIKUM (Versi dengan kata berbeda)**

**1. Adakah error ketika terjadi kesalahan penulisan tag?**
Jika ada kesalahan dalam penulisan tag HTML (misalnya `<pp>` bukannya `<p>` atau tag tidak ditutup), browser tidak langsung menampilkan pesan error seperti di bahasa pemrograman. Browser biasanya tetap menampilkan halaman, tetapi hasil tampilannya bisa **berantakan** atau tidak sesuai struktur yang diinginkan.

---

**2. Apa perbedaan tag `<p>` dengan `<br>`?**

* `<p>` → berfungsi untuk membuat **paragraf baru**, dengan jarak cukup lebar di atas dan bawah teks.
* `<br>` → hanya digunakan untuk **pindah ke baris berikutnya** tanpa menambah jarak seperti paragraf.
  Umumnya `<p>` dipakai untuk teks panjang (artikel, laporan), sedangkan `<br>` cocok untuk teks berformat khusus (puisi, alamat).

---

**3. Apa perbedaan atribut `title` dan `alt` pada tag `<img>`?**

* `alt` → adalah teks alternatif yang muncul jika gambar tidak bisa ditampilkan, serta digunakan oleh pembaca layar untuk membantu pengguna disabilitas.
* `title` → adalah keterangan tambahan yang muncul saat kursor diarahkan ke gambar (tooltip).

👉 Jadi, `alt` penting untuk **pengganti isi gambar**, sementara `title` lebih ke **informasi tambahan bagi pengguna**.

---

**4. Agar proporsional, sebaiknya atribut `width` dan `height` diisi semua atau tidak? Jelaskan.**
Untuk menjaga ukuran gambar tetap seimbang:

* Lebih aman hanya mengisi **salah satu atribut saja** (`width` atau `height`), sehingga browser otomatis menyesuaikan sisi lainnya.
* Jika mengisi keduanya, ukurannya harus sesuai dengan perbandingan asli gambar. Jika tidak, gambar bisa terlihat **distorsi** (terlalu melebar atau gepeng).

---

**5. Apa perbedaan atribut `target` dengan nilai `_blank`, `_self`, `_top`, dan `_parent`?**

* `_blank` → link terbuka di tab/jendela baru.
* `_self` → link terbuka di tab/jendela yang sama (nilai default).
* `_top` → link terbuka di jendela utama, menutup semua frame jika ada.
* `_parent` → link terbuka di frame induk (jika halaman berada di dalam frame).

---

Mau aku bikinkan juga **versi tabel Pertanyaan & Jawaban di Word** biar lebih rapi untuk laporanmu?
