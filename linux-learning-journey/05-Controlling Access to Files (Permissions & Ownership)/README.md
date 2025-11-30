# 05 — Controlling Access to Files (Permissions & Ownership)

Linux mengatur hak akses file untuk owner, group, dan others.

---

## 🔹 Materi
```bash
# Melihat permission
ls -l

# Mengubah permission
chmod 755 file
chmod u+r file
chmod g-w file
chmod o+x file

# Mengubah kepemilikan
sudo chown user file
sudo chown user:group file
sudo chgrp group file
🔹 Contoh Soal Cerita
Kamu membuat file secret.txt berisi data penting.
Atur supaya hanya owner bisa baca/tulis, group bisa baca, others tidak bisa akses.

🔹 Cara Mengerjakan
bash
Copy code
touch secret.txt
chmod 640 secret.txt
sudo chown andi secret.txt
ls -l secret.txt
Insight
Mengontrol akses file menjaga data tetap aman.

Hak akses sesuai kebutuhan user sangat penting.

