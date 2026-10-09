# 02 — File Hidden & Permission

- File hidden namanya diawali titik, misal `.bashrc`. Tidak tampil di `ls` biasa — pakai `ls -la`.
- Trik file bernama `-` (strip): `cat < -` atau `cat ./-` supaya tidak dibaca sebagai opsi.
- `ls -l` menampilkan permission `rwxrwxrwx` = read/write/execute untuk user, group, other.
- `chmod` mengubah permission (didalei di catatan lanjutan).
