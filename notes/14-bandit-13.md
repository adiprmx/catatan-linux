# 14 — Bandit Level 13 (writeup)

- Level 13 tidak memberi password bandit14 — tapi memberi PRIVATE SSH KEY di home directory.
- Login sebagai bandit14: `ssh -i sshkey.private bandit14@localhost -p 2220`
- Password bandit14 ada di `/etc/bandit_pass/bandit14` yang hanya bisa dibaca user bandit14.

Pelajaran: SSH key sebagai pengganti password — konsep yang dipakai di dunia nyata
untuk server, GitHub, dan deployment.
