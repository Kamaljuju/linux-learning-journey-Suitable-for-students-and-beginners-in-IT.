# 07 — Controlling Services & SSH

Materi ini membahas **service Linux** dan **remote login menggunakan SSH**.

---

## 🔹 Materi
```bash
# Systemd Service
systemctl status nama_service
systemctl start nama_service
systemctl stop nama_service
systemctl restart nama_service
systemctl enable nama_service
systemctl disable nama_service

# SSH
systemctl status ssh
systemctl start ssh
systemctl enable ssh
systemctl restart ssh
ssh username@ip_address
ssh -p 2222 username@ip_address
🔹 Contoh Soal Cerita
Kamu ingin mengakses server sekolah dari rumah.
Periksa apakah SSH aktif, aktifkan jika mati.
Restart SSH setelah konfigurasi diperbarui.
Login ke server menggunakan SSH.

🔹 Cara Mengerjakan
bash
Copy code
systemctl status ssh
sudo systemctl start ssh
sudo systemctl enable ssh
sudo systemctl restart ssh
ssh username@ip_address
ssh -p 2222 username@ip_address
Insight
Service mengatur aplikasi yang berjalan di background.

SSH penting untuk remote server secara aman.