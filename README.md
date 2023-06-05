# LapKI_RivaMahyuli_478709_Pertemuan12

# Web Dynamic Pentest menggunakan Nessus
Pada pratikum ini kita menggunakan Nessus untuk memindai vulnerability di suatu website. Setelah melakukan instalasi Nessus kita akan melakukan analisis 
pada setiap web yang yang kita pindai untuk memeriksa kerentanan pada web tersebut.
Beberapa Web yang akan di pindai :
1. Metasploitable 
2. UltimateLAMP
3. Dojo keamanan web
4. Mutillidae
5. De-ICE
6. Kambing web OWASP
7. Google gruyere
8. Hackdemik Owasp

# 1. Analisis Metasploitable
![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/38420335-7668-4309-abda-46a120d642fb)

pada gambar diatas kita bisa melihat dari web Metasploitable terdapat kerentanan dengan tingkat keparahan 'mixed' ini menunjukkan bahwa kerentanan yang ditemukan memiliki potensi serius untuk dimanfaatkan oleh penyerang, tetapi mungkin memerlukan kondisi khusus atau akses yang lebih terbatas untuk mengeksploitasinya. 
"Info" pada laporan Nessus merujuk pada temuan informasi yang relevan, tetapi bukan kerentanan yang kritis atau serius. Meskipun informasi ini mungkin tidak langsung berdampak pada keamanan, tetapi tetap penting untuk diketahui.

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/e930a34d-5e75-4a6d-8cf9-60ff26b7aab4)

kerentanan yang ditemukan memiliki deskripsi "HSTS Missing from HTTPS Server" atau "HSTS Tidak Ada pada Server HTTPS". HSTS (HTTP Strict Transport Security) adalah kebijakan yang diimplementasikan oleh server untuk memaksa klien (browser) selalu berkomunikasi melalui HTTPS dengan server tersebut. Jika kebijakan ini tidak diatur dengan benar pada server HTTPS, maka ada potensi kerentanan dalam pengiriman data yang tidak terenkripsi melalui protokol HTTP.

# 2. Analisis UltimateLAMP

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/d4a40d7c-d229-4726-9c4f-8886346de3da)

pada web ini terdapat banyak kerentanan dengan tingkat keparahan yang berbeda
yaitu mixed, medium, dan high

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/b195d06e-f072-4b86-a16f-6e064a87288e)

Kerentanan ini mengindikasikan bahwa ada celah dalam aplikasi web yang memungkinkan penyerang untuk menjalankan perintah (command) pada sistem yang menjalankan aplikasi tersebut. Sebagai contoh, penyerang dapat memanipulasi input pada URL atau parameter permintaan HTTP untuk menjalankan perintah yang tidak diizinkan atau berbahaya di server. Level keparahan "high" menunjukkan bahwa kerentanan tersebut memiliki potensi risiko yang tinggi dan dapat dieksploitasi dengan relatif mudah. 

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/c3dd73f4-46d7-46d5-b4dd-506b31e1ff1c)

JQuery 1.2 < 3.5.0 Multiple XSS  mengindikasikan bahwa ada kerentanan potensial terkait keamanan lintas situs (Cross-Site Scripting, XSS) dalam versi jQuery 1.2 hingga 3.5.0. medium" menunjukkan bahwa kerentanan ini memiliki tingkat risiko yang signifikan, tetapi kemungkinan memiliki tingkat eksploitasi yang lebih rendah
Dilevel ini terdapat berbagai kerentanan seperti Browsable Web Directories, 
FlatNuke index.php id Parameter Traversal Arbitrary File Access, Backup Files Disclosure, Web Application Information Disclosure
# 3. Analisis  Dojo keamanan web

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/2ded4290-29d2-4106-88ce-78b33c1c78f2)

pada dojo keamanan web kerentanan yang ditemukan sama dengan web Metasploitable

# 4. Analisis Mutillidae

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/7ecf8976-f786-4c74-b0c1-0d4f7bd5bb84)

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/973f7480-cc6d-4215-8895-70972ce7177e)

 "Apple Mac OS X Find-By-Content .DS_Store Web Directory Listing" dengan level keparahan "Medium" dalam Nessus mengindikasikan adanya kerentanan terkait konfigurasi atau pengelolaan berkas .DS_Store pada sistem operasi Apple Mac OS X.

.DS_Store adalah sebuah berkas yang dibuat oleh sistem operasi Mac OS X untuk menyimpan informasi metadata dan pengaturan tampilan dalam sebuah direktori. Pada umumnya, berkas ini tidak seharusnya diakses melalui web karena berisi informasi yang hanya relevan pada tingkat lokal.

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/6fe6ab11-340c-4051-964d-a1439f23c7d2)

 "Web Server Uses Basic Authentication Without HTTPS" dengan level keparahan "Low" dalam Nessus mengindikasikan bahwa server web yang diperiksa menggunakan metode autentikasi dasar (basic authentication) tanpa menggunakan protokol HTTPS (HTTP Secure).

Basic authentication adalah metode autentikasi yang umum digunakan di web di mana kredensial pengguna (username dan password) dikirim dalam header permintaan HTTP. Namun, karena metode ini mengirimkan kredensial dalam teks biasa (plain text), tanpa pengamanan tambahan, penggunaan basic authentication tanpa HTTPS dapat menjadi risiko keamanan.

# 5. Analisis De-ICE
![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/c2e18507-9ea9-4585-9db7-e201e2612909)

pada De-ICE  kerentanan yang ditemukan sama dengan web Metasploitable dan dojo keamanan web

# 6. Analisis Kambing web OWASP
![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/c2a3f3ff-8b93-45ea-8311-eb8b07e76b27)

Pada web ini tidak terdapat kerentanan pada web hanya terdapat info yang  merujuk pada temuan informasi yang relevan, tetapi bukan kerentanan yang kritis atau serius. Meskipun informasi ini mungkin tidak langsung berdampak pada keamanan, tetapi tetap penting untuk diketahui.

# 7. Analisis Google gruyere
![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/13f82964-36ad-4d9a-ba87-ad2dd0f8df17)

Hasil "CGI Generic HTML Injections (quick test)" dengan level keparahan "Medium" dalam Nessus mengindikasikan adanya kerentanan terkait serangan HTML Injection pada skrip CGI (Common Gateway Interface) yang dieksekusi oleh server web.

HTML Injection (atau sering disebut juga sebagai "Cross-Site Scripting" atau XSS) adalah jenis serangan di mana penyerang menyisipkan kode HTML atau skrip berbahaya ke dalam halaman web yang kemudian dieksekusi oleh browser pengguna. Jika serangan ini berhasil, penyerang dapat memanipulasi tampilan halaman web, mencuri informasi pengguna, atau menjalankan tindakan yang tidak diinginkan.

Kerentanan "CGI Generic HTML Injections" menunjukkan bahwa ada celah dalam skrip CGI yang dieksekusi oleh server web, yang memungkinkan input pengguna tidak diolah dengan benar dan dapat menyebabkan injeksi HTML. Dalam hal ini, kerentanan tersebut diidentifikasi secara umum dan tidak spesifik terhadap satu skrip CGI tertentu.

![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/8d6f703c-4e4b-46d6-9c4b-8a7da1f92a2a)

Hasil "Web Server Transmits Cleartext Credentials" dengan level keparahan "Low" dalam Nessus mengindikasikan bahwa server web yang diperiksa mengirimkan kredensial pengguna dalam bentuk teks biasa (cleartext) melalui lalu lintas jaringan.

Kredensial pengguna seperti username dan password harus dijaga kerahasiaannya saat dikirimkan melalui jaringan. Namun, jika server web mengirimkan kredensial dalam bentuk teks biasa (cleartext) tanpa enkripsi atau perlindungan tambahan, maka informasi tersebut dapat dengan mudah dicuri oleh pihak ketiga yang mungkin memantau atau mencuri lalu lintas jaringan.

Level keparahan "low" menunjukkan bahwa kerentanan ini memiliki tingkat risiko yang rendah. Namun, meskipun risikonya rendah, penting untuk memperhatikan keamanan lalu lintas jaringan dan melindungi kredensial pengguna dari potensi pencurian.

# 8. Analisis Hackdemik Owasp
![image](https://github.com/RIVAMAHYULi/LapKI_RivaMahyuli_478709_Pertemuan12/assets/99727334/75a53e39-52db-49ee-9df8-8cd75cdd4802)

Hasil "Web Application Potentially Vulnerable to Clickjacking" dengan level keparahan "Medium" dalam Nessus mengindikasikan bahwa aplikasi web yang diperiksa mungkin rentan terhadap serangan Clickjacking.

Clickjacking adalah jenis serangan di mana penyerang menipu pengguna agar mengklik elemen yang tidak disadari di dalam halaman web. Serangan ini memanfaatkan kelemahan dalam cara halaman web di-render oleh browser. Penyerang dapat menyembunyikan elemen yang sebenarnya di dalam halaman web dan menampilkan elemen palsu yang menarik perhatian pengguna, yang kemudian mengakibatkan pengguna melakukan tindakan tanpa disadari.

Kerentanan "Potentially Vulnerable to Clickjacking" menunjukkan bahwa ada potensi bahwa aplikasi web dapat dieksploitasi oleh serangan Clickjacking. Namun, perlu diingat bahwa ini hanya merupakan peringatan potensial dan perlu dilakukan penelitian lebih lanjut untuk memverifikasi kerentanan tersebut.

Level keparahan "medium" menunjukkan bahwa kerentanan ini memiliki tingkat risiko yang signifikan, tetapi mungkin tidak se-serius kerentanan dengan level "high" atau "critical". Meskipun risikonya tidak sebesar kerentanan tingkat lebih tinggi, masih perlu diperbaiki untuk mencegah serangan Clickjacking yang dapat memanipulasi interaksi pengguna.
