# Sistem Login User dan Admin

Proyek ini adalah sebuah aplikasi web dengan sistem login yang memisahkan akses untuk admin dan user biasa.

## Fitur

- Sistem autentikasi dengan username dan password
- Role-based access control (admin dan user)
- Dashboard admin dengan desain modern
- Dashboard user sederhana
- Perlindungan routing berdasarkan status login dan role

## Teknologi yang Digunakan

- React
- Vite
- Zustand (state management)
- React Router (navigasi)
- Shadcn/UI (komponen UI)
- Tailwind CSS (styling)

## Kredensial Login

### Admin
- Username: `admin`
- Password: `admin123`

### User
- Username: `ahmad` (dan nama lain, cek src/data/users.ts)
- Password: `[nama]123` (misalnya: ahmad123, afifah123, dll)

## Cara Menjalankan

```bash
# Menginstal dependencies
bun install

# Menjalankan aplikasi
bun run dev
```

Aplikasi akan berjalan di `http://localhost:5173`

## Struktur Proyek

- `/src/components` - Komponen React
  - `/Admin` - Komponen untuk halaman admin
  - `/User` - Komponen untuk halaman user
- `/src/pages` - Halaman utama aplikasi
- `/src/store` - Zustand store untuk manajemen state
- `/src/data` - Data statis untuk aplikasi

## Catatan

- Data pengguna disimpan hanya secara lokal (browser storage)
- Untuk menambahkan/mengubah pengguna, edit file `src/data/users.ts`
