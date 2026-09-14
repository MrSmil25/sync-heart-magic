# Perbaikan layar pembuka sebelum login

## Tujuan
Mencegah layar pembuka terlihat macet atau kosong sebelum halaman login tersedia.

## Perubahan
- Tampilkan layar pembuka segera, tanpa menunggu pemeriksaan sesi pengguna selesai.
- Pertahankan pengalihan pengguna yang sudah login ke dashboard setelah pemeriksaan selesai.
- Ringankan animasi logo saat perangkat lambat dan pastikan logo cadangan langsung terlihat selama model 3D dimuat.
- Pertahankan desain, autentikasi, rute, dan alur login yang ada.

## Validasi
- Uji tampilan pada saat 100 ms, 500 ms, dan setelah animasi termuat.
- Pastikan klik layar tetap membuka halaman login.
- Periksa tampilan desktop dan ukuran layar saat ini, serta memastikan tidak ada error baru.
