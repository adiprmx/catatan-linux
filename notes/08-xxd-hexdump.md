# 08 — xxd & Hexdump

- Hexdump = tampilan isi file sebagai angka heksa + representasi teks.
- `xxd file` — buat hexdump; `xxd -r` — BALIKKAN hexdump jadi file binary asli.
- Berguna saat file dikirim sebagai teks hex (misal output yang di-copy dari terminal).

Alur: `xxd -r data.txt > data` lalu `file data` untuk tahu langkah berikutnya.
