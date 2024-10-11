# Membuat List dalam HTML

Proyek ini bertujuan untuk menunjukkan cara membuat berbagai jenis daftar (list) dalam HTML. Jenis-jenis list yang ditampilkan dalam halaman ini adalah ordered list (daftar berurutan), unordered list (daftar tidak berurutan), dan description list (daftar deskripsi).

## Jenis List yang Ditampilkan

1. **Ordered List (ol)** - Daftar Berurutan
2. **Unordered List (ul)** - Daftar Tidak Berurutan
3. **Description List (dl)** - Daftar Deskripsi

## Penjelasan Struktur HTML

### 1. Ordered List (Daftar Berurutan)
Elemen `<ol>` digunakan untuk membuat daftar berurutan, di mana setiap item diberi nomor secara otomatis. Pada contoh ini, daftar mata kuliah dalam Ordered List adalah:
- Pemrograman Web
- Sistem Informasi
- Basis Data 2

### 2. Unordered List (Daftar Tak Berurutan)
Elemen `<ul>` digunakan untuk membuat daftar tak berurutan, di mana setiap item ditandai dengan bullet point (titik). Daftar mata kuliah dalam Unordered List adalah:
- Jaringan Komputer
- Struktur Data
- Algoritma & Pemrograman

### 3. Description List (Daftar Deskripsi)
Elemen `<dl>` digunakan untuk membuat daftar yang berisi deskripsi istilah. Elemen `<dt>` digunakan untuk menampilkan istilah, dan elemen `<dd>` digunakan untuk menampilkan deskripsi istilah tersebut. Pada contoh ini, terdapat dua kategori fakultas dengan daftar program studi masing-masing:
- **Fakultas Teknik**
  - Teknik Industri
  - Teknik Informatika
  - Teknik Lingkungan
- **Fakultas Ekonomi dan Bisnis**
  - Akuntansi
  - Manajemen
  - Bisnis Digital

## Cara Menjalankan Kode
1. Simpan kode HTML di atas dalam sebuah file dengan nama `lab3_list.html`.
2. Buka file tersebut di browser, dan halaman akan menampilkan berbagai jenis daftar sesuai dengan kode HTML yang telah dibuat.

## Tampilan Hasil
Ketika kode dijalankan, berikut ini hasil yang akan muncul:
1. **Ordered List**: Menampilkan daftar dengan penomoran otomatis.
2. **Unordered List**: Menampilkan daftar dengan bullet points.
3. **Description List**: Menampilkan daftar deskripsi untuk setiap fakultas dan program studi.

![Cuplikan layar 2024-10-11 110806](https://github.com/user-attachments/assets/00982873-9509-4f78-82e3-06e364e1d603)


# Membuat Table dalam HTML

Proyek ini bertujuan untuk menunjukkan cara membuat table (tabel) dalam HTML. Tabel ini digunakan untuk menampilkan informasi dalam bentuk baris dan kolom, yang sering digunakan untuk menyusun data yang terstruktur.

## Struktur Tabel yang Ditampilkan

1. **Kolom No.**: Berisi nomor urut untuk setiap entri.
2. **Kolom Fakultas**: Menampilkan nama fakultas.
3. **Kolom Program Studi**: Menampilkan program studi dari fakultas yang terkait.

## Penjelasan Struktur HTML

### Tabel (Table)
Elemen `<table>` digunakan untuk membuat tabel dalam HTML. Setiap tabel terdiri dari beberapa elemen penting:

- **`<tr>`**: Tag untuk membuat baris (row) dalam tabel.
- **`<th>`**: Tag untuk membuat heading atau judul kolom. Digunakan dalam baris pertama tabel.
- **`<td>`**: Tag untuk membuat data dalam tabel, digunakan pada setiap baris setelah heading.

Dalam contoh di atas, tabel memiliki tiga kolom: 
1. Kolom "No." yang menunjukkan nomor urut. 
2. Kolom "Fakultas" yang menampilkan nama fakultas. 
3. Kolom "Program Studi" yang menampilkan program studi dari fakultas tersebut.

### Border dan Padding
Untuk membuat batas antar kolom dan baris terlihat, digunakan properti CSS `border` dan `border-collapse`. Properti `padding` digunakan untuk memberi ruang di sekitar konten dalam setiap sel.

## Cara Menjalankan Kode
1. Simpan kode HTML di atas dalam sebuah file dengan nama `lab3_tabel.html`.
2. Buka file tersebut di browser, dan halaman akan menampilkan tabel yang telah dibuat sesuai dengan kode HTML di atas.

## Tampilan Hasil
Ketika kode dijalankan, tabel akan menampilkan informasi sebagai berikut:
1. No. urut dari 1 hingga 3.
2. Nama Fakultas yaitu "Teknik".

3. Program studi di bawah Fakultas Teknik, yaitu Teknik Informatika, Teknik Industri, dan Teknik Lingkungan.

![Cuplikan layar 2024-10-11 111550](https://github.com/user-attachments/assets/2addfd07-cd85-4ba2-941d-b2947ef359d8)


# Penjelasan Formulir HTML

Ini adalah formulir HTML sederhana untuk mengumpulkan data pelanggan. Formulir ini mencakup rincian berikut:
- **Nama**: Kolom input teks untuk nama pelanggan.
- **Alamat**: Area teks untuk alamat pelanggan.
- **Jenis Kelamin**: Dua tombol radio untuk memilih jenis kelamin pelanggan: Laki-laki atau Perempuan.

Formulir ini dibungkus dalam fieldset dengan judul "Data Pelanggan". Tombol hijau bertuliskan "Login" ada di akhir formulir untuk pengiriman data.

## Struktur Formulir

Formulir ini terdiri dari:
1. **Input Nama**: Kolom input standar (`<input type="text">`).
2. **Input Alamat**: Area teks (`<textarea>`) untuk memasukkan teks yang lebih panjang, seperti alamat.
3. **Pilihan Jenis Kelamin**: Dua tombol radio (`<input type="radio">`) untuk memilih jenis kelamin.
4. **Tombol Login**: Tombol (`<input type="submit">`) untuk mengirimkan formulir, yang diberi gaya sebagai tombol login hijau.

Struktur formulir ini dimaksudkan untuk digunakan dalam skenario pengumpulan data pelanggan, seperti bengkel atau penyedia layanan lainnya.

## Cara Menggunakan
1. Isi kolom "Nama" dengan nama Anda.
2. Masukkan alamat Anda di kotak teks "Alamat".
3. Pilih jenis kelamin dengan memilih tombol radio yang sesuai.
4. Klik tombol "Login" untuk mengirimkan formulir.

![Cuplikan layar 2024-10-11 111817](https://github.com/user-attachments/assets/f6654ee6-efbd-4afd-989f-aedd9c443dc1)



