# 04 — grep, sort, uniq

- `grep kata file` — tampilkan baris yang mengandung kata; `-i` abaikan kapital.
- `sort` — urutkan baris; `uniq` — hapus baris duplikat yang berurutan.
- Kombinasi klasik analisis log: `sort file | uniq -u` → hanya baris yang muncul tepat 1 kali.
- `uniq -c` menghitung kemunculan tiap baris; `uniq -d` hanya yang duplikat.

Contoh nyata: `strings data.txt | sort | uniq -u` dipakai buat nemu password yang unik di Bandit level 8.
