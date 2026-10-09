# 11 — Bandit Level 0–5 (writeup)

- L0→1: `cat readme` — password di file biasa.
- L1→2: file bernama `-`: `cat ./-` supaya tidak dibaca sebagai opsi.
- L2→3: file dengan spasi: pakai kutip atau escape, misal `cat "spaces in this filename"`.
- L3→4: file hidden `...Hiding-From-You` di `inhere/`: `ls -la inhere`.
- L4→5: cari file ASCII di antara file binary: `file inhere/*`.
- L5→6: `find inhere/ -type f -size 1033c ! -executable`.

Pelajaran: `ls -la`, `file`, `find`, dan cara memegang nama file aneh.
