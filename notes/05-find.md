# 05 — find

Mencari file dengan kriteria detail:

- `find dir -name "*.txt"` — berdasar nama (pakai kutip supaya tidak di-expand shell)
- `-type f` file biasa, `-type d` direktori
- `-size 1033c` ukuran tepat 1033 byte; `+`/`-` untuk lebih/kurang dari
- `-user nama` / `-group nama` berdasar pemilik
- `! -executable` — negasi: yang TIDAK executable
- Gabungkan: `find inhere/ -type f -size 1033c ! -executable`

Ingat: file bernama aneh (spasi/strip) aman dipegang dengan `--` atau path `./`.
