# 12 — Bandit Level 6–9 (writeup)

- L6→7: `find / -user bandit7 -group bandit6 -size 33c 2>/dev/null` — cari di seluruh sistem,
  buang error permission dengan `2>/dev/null`.
- L7→8: `grep millionth data.txt` — saring baris berisi kata kunci.
- L8→9: `strings data.txt | sort | uniq -u` — password = satu-satunya baris yang muncul tepat 1x.
- L9→10: `strings data.txt | grep "="` — password setelah deretan `=` (awas jebakan `=== the password is`).

Pelajaran: `grep`, pipe `|`, `sort` + `uniq -u`, dan membaca soal dengan teliti
(level bisa bergeser dari panduan lama — cek soal resmi).
