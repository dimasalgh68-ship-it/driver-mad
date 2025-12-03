<h1>Driver Mad — Web Game (HTML, CSS, JS)</h1>
![driver](./mobil.png
)
Driver Mad adalah game mobil sederhana berbasis HTML, CSS, dan JavaScript, di mana pemain harus melewati rintangan dengan mengontrol tinggi suspensi mobil. Tantangannya adalah timing, stabilitas, dan kemampuan membaca bentuk obstacle.

Game ini terinspirasi dari mekanik “Driver Mad” versi mobile, tapi dibuat ulang (fan-made) dengan teknologi web tanpa engine tambahan.

🎮 Gameplay (Logika Inti)

Secara logis, game ini bekerja seperti ini:

Mobil berjalan otomatis ke depan.

Pemain hanya mengontrol naik/turun suspensi (atau tinggi roda).

Rintangan muncul di depan dengan ketinggian dan jarak berbeda.

Pemain harus menyesuaikan tinggi mobil agar tidak menabrak obstacle.

Jika mobil menyentuh obstacle → Game Over.

Semakin jauh melaju → skor meningkat.

Mekanik sederhana, tetapi bergantung pada timing dan konsistensi.

✨ Fitur

Kontrol suspensi mobil yang halus

Sistem collision sederhana berbasis bounding box

Level atau rintangan random-generated

Efek animasi mobil naik / turun

Skor berbasis jarak tempuh

UI game over + tombol restart

Berjalan 100% pada browser tanpa server

🕹 Kontrol

Click / Tap / Space / W → naikkan suspensi

Lepaskan → turunkan suspensi

(ubah sesuai implementasi kode kamu — tinggal bilang kalau mau disesuaikan)

🚗 Cara Menjalankan

Clone atau download repo:

git clone https://github.com/yourusername/driver-mad.git
cd driver-mad


Jalankan:

Klik dua kali index.html

Atau jalankan local server:

python -m http.server 8000


Mainkan di browser:
http://localhost:8000
