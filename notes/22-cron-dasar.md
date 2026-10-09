# 22 — Cron Dasar

Format jadwal cron: `menit jam tanggal bulan hari`
```
*/5 * * * * /path/cek.sh   → tiap 5 menit
0 8 * * * /path/lapor.sh   → tiap hari jam 08:00
0 0 * * 0 /path/mingguan.sh → tiap Minggu tengah malam
```
- `*` = setiap; `*/5` = tiap 5; daftar: `1,15`; rentang: `9-17`
- `crontab -e` untuk edit, `crontab -l` untuk lihat
- Cron cocok untuk cek berkala; untuk "bangun saat ada kejadian" lebih pas pakai hook/event.
