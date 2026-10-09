# 21 — Shell Script Dasar

- Baris pertama `#!/usr/bin/env bash` (shebang) = "jalankan pakai bash"
- `chmod +x script.sh` supaya bisa dieksekusi langsung
- Variabel: `NAMA="adi"` (tanpa spasi di sekitar `=`!), pakai: `echo $NAMA`
- `set -euo pipefail` di awal script: berhenti saat error, anggap variabel kosong sebagai error
- Komentar diawali `#` — script yang baik menjelaskan KENAPA, bukan cuma APA
