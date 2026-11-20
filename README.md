<p align="center"><img src="icons/logo.svg" width="140" alt="Logo MyCRT-AID"></p>

# MyCRT-AID

**MyCRT-AID** ialah Progressive Web App (PWA) untuk Cyber Responder Team (CRT), Cawangan Penguatkuasaan Farmasi Sarawak: panduan langkah demi langkah semasa rampasan peranti digital, dengan muat naik gambar, animasi tunjuk cara, draf Senarai Bongkar dan laporan PDF.

## Rujukan prosedur
- Prosedur Kualiti K-PK-14 *Rampasan dan Pengendalian Peranti Digital*, Keluaran 1.0 (22 Februari 2023), Bahagian Penguatkuasaan Farmasi KKM
- Senarai Semak Operasi Rampasan Digital, CPF Sarawak (2022_07)

## Ciri
- Wizard langkah ikut jenis peranti (telefon / laptop / CPU) dan status ON / OFF
- Muat naik gambar pada setiap langkah, dengan cop masa
- Animasi tunjuk cara iPhone / Android / Windows / macOS (IMEI, eSIM, flight mode, kunci skrin, cara ambil gambar komponen, bungkus dan lak rasmi)
- Lampiran A dan draf Senarai Bongkar dijana automatik
- Laporan akhir PDF (maklumat kes, Senarai Bongkar, Lampiran A, log langkah, gambar bernombor)
- Boleh dipasang ke skrin utama dan berfungsi luar talian selepas dibuka sekali

## Privasi data
Semua data kes dan gambar disimpan **dalam pelayar peranti itu sahaja** (IndexedDB). Tiada data dihantar ke pelayan. Muat turun laporan PDF sebelum menekan “Kes baru” atau memadam data pelayar.

## Pasang di telefon
- **Android (Chrome):** buka pautan › menu ⋮ › *Install app* / *Add to Home screen*
- **iPhone (Safari):** buka pautan › butang Share › *Add to Home Screen*

## Kemas kini
Selepas mengubah `index.html`, naikkan nilai `VERSION` dalam `sw.js` supaya peranti pengguna menerima versi baru.

## Struktur
```
index.html             app (satu fail)
manifest.webmanifest   maklumat PWA
sw.js                  service worker (luar talian)
icons/                 ikon app
```

## Logo
Konsep **Lak Pua**: lak rasmi dikelilingi corak zigzag dan berlian ala pua kumbu Iban, dengan telefon dan kanta pembesar di tengah, mewakili ekshibit digital yang dimeterai dan dipelihara rantaian keterangannya. Warna hitam, kuning dan merah diilhamkan daripada warna Sarawak.
