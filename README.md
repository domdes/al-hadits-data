# Al-Hadits Data (7 Kitab Induk — Arab, Indonesia, Inggris)

Repositori data hadits ringan & independen untuk Portal Web, Android, dan iOS Yayasan Asyuhada Jaya Bekasi.

## Kitab yang Tersedia
1. Shahih Al-Bukhari (`bukhari`)
2. Shahih Muslim (`muslim`)
3. Sunan At-Tirmidzi (`tirmidhi`)
4. Sunan Abu Daud (`abudawud`)
5. Sunan An-Nasa'i (`nasai`)
6. Sunan Ibnu Majah (`ibnmajah`)
7. Muwaththa' Imam Malik (`malik`)

## Struktur File
- `info.json` — Metadata kitab dan daftar bab bawaan.
- `sections-id.json` — Daftar nama bab (chapter) yang dapat diterjemahkan ke Bahasa Indonesia tanpa mengubah file hadits mentah.
- `editions/ara-<kitab>.min.json` — Lafadz Arab berharokat.
- `editions/ind-<kitab>.min.json` — Terjemahan Bahasa Indonesia.
- `editions/eng-<kitab>.min.json` — Terjemahan Bahasa Inggris.

## Lisensi & Sumber
Data awal diadaptasi dari [fawazahmed0/hadith-api](https://github.com/fawazahmed0/hadith-api) yang dirilis ke Public Domain di bawah lisensi **The Unlicense**.
