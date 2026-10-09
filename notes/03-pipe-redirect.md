# 03 — Pipe & Redirect

- `|` (pipe): sambungkan output perintah ke input perintah berikutnya.
  Contoh: `ls | grep txt` — daftar file lalu saring yang mengandung "txt".
- `>` tulis output ke file (menimpa isi lama); `>>` menambahkan ke akhir file.
- `2>/dev/null`: buang pesan error (stderr) supaya output bersih.
  Contoh: `find / -name "*.log" 2>/dev/null` — cari tanpa dibanjiri "Permission denied".

Pipe adalah "lem super" terminal: rangkaian perintah kecil jadi alat besar.
