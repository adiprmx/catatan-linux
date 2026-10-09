# 09 — Kompresi: gzip, bzip2, tar

- `gzip -d x.gz` → hasil `x`; `bzip2 -d x.bz2` → hasil `x` (atau `x.out` kalau nama asli tidak ketebak)
- `tar -xf x.tar` → ekstrak arsip tar ke direktori sekarang
- Triknya: program decompress butuh EKSTENSI yang tepat — rename dulu pakai `mv`
  (`mv data data.gz`) sebelum `gzip -d`.
- Pola "kupas berlapis": tiap selesai decompress, jalankan `file` lagi untuk tahu lapisan berikutnya.
  Bisa gzip → bzip2 → tar → gzip lagi, dst.
