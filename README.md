# Portal Pendapatan Pegawai

Aplikasi web untuk mengelola data pendapatan pegawai rumah sakit: gaji pokok, tunjangan, dan jasa pelayanan, dengan dua tampilan dalam satu kode.

## Kegunaan

- Operator mengelola data pendapatan pegawai.
- Pegawai melihat rincian pendapatannya dari ponsel.
- Rekap pendapatan per periode.

## Tech stack

| Lapis | Teknologi |
|---|---|
| Framework | Next.js 14 (App Router) + TypeScript |
| Data | MySQL 8 lewat Prisma |
| Auth | Auth.js v5 dengan dua penyedia |
| UI | Tailwind CSS |
| Infrastruktur | Docker |

## Alur singkat

1. Operator masuk dan memasukkan komponen pendapatan.
2. Data dihitung dan disimpan per periode.
3. Pegawai masuk dengan akunnya dan melihat rincian.
4. Rekap diunduh untuk arsip.

## Ringkasan

| | |
|---|---|
| Mulai dikembangkan | Juli 2026 |
| Status | Aktif dipakai internal |

> Kode sumber tidak dipublikasikan. Repo ini hanya menjelaskan kegunaan, stack, dan alur kerja. Tidak ada data pengguna, data pasien, atau kredensial di sini.
