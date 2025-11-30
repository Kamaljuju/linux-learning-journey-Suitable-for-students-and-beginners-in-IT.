# 06 — Monitoring and Managing Processes

Mengelola proses menjaga sistem tetap stabil.

---

## 🔹 Materi
```bash
# Melihat proses
ps aux
top
htop   # jika terinstall

# Mencari proses
ps aux | grep nama_proses
pgrep nama_proses

# Menghentikan proses
kill PID
kill -9 PID
pkill nama_proses

# Background & Foreground
command &
jobs
fg %1
bg %1
🔹 Contoh Soal Cerita
Laptop terasa lambat.
Cari proses firefox yang memakan banyak memori.
Hentikan proses tersebut.
Jalankan proses lain di background dan pantau job list.

🔹 Cara Mengerjakan
bash
Copy code
ps aux | grep firefox
pkill firefox
sleep 60 &
jobs
Insight
Mengontrol proses membantu troubleshooting server.

Penting untuk menjaga performa sistem.