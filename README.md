# Lab9Web

# PHP Modular

Nama : Dhea Dwi Adelia

NIM : 312210116

Kelas : TI.22.A.1


# Instruksi Praktikum

1. Persiapkan text editor misalnya VSCode.

2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)
   
3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

# Langkah-Langkah Praktikum

1. Buat file baru dengan nama header.php

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <title>Contoh Modularisasi</title>
            <link href="style.css" rel="stylesheet" type="text/stylesheet"
        media="screen" />
        </head>
        <body>
            <div class="container">
                <header>
                    <h1>Modularisasi Menggunakan Require</h1>
                </header>
                <nav>
                    <a href="home.php">Home</a>
                    <a href="about.php">Tentang</a>
                    <a href="kontak.php">Kontak</a>
                </nav>

![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/ab9fd1e2-82aa-4ccc-9e3d-0418342b07b8)


2. Buat File baru dengan nama footer.php

               <footer>
                  <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
               </footer>
            </div>
         </body>
         </html>

   ![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/d2155dc4-1d4f-46cb-80dc-7da051eea52c)


4. Buat file baru dengan nama home.php

         <?php require('header.php'); ?>
         <div class="content">
            <h2>Ini Halaman Home</h2>
            <p>Ini adalah bagian content dari halaman.</p>
         </div>
         <?php require('footer.php'); ?>

   ![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/d373b1cb-5078-4f39-be91-7d7c367f47fe)


6. Buat file baru dengan nama about.php

         <?php require('header.php'); ?>
         <div class="content">
            <h2>Ini Halaman About</h2>
            <p>Ini adalah bagian content dari halaman.</p>
         </div>
         <?php require('footer.php'); ?>

![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/72ca7407-7fed-45d4-849a-1c89de481f3b)

  
# Pertanyaan dan Tugas

Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/1b3119fd-d66d-4e39-9bf2-abb642ffe8e9)

![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/e5424230-ffab-4267-b721-d391a5cef660)

![image](https://github.com/adeliadhea06/Lab9Web/assets/115794875/e4cced45-9ba7-48c4-82db-a6c7a7ac6149)


# Sekian dan Terima Kasih
