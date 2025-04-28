
WePOS - Cafe v.3.42.22
Updated: 07-01-2021 01:00:00

Cocok untuk:
Cafe/Resto/Rumah Makan (semua penjualan berbasis Cafe)

Aplikasi ini menggunakan:
- Codeigniter 3.1.13 | https://www.codeigniter.com/ | MIT License
- ExtJS 4.2 GPL v.3 | sencha.com | GPL v3 (source bisa dilihat di folder "assets\js\extjs.4.2")
- JQuery v1.7.1 jquery.com | jquery.org | MIT License
- Database MySQL GPL v2

untuk versi Retail/Toko: https://github.com/copolatoz/wepos-retail

*aplikasi ini berisi modul-modul standar untuk sistem cafe/resto 
*untuk modul lengkap silahkan daftarkan merchant/cafe/resto untuk mendapatkan merchant-key di wepos.id

#Cara Instalasi Aplikasi:
1. Install XAMPP 5.5.24 atau 5.6.32
2. copy-paste folder hasil download aplikasi 'wepos-cafe' ke xampp/htdocs/

	#copy dan rename file:
	1. copy index.php.org --> index.php
	2. copy .htaccess.org --> .htaccess (edit isi file, sesuaikan dengan nama folder)

	#folder /applications/config 
	1. copy app_config.php.org --> app_config.php
	2. copy config.php.org --> config.php
	3. copy database.php.org --> database.php (edit isi file, sesuaikan dengan nama database)

	#import database: db/database_wepos_free.sql
	1. akses ke http://localhost/phpmyadmin
	2. buat database baru misal: wepos-cafe
	3. import db/database_wepos_cafe.sql


3. run di browser sesuai nama folder yang digunakan, default: http://localhost/wepos

	#Mengganti URL menjadi http://localhost/nama-cafe-anda
	1. ganti nama folder download 'wepos-cafe' menjadi 'nama-cafe-anda'
	2. ubah isi/text pada file .htaccess 'wepos-cafe' menjadi 'nama-cafe-anda'
		*jika .htaccess tidak ditemukan, ubah settingan folder anda agar dapat melihat hidden file dan ekstensi file
		*gunakan editor semisal notepad++ untuk save-as atau membuat/edit file .htaccess
	
	#integrasi dengan WePOS.Cashier - Android Browser:
	1. Install Aplikasi RawBT
	2. Setup Setingan printer di RawBT
        3. Setup Printer di Aplikasi WePOS dengan tipe "Android" 


4. untuk setup printer Thermal -> silahkan download extension PHP di website wepos.id atau bisa google "printer extension untuk php 5.6"



Team WePOS ^^
contact@wepos.id 







