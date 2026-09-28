BAKSO UMUM KHAS MAKASSAR — PWA
================================

Paket ini adalah versi web/PWA. Jangan dibuka dari aplikasi Files sebagai file lokal.
Agar tombol MASUK dan semua JavaScript berjalan normal di iPhone, file harus disajikan
melalui HTTPS (website).

FILE:
- index.html       aplikasi
- manifest.json    konfigurasi install ke Home Screen
- sw.js            cache/offline dasar
- icon-*.png       ikon aplikasi

CARA DI IPHONE:
1. Upload seluruh isi folder ini ke hosting HTTPS.
2. Buka alamat website tersebut di Safari.
3. Tekan Share.
4. Pilih "Add to Home Screen / Tambahkan ke Layar Utama".
5. Buka ikon "Bakso Umum" dari Home Screen.

CATATAN:
Versi ini masih prototype lokal: data transaksi/menu tersimpan di browser perangkat.
Multi-HP dengan database online dan printer Bluetooth langsung membutuhkan versi produksi
dengan backend/database dan modul printer native.
