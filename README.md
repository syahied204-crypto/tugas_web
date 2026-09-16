# Portofolio Syahied

Website portofolio statis mahasiswa Teknik Informatika,
Universitas 17 Agustus 1945 Surabaya. Dibangun dengan
HTML5 dan CSS3 tanpa kerangka kerja tambahan agar ringan
dan mudah dipublikasikan sebagai halaman statis.

Halaman langsung: https://syahied.github.io/portofolio

## Isi halaman

| Bagian     | Keterangan                           |
|------------|--------------------------------------|
| Identitas  | Nama, NBI, prodi, dan tautan utama   |
| Profil     | Ringkasan diri dan data akademik     |
| Kompetensi | Kemampuan teknis per bidang          |
| Proyek     | Tiga proyek dan tumpukan teknologi   |
| Organisasi | Pengalaman kepanitiaan dan organisasi|
| Kontak     | Surel, GitHub, dan LinkedIn          |

## Struktur berkas

    portofolio/
    |-- index.html          # struktur halaman
    |-- css/
    |   `-- style.css       # warna, layout, media query
    |-- img/                # aset gambar
    `-- README.md           # dokumentasi repositori

## Teknologi

- HTML5 semantik (header, nav, main, section,
  article, footer)
- CSS3: custom properties, flexbox, media query,
  prefers-reduced-motion
- Tanpa dependensi eksternal dan tanpa proses build

## Menjalankan secara lokal

    git clone https://github.com/syahied/portofolio.git
    cd portofolio
    python -m http.server 8000
    # buka http://localhost:8000 pada peramban

## Alur kontribusi

1. Buat branch dari `main`: `fitur/<nama-fitur>`.
2. Kerjakan perubahan, buat commit kecil dan jelas.
3. Jalankan `git pull origin main` sebelum push.
4. Buka pull request, minta tinjauan satu anggota tim.
5. Setelah disetujui, merge ke `main`; publikasi
   berjalan otomatis.

## Publikasi

Halaman dipublikasikan melalui GitHub Pages dari branch
`main` folder root. Setiap merge ke `main` memperbarui
situs dalam waktu singkat.

## Lisensi

MIT License. Konten portofolio (teks dan gambar diri)
tidak termasuk lisensi ini.
