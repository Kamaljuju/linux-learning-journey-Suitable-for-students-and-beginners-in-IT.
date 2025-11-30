# 04 — Managing Local Users and Groups

Mengatur user dan group sangat penting untuk keamanan sistem.

---

## 🔹 Materi
```bash
# User Management
sudo adduser nama_user
sudo passwd nama_user
sudo userdel nama_user

# Group Management
sudo groupadd nama_group
sudo groupdel nama_group
sudo gpasswd -a user group
sudo gpasswd -d user group

# Melihat info user & group
id user
groups user
cat /etc/passwd
cat /etc/group
🔹 Contoh Soal Cerita
Sebuah komputer digunakan beberapa temanmu.
Buat user baru bernama andi.
Tambahkan ke group students.
Setelah latihan selesai, hapus user tersebut.

🔹 Cara Mengerjakan
bash
Copy code
sudo adduser andi
sudo gpasswd -a andi students
groups andi
sudo userdel -r andi
Insight
User & group menentukan siapa bisa mengakses file atau folder.

Penting untuk keamanan server.