# SEMANTIC-HTML.
Latihan Praktikum 1 Semantic HTML

AGUS RUDI SETIAWAN_2205101089

## Tag <html> dan <body>
1. Codingan 1:
Tidak menyertakan tag <html> atau <body>. Struktur halaman dimulai langsung dengan <header>, sehingga tidak memenuhi standar HTML5.
2. Codingan 2:
Menggunakan tag <html> dengan atribut lang="en" untuk menunjukkan bahasa halaman adalah bahasa Inggris, serta tag <body> yang membungkus seluruh elemen halaman (seperti <header>, <nav>, <section>, dan <footer>).

## Tag <head>
1. Codingan 1:
Tidak memiliki tag <head>, sehingga elemen penting seperti metadata dan referensi ke file CSS eksternal tidak disertakan.
2. Codingan 2:
Menyertakan tag <head> dengan beberapa elemen utama:
•	<meta charset="UTF-8">` untuk menentukan encoding karakter yang digunakan,
•	<meta name="viewport" content="width=device-width, initial-scale=1.0">` untuk mendukung tampilan responsif pada perangkat seluler,
•	<title>HTML5 Semantic</title>` sebagai judul halaman, dan
•	<link rel="stylesheet" href="./assets/styles/styles.css">` untuk menghubungkan file CSS eksternal.

## Penutupan Tag
1. Codingan 1:
Tidak memiliki tag penutup </html> atau </body>, membuat struktur kurang lengkap dan tidak sesuai standar HTML5.
2. Codingan 2:
Menggunakan penutupan tag yang lengkap (</html> dan </body>), menjadikannya lebih sesuai dengan standar HTML5.

## Atribut lang="en" pada Tag <html>
1. Codingan 1:
Tidak menambahkan atribut lang pada tag <html>.
2. Codingan 2:
Menambahkan lang="en" pada tag <html>, yang memberikan informasi kepada mesin pencari dan pembaca layar bahwa halaman ini berbahasa Inggris.

## Penyusunan Struktur Halaman
1. Codingan 1:
Struktur HTML sederhana, terdiri dari elemen-elemen dasar seperti <header>, <nav>, <section>, dan <footer>, tanpa tag <head> dan <body>.
2. Codingan 2:
Memiliki struktur HTML yang lebih lengkap dengan tag <head> dan <body>, mengikuti praktik pengkodean HTML5 yang baik.

## Properti CSS grid-template-columns
1. Codingan 1:
  css
  	grid-template-columns: 20% 1fr 18;
  
Pengaturan lebar kolom grid di sini menggunakan nilai 20%, 1fr, dan 18 tanpa satuan yang tepat, yang bisa dianggap tidak valid atau menghasilkan tata letak yang salah.
2. Codingan 2:
 	 css
 	 grid-template-columns: 20% 1fr 18%;
 	 
Lebar kolom ketiga ditulis dengan satuan yang benar, yaitu 18%, yang memastikan semua kolom memiliki ukuran yang valid.

## Properti margin pada <body>
1. Codingan 1:
Tidak ada margin yang diterapkan pada elemen <body>.
2. Codingan 2:
Menyertakan margin: 10px; pada elemen <body>, memberikan jarak antara batas konten dan tepi jendela browser.

## Kesalahan Penulisan Selector pada Footer di Codingan 1
1. Codingan 1:
Kesalahan terjadi pada penulisan selector CSS untuk elemen footer, yaitu I footer { ... }. Huruf "I" sebelum tag footer tidak diperlukan dan menyebabkan aturan CSS tidak diterapkan dengan benar.
2. Codingan 2:
Selector ditulis dengan benar sebagai footer { ... }, sehingga aturan CSS akan berlaku pada elemen foote
