# 06 — file, strings, base64

- `file x` — menebak tipe file dari ISINYA, bukan dari ekstensi. Andalan saat menghadapi file misterius.
- `strings x` — menarik teks yang bisa dibaca manusia dari file binary.
- `base64` / `base64 -d` — encode/decode base64. PENTING: ini BUKAN enkripsi,
  cuma cara membungkus data binary jadi teks. Attacker suka pakai buat menyamarkan payload.

Alur tipikal: `file` dulu → kalau ASCII langsung `cat`; kalau binary → `strings`.
