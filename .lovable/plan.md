# Dashboard V2 — Information Architecture Refinement

## Hasil yang akan dibuat
- Mempertahankan hero, foto tim, warna utama, sidebar, menu, dan seluruh alur akses tanpa perubahan.
- Menambahkan ringkasan hari ini yang ringkas di bawah hero, memakai data tugas, agenda, dan notifikasi yang sudah dimuat.
- Mempertahankan “Mulai dari sini” sebagai action center dengan gerak hover yang lebih jelas namun tetap tenang.
- Mengumpulkan semua kondisi yang membutuhkan tindakan ke bagian “Perlu Perhatian” berbentuk daftar horizontal; tampilkan keadaan “Semua aman” bila kosong.
- Menempatkan aktivitas organisasi setelah perhatian, dengan timeline dan empty state yang lebih membantu.
- Memindahkan statistik ke “Organisasi Hari Ini”, menyederhanakan statistik utama, dan menempatkan keuangan dalam ringkasan tersendiri yang tidak dominan.
- Menjaga seluruh fitur khusus peran dan divisi tetap tersedia setelah ringkasan utama.

## Urutan baru
1. Hero yang sudah disetujui
2. Ringkasan hari ini
3. Mulai dari sini
4. Perlu Perhatian
5. Aktivitas Organisasi
6. Organisasi Hari Ini
7. Keuangan
8. Informasi khusus peran/divisi yang sudah ada

## Detail teknis
- Menggunakan query, hooks, state, permission, dan data yang saat ini sudah ada; tidak menambah atau mengubah database maupun API.
- Memecah presentasi perhatian dan keuangan menjadi komponen kecil agar halaman tetap mudah dirawat.
- Menggunakan token warna Dashboard V2 dan motion 180–250 ms, termasuk dukungan reduced motion.
- Memastikan urutan yang sama pada desktop dan mobile.
- Memvalidasi hasil melalui build dan tampilan lokal. Screenshot dashboard login-protected akan diambil bila sesi autentikasi tersedia; jika tidak, keterbatasannya akan dilaporkan tanpa meminta kredensial.
