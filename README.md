# SIMLAB BSM TKJ

Aplikasi pengelolaan Lab Komputer TKJ, SMK Bina Siswa Mandiri Bl. Limbangan.
Situs statis: satu berkas `index.html`, tanpa proses build.

## Pasang di Vercel (lewat terminal)

1. Pasang Node.js, lalu jalankan: `npm i -g vercel`
2. Masuk ke folder ini: `cd simlab-bsm-tkj`
3. Jalankan `vercel` dan masuk ke akun Vercel bila diminta.
4. Saat ditanya nama proyek, isi `simlab-bsm-tkj`. Jawab default untuk pertanyaan lain.
5. Terbitkan ke alamat tetap: `vercel --prod`

Alamat yang dihasilkan biasanya `https://simlab-bsm-tkj.vercel.app`.

## Pasang di Vercel (lewat GitHub)

1. Unggah isi folder ini ke repositori GitHub baru.
2. Di vercel.com pilih Add New > Project, impor repositori itu, lalu Deploy.

## Catatan

- Data disimpan di peramban (localStorage) pada setiap perangkat dan tidak tersinkron.
- Alamat Vercel tidak boleh memakai garis bawah, jadi pakai `simlab-bsm-tkj`.
