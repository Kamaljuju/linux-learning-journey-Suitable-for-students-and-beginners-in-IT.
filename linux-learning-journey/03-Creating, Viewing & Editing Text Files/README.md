# 03 — Creating, Viewing & Editing Text Files

Belajar membuat, melihat, dan mengedit file teks di Linux.

---

## 🔹 Materi
```bash
# Membuat file teks
touch file.txt
echo "Halo Linux" > file.txt

# Melihat file
cat file.txt
more file.txt
less file.txt
head file.txt
tail file.txt

# Mengedit file
nano file.txt
vi file.txt
🔹 Contoh Soal Cerita
Kamu mendapat instruksi untuk membuat catatan rapat tim.
Buat file meeting.txt berisi ringkasan.
Tampilkan isi file untuk memastikan tidak ada yang salah.
Tambahkan catatan tambahan di akhir file.

🔹 Cara Mengerjakan
bash
Copy code
echo "Rapat hari ini membahas Linux Learning Journey" > meeting.txt
echo "Besok latihan mengelola user dan permission" >> meeting.txt
cat meeting.txt
nano meeting.txt
Insight
File teks penting untuk konfigurasi sistem.

Menguasai editor teks di terminal sangat membantu.