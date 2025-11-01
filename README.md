# Panduan Instalasi dan Konfigurasi VM di Proxmox

Dokumentasi ini berisi panduan lengkap untuk menginstal dan mengonfigurasi **VM di Proxmox**, dengan 2 opsi sistem operasi: **Windows** dan **Linux**.  
Pilih panduan sesuai OS yang ingin digunakan.

---

## 🔹 Pilihan 1: Windows

1. **Install Windows 11**  
   Lihat [install.md](./windows/install.md) untuk panduan instalasi step-by-step.

2. **Konfigurasi Pasca-Instalasi**  
   Lihat [konfigurasi.md](./windows/konfigurasi.md) untuk pengaturan jaringan, driver, RDP, dan QEMU Guest Agent.

3. **Proxmox VM Configuration**  
   Lihat [proxmox-config.md](./windows/proxmox-config.md) untuk pengaturan hardware VM, ISO, VirtIO, dan opsi tambahan.

---

## 🔹 Pilihan 2: Linux

1. **Install Linux**  
   Lihat [install.md](./linux/install.md) untuk panduan instalasi distribusi Linux yang diinginkan (misal Ubuntu/Debian).

2. **Konfigurasi Pasca-Instalasi**  
   Lihat [konfigurasi.md](./linux/konfigurasi.md) untuk pengaturan jaringan, user, firewall, dan tools tambahan.

3. **Proxmox VM Configuration**  
   Lihat [proxmox-config.md](./linux/proxmox-config.md) untuk pengaturan hardware VM, ISO, disk, dan optimasi kinerja VM.

---

## ⚡ Tips Umum

- Pastikan **VM dalam keadaan mati** sebelum mengubah konfigurasi hardware di Proxmox.  
- Gunakan **VirtIO drivers** untuk Windows agar performa storage dan network optimal.  
- Selalu buat **snapshot** sebelum melakukan instalasi atau konfigurasi besar.  
- Untuk akses jarak jauh, aktifkan **RDP (Windows)** atau **SSH (Linux)**.  

---