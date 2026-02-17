# 📌 Langkah Pengumpulan Tugas Web via GitHub

## 1. Fork Repository
- Buka link repository tugas dari aku.
- Klik tombol Fork (pojok kanan atas).
- Repository akan tersalin ke akun GitHub kalian sendiri.

## 2. Clone Repository (yang sudah di-fork)
- Masuk ke repository hasil fork di akun kalian.
- Klik Code → Copy link HTTPS.
- Buka Terminal / Git Bash, lalu ketik:
 ```
 git clone LINK_REPO_KALIAN
 ```
- Masuk ke folder project:
```
cd nama-repository
```

## 3. Kerjakan & Masukkan File Web
- Masukkan / edit file web kalian
(contoh: index.html, style.css, script.js).
- Pastikan web bisa dibuka normal di browser.

## 4. Commit & Push ke GitHub
- Cek perubahan:
```
git status
```
- Tambahkan semua file:
```
git add .
```
- Commit perubahan:
```
git commit -m "Mengumpulkan tugas web"
```
- Push ke repository fork kalian:
```
git push origin main
```

## 5. Kirim Link Web (GitHub Pages)
- Masuk ke Settings → Pages.
- Pilih:
  1. Branch: main
  2. Folder: /root
- Simpan, lalu tunggu sampai muncul link GitHub Pages.
- Pastikan link bisa dibuka.
- Link inilah yang nanti aku cek.

## 6. Pull Request ke Repository Aku
- Masuk ke repository fork kalian.
- Klik Contribute → Open Pull Request.
- Pastikan:
  1. Base repository → punya aku
  2. Compare repository → punya kalian
- Klik Create Pull Request.
- Isi judul (contoh):
  1. Tugas Web – Nama Lengkap
  2. Kirim Pull Request.
- Nanti konfirmasi ke aku kalo udah nge pull request biar di cek

## 7. Selesai 
