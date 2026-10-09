# 07 — tr & ROT13

- `tr 'SET1' 'SET2'` — tukar tiap karakter set1 ke set2, satu-satu.
- ROT13 = tiap huruf digeser 13 posisi (a→n, b→o, ..., n→a). Cara decode:
  `cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'`
- ROT13 itu "enkripsi" mainan — membaliknya semudah mengenkripsinya.
  Jangan pernah pakai untuk data serius.
