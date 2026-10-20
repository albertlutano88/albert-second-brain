# Aturan kerja Claude di repo ini

Repo ini second brain Albert Lutano. Baca file ini sebelum menambah atau memindah apa pun.

## Gaya

- Bahasa Indonesia yang natural, seperti menulis untuk teman yang cerdas.
- Jangan pakai em dash. Pakai koma, titik dua, atau kalimat baru.
- Catat apa yang Albert katakan. Jangan menambah tafsiran atau saran ke dalam catatan.
- Setiap entri diberi tanggal: `- YYYY-MM-DD: isi`. Entri terbaru di atas.

## Routing pesan

1. Tentukan jenis: ide, tugas, janji, atau catatan. Awalan (`ide:`, `tugas:`, `janji:`, `catat:`) selalu menang. Tanpa awalan, tebak dari isinya.
2. Tentukan rumah:
   - Ada tenggat dan hasil akhir yang jelas, dan sudah punya file di `1-proyek/`: masuk ke sana.
   - Berkaitan dengan ventura, klien, atau area hidup yang sudah ada di `2-area/`: masuk ke file itu.
   - Bahan referensi atau ide yang belum terikat ke mana pun: `3-sumber/`.
   - Ragu: `INBOX.md`.
   - Belanja dan pesanan makanan pribadi masuk ke `2-area/hidup/kesehatan.md`.
3. Janji selalu dicatat di `JANJI.md` (kepada siapa, apa, tenggat, status), lalu ditautkan dari file area atau proyeknya.
4. Tugas masuk ke bagian `## Tugas` sebagai checkbox: `- [ ] isi (tenggat: YYYY-MM-DD)`.
5. Proyek baru dibuat di `1-proyek/` hanya kalau ada hasil akhir yang jelas. Nama file: `slug-singkat.md`, pakai `1-proyek/_template.md`.
6. Proyek selesai: pindah ke `4-arsip/` dengan tanggal selesai di bagian atas.
7. Satu pesan bisa menyentuh beberapa file. Pecah sesuai tujuan.
8. Commit setelah setiap pesan: `jenis: ringkasan singkat` (contoh `tugas: kirim action plan WMC ke Ryan`). Push ke `main`.

## Batas

- Angka dan transaksi keuangan tidak dicatat di sini. Taruh tautan ke [albert-lutano-finance](https://github.com/albertlutano88/albert-lutano-finance).
- Materi kampanye dan output tim AI tinggal di [albert-lutano-company](https://github.com/albertlutano88/albert-lutano-company). Di sini cukup keputusan dan tautannya.
- Jangan simpan nomor rekening, nomor kartu, nomor identitas, atau kata sandi.

## Review mingguan (Minggu malam)

Ikuti `review/_template.md`. Simpan hasilnya di `review/YYYY-MM-DD.md` (tanggal hari Minggu itu), commit `review: minggu YYYY-MM-DD`.
