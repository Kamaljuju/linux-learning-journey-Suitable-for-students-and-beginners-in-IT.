# 02 — Working with Directories & Files

Mengelola file dan folder adalah skill penting di Linux.

---

## 🔹 Materi
```bash
mkdir folder        # membuat folder baru
rmdir folder        # menghapus folder kosong
rm -r folder        # menghapus folder beserta isinya
touch file.txt      # membuat file kosong
cp file1.txt file2.txt   # menyalin file
mv file.txt dir/         # memindahkan atau rename file
rm file.txt              # menghapus file
ls -l                    # melihat isi folder + detail
🔹 Contoh Soal Cerita
Bos meminta kamu membuat struktur folder untuk proyek baru: project, docs, dan src.
Di dalam docs, buat file README.txt. Salin file tersebut ke docs_backup.

🔹 Cara Mengerjakan
bash
Copy code
mkdir project
cd project
mkdir docs src
touch docs/README.txt
cp docs/README.txt docs_backup.txt
ls -l docs
ls -l docs_backup.txt
Insight
Mengelola folder dan file secara efektif adalah skill penting bagi sysadmin atau developer.