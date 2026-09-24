# Panduan Kontribusi — IDTC Pokja 2

Terima kasih sudah mau berkontribusi! Panduan ini berlaku untuk semua repo di organisasi `idtc-id`, kecuali repo tersebut punya `CONTRIBUTING.md` sendiri.

## Alur kerja singkat

1. **Mulai dari issue.** Cek dulu apakah sudah ada issue serupa. Kalau belum, buat issue baru memakai template yang tersedia.
2. **Buat branch** dari `main` dengan nama `jenis/deskripsi-singkat`, contoh:
   - `data/lidar-kecamatan-a`
   - `docs/charter-pilot`
   - `fitur/konektor-sensor-mqtt`
   - `perbaikan/koordinat-salah`
3. **Commit kecil dan jelas**, dalam Bahasa Indonesia atau Inggris, contoh: `Tambah skrip konversi LAS ke 3D Tiles`.
4. **Buka Pull Request (PR)** ke `main`, isi template PR, dan tautkan issue (`Closes #12`).
5. **Review**: minimal 1 approval. Reviewer otomatis diminta sesuai `CODEOWNERS`.
6. Setelah disetujui, PR di-*merge* oleh pemilik repo atau yang mengajukan (jika punya akses).

Belum terbiasa dengan git? Anda tetap bisa berkontribusi lewat **edit file langsung di web GitHub** — lihat panduan pemula di repo `pokja2-handbook`.

## Hal yang TIDAK boleh masuk repo

- Data mitra yang belum ada izin tertulis untuk dibagikan.
- Data pribadi (NIK, nomor HP, alamat perorangan, dll).
- Kredensial: password, API key, token, connection string.
- File data besar (> 50 MB) — simpan di storage terpisah dan catat tautannya di katalog data.

Tidak sengaja meng-upload hal di atas? Segera hubungi pengurus; **menghapus file saja tidak cukup** karena masih tersimpan di riwayat git.

## Diskusi

- Pertanyaan, ide, dan diskusi terbuka → **Discussions** di `pokja2-handbook`.
- Pekerjaan konkret yang perlu dikerjakan → **Issue** di repo terkait.
- WhatsApp → hanya pengumuman dan tautan.

## Lisensi

Kecuali dinyatakan lain di repo masing-masing: kode berlisensi **MIT**, dokumentasi **CC BY 4.0**, dan data mengikuti lisensi pemiliknya.
