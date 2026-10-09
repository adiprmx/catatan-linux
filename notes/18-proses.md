# 18 — Proses

- `ps aux` — daftar semua proses yang jalan; kolom PID = nomor identitas proses
- `kill <PID>` — hentikan proses dengan sopan (SIGTERM); `kill -9 <PID>` paksa mati (SIGKILL)
- `pkill -f <pola>` — kill berdasar nama/pola command line (hati-hati pola yang match shell sendiri!)
- `<perintah> &` — jalankan di background; `jobs` — lihat daftar job; `fg` — tarik ke foreground
- Umur proses yang akurat: `ps -o etimes= -p <PID>` (detik sejak start)
