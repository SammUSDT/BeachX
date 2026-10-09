# BEACHX — Bug Menu App

Aplikasi bug menu untuk gaya-gayaan.

## Struktur File
- `account.html` — Halaman login
- `index.html` — Dashboard utama

## Cara Pakai di Sketchware
1. Buat project baru
2. Tambahkan WebView ke layout
3. Di onCreate, tambahkan:
   webView.getSettings().setJavaScriptEnabled(true);
   webView.loadUrl("file:///android_asset/account.html");
4. Letakkan kedua file di folder assets
5. Build & Install

## Alur
1. User buka app → `account.html` (login)
2. Isi username & password → klik SIGN IN
3. Redirect ke `index.html` (dashboard)
4. Bisa ganti tema, buka menu bug, logout

## Tema
- Blue (default)
- Red
- Green
- Purple
- Orange
- Pink
