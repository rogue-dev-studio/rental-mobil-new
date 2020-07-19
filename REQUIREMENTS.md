# Requirements — Rental Mobil

## Tujuan
Mengelola operasional usaha rental mobil: armada, transaksi sewa, dan data pelanggan.

## Aktor
- Admin / pemilik usaha rental
- Staf operasional

## Kebutuhan fungsional (FR)
- FR-01 Manajemen data kendaraan / armada
- FR-02 Manajemen data pelanggan
- FR-03 Pencatatan transaksi sewa
- FR-04 Pantau status ketersediaan kendaraan
- FR-05 Laporan ringkas operasional (sesuai modul yang tersedia)

## Kebutuhan non-fungsional (NFR)
- NFR-01 Autentikasi admin
- NFR-02 UI web untuk operasional harian
- NFR-03 Berjalan di browser modern

## Batasan & asumsi
- Fokus operasional rental (bukan marketplace multi-vendor)
- Pembayaran gateway pihak ketiga opsional / di luar scope demo
- Demo portfolio; aturan bisnis klien dapat ditambah

## Stack
- Laravel, MySQL, Bootstrap / aset vendor UI
