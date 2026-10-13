<p align="center">
  <img src="assets/logo-pens.png" alt="Logo PENS" width="150">
</p>

<h1 align="center">Laporan Praktikum DevOps</h1>

<p align="center">
  <strong>Politeknik Elektronika Negeri Surabaya (PENS)</strong><br>
  Dokumentasi laporan praktikum DevOps yang disusun dalam format Markdown
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown">
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="NGINX">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

---

## 📋 Daftar Laporan

| No. | Materi | Dokumentasi |
|-----|--------|-------------|
| 1 | Fondasi Teoretis dan Kerangka Kerja DevSecOps | [📄 Buka Laporan](laporan/bab-01-fondasi-teoretis-devsecops.md) |
| 2 | Konsep Container dan Instalasi Docker | [📄 Buka Laporan](laporan/bab-02-konsep-container-instalasi-docker.md) |
| 3 | Docker Network, Volume, Bind Mount, Tmpfs dan Compose | [📄 Buka Laporan](laporan/bab-03-docker-network-volume-compose.md) |
| 4 | Nginx, Apache, Flask, dan TLS dengan Docker Compose | [📄 Buka Laporan](laporan/bab-04-nginx-apache-tls-docker-compose.md) |
| 5 | PostgreSQL, pgAdmin, Volume, Backup, dan Restore | [📄 Buka Laporan](laporan/bab-05-postgresql-pgadmin-volume-backup-restore.md) |

---

## 🗂️ Struktur Repository

```
laporan-praktikum-devops/
├── README.md
├── .gitignore
├── laporan/
│   ├── bab-01-fondasi-teoretis-devsecops.md
│   ├── bab-02-konsep-container-instalasi-docker.md
│   ├── bab-03-docker-network-volume-compose.md
│   ├── bab-04-nginx-apache-tls-docker-compose.md
│   └── bab-05-postgresql-pgadmin-volume-backup-restore.md
└── assets/
    ├── logo-pens.png
    ├── bab-01/
    ├── bab-02/
    ├── bab-03/
    ├── bab-04/
    └── bab-05/
```

---

## 🛠️ Teknologi

| Teknologi | Deskripsi |
|-----------|-----------|
| **Docker** | Platform containerisasi untuk menjalankan dan mengelola container |
| **Linux / Ubuntu 22.04 LTS** | Sistem operasi untuk environment praktikum pada VM Proxmox |
| **NGINX** | Web server dan reverse proxy dengan terminasi TLS |
| **PostgreSQL** | Sistem manajemen basis data relasional open-source |
| **pgAdmin** | Alat administrasi dan manajemen PostgreSQL berbasis web |
| **Git & GitHub** | Sistem kontrol versi dan platform kolaborasi kode |
| **Markdown** | Format penulisan dokumentasi laporan |

---

## 📝 Isi Dokumentasi

Setiap laporan berisi penjelasan mengenai:

- ✅ **Lingkungan Kerja** — Spesifikasi VM, sistem operasi, dan tools yang digunakan
- ✅ **Langkah Kerja** — Perintah terminal yang dijalankan beserta penjelasannya
- ✅ **Konfigurasi** — File konfigurasi yang digunakan (Docker Compose, NGINX, dll.)
- ✅ **Bukti Pelaksanaan** — Screenshot terminal dan hasil eksekusi
- ✅ **Hasil Pengujian** — Verifikasi dan skenario pengujian
- ✅ **Evaluasi** — Analisis, kesimpulan, dan jawaban latihan mandiri

---

## 🖥️ Environment Praktikum

```
Platform   : Proxmox VE (Virtual Machine)
OS         : Ubuntu Linux 22.04 LTS
Arsitektur : linux/amd64
Hostname   : ubn-2
User       : ubuntu-2
IP Address : 10.252.108.103
```

---

## ⚠️ Catatan

Repository ini dibuat untuk keperluan dokumentasi pembelajaran dan praktikum DevOps.  
Isi laporan disesuaikan dengan pelaksanaan praktikum yang sebenarnya.  
Seluruh credential, password, dan token yang muncul dalam screenshot bersifat **dummy/lab** dan tidak digunakan di lingkungan produksi.
