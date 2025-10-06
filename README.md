Weather App
Weather App Demo

Deskripsi
Weather App adalah aplikasi web modern yang dibangun menggunakan React.js untuk memantau cuaca real-time di seluruh dunia. Aplikasi ini mengintegrasikan API OpenWeatherMap untuk mendapatkan data cuaca terkini, prakiraan 5 hari ke depan, dan informasi detail seperti suhu, kelembaban, angin, serta deskripsi cuaca.

Fitur Utama:

Halaman Selamat Datang (MainMenu): Antarmuka sederhana dengan animasi untuk navigasi ke app cuaca.
Pencarian Cuaca: Cari cuaca berdasarkan nama kota atau lokasi saat ini (geolocation).
Tampilan Cuaca Saat Ini: Suhu, ikon cuaca, sensasi suhu, kelembaban, dan kecepatan angin.
Prakiraan Cuaca: Forecast harian untuk 5 hari ke depan dengan ikon dan suhu.
Tema Light/Dark Mode: Switch tema secara otomatis berdasarkan preferensi browser atau manual.
Unit Suhu: Toggle antara Celsius (°C) dan Fahrenheit (°F).
Efek Visual: Gradient background dinamis berdasarkan kondisi cuaca, efek hujan saat cuaca hujan, dan animasi halus dengan Framer Motion.
Routing & Error Handling: Navigasi dengan React Router, halaman 404 custom bertema cuaca.
Responsive Design: Optimal untuk desktop dan mobile menggunakan Tailwind CSS.
Aplikasi ini dirancang untuk user-friendly, cepat, dan estetis, cocok untuk project kuliah atau demo portofolio.

Demo
Aplikasi ini telah dideploy dan bisa diakses secara live di:
(https://github.com/kyy-sr/weather-web)


Cara Akses Demo:

Buka link di atas.
Di halaman utama, klik "Mulai Cek Cuaca".
Search kota (misal: "Jakarta") atau klik "My Location" untuk lokasi sekarang.
Switch tema atau unit suhu untuk test fitur.
(Tambahkan screenshot di sini jika ingin: Screenshot)

Cara Install dan Menjalankan
Prasyarat
Node.js (versi 14+ direkomendasikan) dan npm/yarn terinstall.
Akun OpenWeatherMap untuk API key (gratis, daftar di openweathermap.org).
Langkah-langkah
Clone Repository:


Run
Copy code
git clone https://github.com/yourusername/weather-app.git
cd weather-app
Install Dependencies:


Run
Copy code
npm install
(Atau yarn install jika pakai Yarn. Ini akan install React, React Router, Framer Motion, Axios, React Icons, Tailwind CSS, dll.)

Setup API Key:

Buat file .env di root project (jangan commit ke Git).
Tambahkan: REACT_APP_API_KEY=your_openweathermap_api_key_here.
Ganti YOUR_API_KEY di src/components/WeatherHome.js dengan process.env.REACT_APP_API_KEY (untuk keamanan).
Jalankan Aplikasi:


Run
Copy code
npm start
App akan terbuka di http://localhost:3000.
Test: Akses / (MainMenu), /weather (app cuaca), atau URL salah untuk 404.
Build untuk Production (untuk deploy):


Run
Copy code
npm run build
Folder build/ siap di-deploy ke GitHub Pages, Vercel, atau Netlify.
Troubleshooting
Error API: Pastikan API key valid dan kota diketik benar (e.g., "Jakarta, ID").
Putih di Bawah: Pastikan Tailwind CSS terinstall dan src/index.css di-update seperti di repo.
Geolocation Error: Izinkan akses lokasi di browser.
Jika error lain, cek console browser (F12) atau jalankan npm audit fix.
Dependencies
React: ^18.2.0
React Router DOM: ^6.8.0 (routing)
Framer Motion: ^10.12.0 (animasi)
Axios: ^1.4.0 (API fetch)
React Icons: ^4.10.1 (ikon cuaca)
Tailwind CSS: ^3.3.0 (styling)
Lihat package.json untuk versi lengkap.

Daftar Anggota Kelompok
Project ini dikembangkan oleh tim berikut 

 M.keysar

 Agus hildan

 Rizki aditiya

 Suryo handoko

 Faiz 
