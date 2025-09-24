# Lab1Web
Nama: Afnan Dika Ramadhan

NIM: 312410518

Kelas: TI24.A5

Mata Kuliah: Pemrograman Web

# Pratikum 1 - Lab1web
**Halaman 1**

![foto](https://github.com/nanafnan09/Lab1Web/blob/621935f62300948a8af5b8ef99b40ae196178674/kode%20halaman%201.png)

**Penjelasan Kode HTML Dasar**

Kode ini merupakan contoh dasar dari struktur halaman web menggunakan HTML. Berikut adalah penjelasan dari setiap bagian kode untuk membantu memahami cara kerjanya.

**1. Struktur Dasar Halaman**

- Baris 1-4, 28: Tag ```<html>``` adalah elemen root yang membungkus seluruh konten halaman. Tag ```<head>``` berisi metadata tentang dokumen, seperti judul.
  
- Baris 3: Tag ```<title>``` menetapkan judul yang akan muncul di tab browser.

- Baris 11, 27: Tag ```<body>``` berisi semua konten yang terlihat oleh pengguna, seperti teks, gambar, dan tautan.

**2. Navigasi**

- Baris 5-9: Tag ```<nav>``` mendefinisikan bagian navigasi. Di dalamnya terdapat daftar tautan.

- Baris 6-8: Tag ```<a>``` (anchor) digunakan untuk membuat hyperlink. Atribut ```href``` berisi URL tujuan.

- ```href="Dasar HTML.html"```: Tautan ke halaman lokal.
  
- ```href="lab1_tag_dasar.html"```: Tautan ke halaman lain dalam folder yang sama.
  
- ```href="http://www.google.com"```: Tautan eksternal ke situs web Google.

- Baris 10: Tag ```<hr>``` membuat garis horizontal sebagai pemisah visual.

**3. Konten Teks**

- Baris 12: ```<h1>``` adalah heading utama, digunakan untuk judul yang paling penting.

- Baris 13-17: Tag ```<p>``` mendefinisikan sebuah paragraf.

- ```align="center"```: Atribut untuk menengahkan teks.

- ```<mark>```: Memberikan sorotan pada teks (seperti stabilo).

- ```<b>```: Membuat teks menjadi tebal (bold).

- ```<i>```: Membuat teks menjadi miring (italic).

- Baris 19-22: Terdapat paragraf lain dengan heading ```<h2>``` yang berisikan contoh penggunaan tag ```<br>``` (break). Tag ini berfungsi untuk membuat baris baru tanpa memulai paragraf baru.

**4. Menampilkan Gambar**

- Baris 24: ```<h3>``` adalah heading untuk bagian "Menampilkan foto".

- Baris 25: Tag ```<img>``` digunakan untuk menyisipkan gambar. ```src="Logo upb (1).png": Atribut source yang menentukan lokasi file gambar```.

- ```width="200"```: Menentukan lebar gambar dalam piksel.

- ```title="Logo Universitas Pelita Bangsa"```: Menampilkan teks saat kursor diarahkan ke gambar.

- ```alt="Logo upb"```: Atribut alternative text yang penting untuk aksesibilitas, menjelaskan gambar jika tidak dapat dimuat atau untuk pembaca layar (screen reader).

# Tampilan Halaman 1
![foto](https://github.com/nanafnan09/Lab1Web/blob/0f170b5441ed26ea67ec136fc382fd84d1648bc7/tampilan%20halaman%201.png)

Difoto tersebut terdapat 3 tombol:

1.```Dasar HTML```, Yaitu tombol untuk mengakses tampilan awal

2.```Halaman 2```, Yaitu Tombol untuk mengakses tampilan kedua

3.```Akses Web Google```, Yaitu tombol untuk membuka google.com

# Tampilan Kode Halaman 2
![foto](https://github.com/nanafnan09/Lab1Web/blob/bf0c9e9271b1152f057f23b5810018bc27a97380/kode%20halaman%202.png)

**Penjelasan Kode HTML Dasar (Halaman 2)**

Kode ini adalah contoh halaman HTML yang lebih sederhana, berfungsi sebagai halaman lanjutan atau sub-halaman dari halaman utama.


**1. Struktur Halaman  Dasar**

- Baris 1-4, 13: Seperti pada kode sebelumnya, tag ```<html>``` dan <head> menjadi struktur utama.

- Baris 3: Tag ```<title>``` di sini adalah Halaman 2, menandakan identitas halaman di tab browser.

- Baris 5, 8: Tag <body> berisi semua konten yang dapat dilihat oleh pengguna.

**2. Konten Teks**

- Baris 6: Tag ```<h1>``` menampilkan judul utama halaman, "Tag Dasar Halaman 2".

- Baris 7: Tag ```<p>``` mendefinisikan sebuah paragraf.

- Tag ```<mark>``` memberikan sorotan visual pada teks, mirip seperti stabilo.

- Tag ```<ins>``` (inserted text) menampilkan teks dengan garis bawah (underline), yang secara semantik menandakan bahwa teks tersebut telah ditambahkan.

**3. Navigasi dan Pemisah**

- Baris 9: Tag ```<hr>``` membuat garis horizontal sebagai pemisah visual, memisahkan konten utama dari bagian navigasi.

- Baris 10-12: Tag ```<nav>``` adalah bagian navigasi.

- Baris 11: Tag ```<a>``` (anchor) digunakan untuk membuat tautan kembali ke halaman utama, dengan atribut href yang mengarah ke file ```lab1_tag_dasar.html. Teks``` "Beranda" berfungsi sebagai label tautan.

# Tampilan Halaman 2
![foto](https://github.com/nanafnan09/Lab1Web/blob/bf0c9e9271b1152f057f23b5810018bc27a97380/tampilan%20halaman%202.png)

Berikut pada halaman 2


# Soal
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

2. Apa perbedaan dari tag ```<p>``` dengan tag ```<br>```, berikan penjelasannya!

3. Apa perbedaan atribut title dan alt pada tag ```<img>```, berikan penjelasannya!

4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ```( _blank, _self, _top,
_parent )```, apa yang terjadi pada masing-masing nilai antribut tersebut?

# Jawaban
1.```HTML``` dirancang untuk "memaafkan" kesalahan penulisan tag. Browser modern akan mencoba mengoreksi atau mengabaikan tag yang salah,sehingga tidak ada error yang muncul di layar seperti pada bahasa pemrograman.Kesalahan biasanya hanya memengaruhi tampilan dan dapat dilihat di Developer Tools browser.

2. Perbedaan ```<p>``` dengan ```<br>```
 ```<p>```Paragraf=Digunakan untuk membuat blok teks baru yang secara visual terpisah (ada spasi di atas dan bawahnya). Ini adalah elemen blok.

```<br>```Line Break=Digunakan untuk membuat baris baru di dalam satu blok teks yang sama, mirip dengan menekan "Enter". Ini adalah elemen kosong.

3. Perbedaan Atribut ```title```dan```alt```
```alt```(Alternate Text): Atribut penting untuk aksesibilitas dan SEO. Teks ini ditampilkan jika gambar gagal dimuat atau dibaca oleh pembaca layar.

```title``` (Title Text): Memberikan informasi tambahan yang muncul sebagai tooltip saat kursor diarahkan ke gambar.

4.Mengatur Ukuran Gambar (```width``` & ```height```)
Sebaiknya hanya isi salah satu atribut (```width``` atau ```height```). Browser akan secara otomatis menghitung atribut lainnya agar gambar tetap proporsional dan tidak terdistorsi. 
Jika Anda mengisi keduanya, gambar mungkin terlihat pipih atau lonjong.

5.Nilai Atribut ```target``` pada Link
Atribut ```target``` menentukan di mana tautan dibuka:

```_blank```: Membuka di tab baru.

```_self```: (Default) Membuka di jendela yang sama.

```_parent```: Membuka di frame induk (jarang digunakan).

```_top```: Membuka di seluruh jendela browser, menghapus semua frame (jarang digunakan).




