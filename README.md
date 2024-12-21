Dokumentasi Proyek: Personal Portfolio Website
1. Deskripsi Proyek
Proyek ini adalah sebuah website portofolio pribadi yang dirancang untuk menampilkan informasi tentang Anggi Prasetyo, seorang IT Engineer. Website ini mencakup bagian profil, informasi kontak, tentang diri, dan keterampilan yang dimiliki.

2. Struktur Proyek
Proyek ini terdiri dari dua file utama:

index.html: File HTML yang berisi struktur dan konten website.
style.css: File CSS yang berisi gaya dan tata letak untuk website.
3. File HTML (index.html)
3.1. Struktur Dasar
html
Insert Code
Run
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio Website designing -K2inofocom</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
</head>
<body>
    <!-- Konten website -->
</body>
</html>
3.2. Konten Utama
Profil: Menampilkan foto, nama, jabatan, dan informasi kontak.
Tentang Saya: Deskripsi singkat tentang latar belakang dan keterampilan.
Keterampilan: Menampilkan keterampilan yang dimiliki dalam bentuk kotak kerja.
3.3. Contoh Kode
html
Insert Code
Run
Copy code
<div class="profile-card"> 
    <div class="profile-pic">
        <img src="images/avatar.webp" alt="user avatar">
    </div>
    <div class="profile-details">
        <div class="intro">
            <h2>Anggi Prasetyo</h2>
            <h4>IT Engineer</h4>
            <span>Ready To Work</span>
            <div class="social">
                <a href="https://www.facebook.com/El.SiggMonteCarlo/" target="_blank"><i class="fab fa-facebook"></i></a>
                <a href="https://www.instagram.com/agprsss_/" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://discordapp.com/users/368012362609065985" target="_blank"><i class="fab fa-discord"></i></a>
                <a href="https://www.linkedin.com/in/anggiiprasetyo/" target="_blank" rel="noopener noreferrer"><i class="fab fa-linkedin"></i></a>
            </div>
        </div>
        <button class="download-btn">
            <a href="CV_Anggi Prasetyo.pdf" download target="_blank">LIHAT CV</a>
        </button>
    </div>
</div>
4. File CSS (style.css)
4.1. Variabel CSS
Menggunakan variabel CSS untuk mendefinisikan warna yang digunakan di seluruh website.

css
Insert Code
Run
Copy code
:root {
    --purple: #2F192E;
    --skyblue: #00b4fc;
    --dark-blue: #012677;
    /* Variabel lainnya */
}
4.2. Gaya Umum
Menetapkan gaya umum untuk elemen di website.

css
Insert Code
Run
Copy code
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
    text-decoration: none;
    font-family: poppins, sans-serif;
}
body {
    background: linear-gradient(45deg, var(--skyblue), var(--dark-blue));
}
4.3. Gaya Khusus untuk Elemen
Menetapkan gaya khusus untuk elemen seperti tombol, profil, dan bagian tentang.

css
Insert Code
Run
Copy code
.profile-card {
    background: #111;
    color: #fff;
    /* Gaya lainnya */
}
.download-btn {
    background: linear-gradient(45deg, #f64c57, #e21b5a);
    color: #ffffff;
    /* Gaya lainnya */
}
5. Responsivitas
Website ini dirancang responsif dengan menggunakan media query untuk menyesuaikan tampilan pada perangkat dengan lebar layar yang lebih kecil.

css
Insert Code
Run
Copy code
@media(max-width:768px) {
    .about {
        max-width: 400px;
        padding: 1rem;
    }
}
6. Cara Menjalankan Proyek
Pastikan Anda memiliki server lokal seperti XAMPP atau WAMP.
Tempatkan folder proyek di dalam direktori htdocs (untuk X AMPP) atau www (untuk WAMP).
7. Fitur Tambahan
Integrasi Media Sosial: Tautan ke profil media sosial untuk meningkatkan konektivitas.
Download CV: Pengguna dapat mengunduh CV dalam format PDF dengan mengklik tombol "LIHAT CV".
8. Kesimpulan
Proyek ini adalah contoh sederhana dari website portofolio pribadi yang dapat digunakan untuk menampilkan informasi dan keterampilan. Dengan menggunakan HTML dan CSS, proyek ini dapat dengan mudah dikembangkan lebih lanjut dengan menambahkan fitur-fitur baru atau memperbaiki desain.
