# 23 — Cheatsheet Bandit Level 0–13

| Level | Kunci |
|-------|-------|
| 0→1 | `cat readme` |
| 1→2 | `cat ./-` (file bernama strip) |
| 2→3 | kutip nama file berspasi |
| 3→4 | `ls -la` (file hidden) |
| 4→5 | `file inhere/*` (cari ASCII) |
| 5→6 | `find` + `-size 1033c ! -executable` |
| 6→7 | `find / -user bandit7 -group bandit6 -size 33c 2>/dev/null` |
| 7→8 | `grep millionth data.txt` |
| 8→9 | `strings data.txt | sort | uniq -u` |
| 9→10 | `strings data.txt | grep "="` |
| 10→11 | `base64 -d data.txt` |
| 11→12 | `tr 'A-Za-z' 'N-ZA-Mn-za-m'` (ROT13) |
| 12→13 | `xxd -r` + kupas gzip/bzip2/tar berlapis |
| 13→14 | `ssh -i sshkey.private bandit14@localhost -p 2220` |

Pola umum: `file` dulu sebagai kompas, lalu alat yang sesuai.
