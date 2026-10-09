# 17 — User & Group

- `whoami` — tampilkan user yang sedang login; `id` — tampilkan uid, gid, dan grup
- `/etc/passwd` — daftar user di sistem (bisa dibaca semua orang)
- Tiap file punya pemilik (user) dan grup pemilik — terlihat di `ls -l`
- `sudo <perintah>` — jalankan perintah sebagai root (biasanya minta password user sendiri)
- Prinsip: jangan kerja sebagai root kalau tidak perlu — makin besar kuasa, makin besar risiko salah ketik.
