# 20 — Regex Dasar (untuk grep)

- `.` = satu karakter apa saja; `*` = nol atau lebih dari pola sebelumnya
- `^` = awal baris; `$` = akhir baris
- `[abc]` = salah satu dari a/b/c; `[0-9]` = satu digit
- `grep -E` (atau `egrep`) untuk regex extended

Contoh:
- `grep "^password" data.txt` — baris yang DIAWALI "password"
- `grep "[0-9]\{4\}"` — baris berisi 4 digit berurutan (basic regex)
- `grep -E "[0-9]{4}"` — sama, versi extended (lebih enak dibaca)
