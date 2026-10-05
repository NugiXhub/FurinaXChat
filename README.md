# FurinaXChat

Aplikasi chat single-file berbasis HTML/CSS/JS yang berjalan di browser tanpa backend server, menggunakan localStorage untuk menyimpan login, kontak, tema, dan data percakapan.

## Cara buka

Buka file `index.html` di browser Anda, atau jalankan server lokal sederhana jika diperlukan:

```bash
python -m http.server 8000
```

Lalu buka:

```text
http://localhost:8000/
```

## Catatan

- Sistem login berbasis nomor telepon dan OTP simulasi.
- Tema dipasang per nomor user di localStorage.
- Developer mode aktif pada nomor hardcoded `+62-800-DEV-001`.
- Semua fitur utama disimulasikan di browser tanpa backend.

