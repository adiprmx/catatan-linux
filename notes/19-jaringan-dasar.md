# 19 — Jaringan Dasar

- `ping <host>` — tes konektivitas (Ctrl+C untuk berhenti)
- `curl -s <url>` — ambil isi URL via terminal; `-s` mode senyap
- `ss -tlnp` — lihat port TCP yang sedang listen + proses pemiliknya
- Port umum: 22 (SSH), 80 (HTTP), 443 (HTTPS)
- Kalau `curl` timeout padahal browser bisa: curigai proxy / firewall egress.
