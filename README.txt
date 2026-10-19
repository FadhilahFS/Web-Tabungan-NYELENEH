DOMPET & TABUNGAN PRIBADI
========================

Cara menjalankan:
1. Ekstrak ZIP ini.
2. Buka index.html di browser modern (Chrome, Edge, Safari).
3. Tambahkan pemasukan agar saldo dompet bertambah.
4. Pilih Menabung untuk memindahkan saldo dompet ke tabungan.
5. Pilih Pengeluaran untuk mengurangi saldo dompet.
6. Atur target tabungan, lihat progres, dan ekspor riwayat sebagai CSV.

Publikasi Cloudflare Pages:
- Buat proyek Pages melalui Direct Upload.
- Unggah ZIP ini atau folder yang berisi index.html.
- Deploy. Cloudflare akan memberikan alamat pages.dev.

Catatan:
- Aplikasi statis ini menyimpan data pada localStorage browser/perangkat yang digunakan.
- Data tidak tersinkronisasi antarperangkat dan bisa hilang jika data browser dihapus.
- Ekspor CSV secara berkala untuk cadangan.

Fitur peringatan saldo rendah:
- Jika saldo dompet turun di bawah Rp100.000, banner peringatan hemat akan muncul otomatis.
- Saat saldo kembali menjadi Rp100.000 atau lebih, peringatan akan hilang.
