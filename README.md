# Web Server Container – Website Statis Kampus

## Deskripsi Proyek
Proyek ini merupakan tugas Ujian Akhir Semester mata kuliah Praktik Sistem Operasi.
Tujuan dari proyek ini adalah menerapkan konsep containerisasi menggunakan Docker
dengan membuat web server statis berbasis Nginx yang dapat diakses melalui browser.

Website dijalankan di dalam container Docker sehingga aplikasi bersifat portabel,
ringan, dan terisolasi dari sistem operasi host.

KELOMPOK 1
## Anggota Kelompok
- Budi Sanjaya (062430701442)
- M. Vikra Pratama (062430701442)


## Teknologi yang Digunakan
- Docker
- Docker Compose
- Nginx
- HTML
- CSS


## Struktur Direktori
web-docker/
─ Dockerfile
─ docker-compose.yml
─ index.html
─ style.css
─ README.md


## Cara Instalasi
1. Install Docker Desktop
2. Pastikan Docker sudah berjalan
3. Clone atau download repository proyek
4. Masuk ke folder proyek


## Cara Menjalankan Aplikasi

Menggunakan Docker Compose:
docker compose up -d

Menggunakan Docker (alternatif):
docker build -t web-kampus .
docker run -d -p 8080:80 web-kampus


## Port Mapping
Aplikasi menggunakan port mapping sebagai berikut:
- Port 8080 pada host
- Port 80 pada container


## Akses Website
Buka browser dan akses:
http://localhost:8080


## Kesimpulan
Dengan menggunakan Docker, web server statis dapat dijalankan secara terisolasi
tanpa perlu menginstal web server langsung pada sistem operasi. Proyek ini
menunjukkan penerapan konsep container, volume, dan network pada Docker.
