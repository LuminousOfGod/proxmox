# Panduan Instalasi Windows 11 di Proxmox

Dokumentasi ini menjelaskan langkah-langkah instalasi Windows 11 pada VM Proxmox, mulai dari persiapan media boot, konfigurasi instalasi, hingga instalasi driver.

---

## 1. Persiapan Media Boot

1. **Tekan tombol saat console sedang loading** untuk melakukan boot dari **CD/DVD**.  
   ![](./image/console.png)

2. **Jika terlambat**, akan masuk ke **Boot Management**.  
   Pilih **Boot Manager**, lalu tekan **Enter**.  
   ![](./image/console-1.png)

3. Setelah masuk, **tekan Enter** untuk memulai booting dari **CD/DVD**.  
   Pastikan untuk menekan **Enter** kembali jika muncul tampilan seperti langkah 1.  
   ![](./image/console-2.png)

4. Jika berhasil, Anda akan melihat tampilan instalasi Windows 11 berikut:  
   ![](./image/install.png)

---

## 2. Pengaturan Awal Instalasi

1. **Pilih bahasa, format waktu, dan pengaturan regional** sesuai kebutuhan.  
   ![](./image/install-2.png)

2. **Atur pengaturan keyboard** sesuai preferensi Anda.  
   ![](./image/install-3.png)

3. Pilih **Install Windows 11**.  
   ![](./image/install-4.png)

4. Pilih **ISO Windows 11** yang ingin diinstal (dalam contoh ini menggunakan versi PRO).  
   ![](./image/install-5.png)

5. **Setujui perjanjian lisensi Windows 11**.  
   ![](./image/install-6.png)

---

## 3. Instalasi Driver

1. Jika disk kosong muncul, pilih **Load Driver**.  
   ![](./image/install-7.png)

2. Pilih **Browse**.  
   ![](./image/install-8.png)

3. Cari **CD Drive VirtIO**, lalu pilih folder **amd64**.  
   ![](./image/install-9.png)

4. Pilih folder **w11**, lalu klik **Ok**.  
   ![](./image/install-10.png)

5. Driver akan muncul seperti pada gambar, pilih driver tersebut lalu klik **Install**.  
   ![](./image/install-11.png)  
   ![](./image/install-12.png)

---

## 4. Partisi dan Instalasi Windows

1. Setelah driver terdeteksi, disk akan muncul.  
   Anda bisa membuat partisi sesuai kebutuhan, namun pada contoh ini partisi di-skip.  
   ![](./image/install-13.png)

2. Pada jendela **Ready to Install**, klik **Install** untuk memulai proses instalasi.  
   ![](./image/install-14.png)

3. Tunggu hingga proses instalasi selesai. Sistem akan **reboot otomatis**.  
   ![](./image/install-15.png)

4. Saat reboot, **jangan menekan tombol apapun** agar sistem dapat booting ke hard disk.  
   Biarkan sementara sebelum CD/DVD ROM di-detach dari VM.  
   ![](./image/install-16.png)

---

## 5. Langkah Selanjutnya

- Setelah instalasi selesai, sistem akan boot ke Windows 11.  
➡️ [**Buka Panduan Konfigurasi Windows 11**](./konfigurasi.md)
