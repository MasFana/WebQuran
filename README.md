# Aplikasi Web Quran MasFana
**Dibuat oleh MasFana** - [MasFana](https://github.com/MasFana)

Adrian Fathan Imama (232410103047)

![Image](https://raw.githubusercontent.com/imamamacuuu/FanaImage/main/uploads/screenshot-1742902655296.png)

Aplikasi web modern dan responsif untuk membaca Al-Quran dengan terjemahan dan fitur navigasi.

## Fitur Utama

- **Pembaca Surah**: Menampilkan surah lengkap dengan teks Arab, translate Indonesia, dan terjemahan Bahasa Indonesia
- **Navigasi Surah**: Mudah berpindah antara surah dengan tombol sebelumnya/selanjutnya
- **Desain Responsif**: Dapat digunakan di berbagai perangkat
- **Mode Gelap**: Tema gelap yang nyaman untuk mata

## Teknologi Yang Digunakan

- HTML
- CSS
- JavaScript
- [API EQuran.id](https://equran.id/apidev) untuk data Quran
- Google Fonts (Poppins dan Traditional Arabic)

## Cara Penggunaan

1. Buka aplikasi di browser web
2. Jelajahi dan search di daftar surat
3. Klik pada surah untuk melihat ayat
4. Gunakan tombol navigasi untuk berpindah surat

## Struktur File

```
/
├── index.html         # Halaman utama
├── baca / 
    └──index.html      # Halaman pembaca surah
├── favicon.ico        # Ikon aplikasi
└── README.md          # Dokumentasi ini

```

## Referensi API

Aplikasi ini menggunakan [API EQuran.id](https://equran.id/apidev):

- Daftar surah: `https://equran.id/api/v2/surat`
- Detail surah: `https://equran.id/api/v2/surat/{nomor}`
- Tafsir: `https://equran.id/api/v2/tafsir/{nomor}`

---

1. **Search Surat**:
    - Gunakan Input di navbar pada halaman utama untuk mencari surat
2. **Navigasi Surat**:
   - Gunakan tombol "< Sebelumnya" dan "Selanjutnya >" untuk berpindah surah
   - Tombol akan dinonaktifkan secara otomatis di surah pertama (Al-Fatihah) dan terakhir (An-Nas)

3. **Membaca Ayat**:
   - Setiap ayat ditampilkan dengan:
     - Nomor ayat
     - Teks Arab
     - Transliterasi Latin
     - Terjemahan Bahasa Indonesia

4. **Tampilan Responsif**:
   - Aplikasi akan menyesuaikan tampilan di:
     - Smartphone (lebar < 640px)
     - Tablet (lebar 640px-1024px)
     - Desktop (lebar > 1024px)