# 10 — SSH & SSH Key

- `ssh user@host -p 2220` — login remote; `-p` untuk port non-standar.
- `ssh -i keyfile user@host` — login pakai private key, tanpa password.
- Private key = IDENTITAS. Jangan disebar, jangan di-commit ke repo publik.
- Public key ditaruh di server tujuan (`~/.ssh/authorized_keys`); private key dipegang client.
