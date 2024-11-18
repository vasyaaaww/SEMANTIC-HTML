# SEMANTIC-HTML
Latihan Praktikum Semantic HTML


## Semantic HTML Project 
Perbedaan yang terdapat pada kedua kode HTML, sebagai berikut:
1. Struktur Dasar HTML <br>
   Kode pertama tidak ada elemen `<html>`,`<head>`, atau `<body>` sedangkan kode kedua memiliki struktur dasar HTML yang lengkap.
2. `<html>` dan `lang` <br>
   Kode kedua menggunakan <html> dengan atribut `lang=en` yang menunjukkan artikel ini menggunakan bahasa Inggris.
3. `<head>` <br>
   Kode pertma tidak menggunakan <head> sedangkan kode kedua menggunakan <head> yang berisi meta tag untuk karakter set dan viewport,       serta judul halaman dan link ke stylesheet eksternal.
4. Meta Tag <br>
  Kode kedua menggunakan meta tag `<meta charset="UTF-8">` untuk menentukan pengkodean karakter dan `<meta name="viewport"       
  content="width=devie_width, initial-scale=1.0">` untuk reponsivitas. sedangkan pada kode pertama tidak ada.
5. Link ke Stylesheet <br>
   Kode kedua menggunakan link ke CSS eksternal `linkrel="stylesheet" href="./assets/styles/styles.css">` untuk styling. Sedangkan pada     kode pertama tidak ada.
6. Kesalahan pada Kode Pertama <br>
   pada kode pertama terdapat kesalahan `<section>` yang ditutup tidak benar. ada pun teks `Konten` yang muncul diluar `<section>` yang     seharusnya tidak ada.
7. Tata Letak dan Semantik <br>
   Kode pertama tidak terorganisir dengan baik, sedangka kode kedua lebih semantic dan terstruktur dengan baik, mengikuti standar           html5.


## Perbedaan pada styles.css
1. Penulisan <br>
   Kode pertama menuliskan aturan untu `nav`, `header`, 'section', dan `footer` terlebih dahulu,diikuti oleh aturan untuk `body`.           Sedangkan Kode Kedua membalikkan urutan, dengan aturan `body` ditulis terlebih dahulu, diikuti oleh aturan `header`, `nav`,              `section`, dan `footer`.
2. Fungsi <br>
   Kedua kode CSS ini mendapatkanhasil yang sama dalam hal tata letak dan styling. urutan penulisan tidak mempengaaruhi hasil akhir jika    tidak ada konflik aturan CSS. 
