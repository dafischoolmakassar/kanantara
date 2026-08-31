# 06 — Harga Pokok Produksi (HPP) Budidaya Nilam per Hektar

## Ringkasan Data dari Literatur

Ditemukan **variasi besar** antar-studi terkait biaya produksi dan hasil per hektar — mencerminkan perbedaan wilayah, skala usaha, metode budidaya (monokultur vs tumpang sari), dan tahun penelitian. Tiga sumber utama:

### Sumber A — Estimasi Skala Besar (Scribd, "Estimasi Keuntungan Nilam 1 Hektar")

| Item | Nilai |
|---|---|
| Hasil minyak nilam | 1.125 – 1.500 kg/tahun |
| Pendapatan kotor | Rp 562.500.000 – 1.050.000.000/tahun |
| Biaya produksi | Rp 40.000.000 – 50.000.000/tahun |
| Laba bersih (estimasi) | Rp 512.500.000 – 1.000.000.000/tahun |

⚠️ **Catatan kehati-hatian**: Angka hasil 1.125–1.500 kg/ha/tahun ini **jauh lebih tinggi** dibanding studi akademik lain (lihat Sumber B & C di bawah, yang melaporkan 100–240 kg/ha/tahun). Kemungkinan sumber ini menggunakan asumsi kepadatan tanam sangat tinggi, banyak siklus panen dalam setahun, atau adalah materi promosi/estimasi optimistis yang tidak divalidasi secara akademik. **Perlakukan sebagai skenario batas atas (upper bound), bukan angka tipikal.**

### Sumber B — Data Produktivitas Regional (Aceh Barat)

> **Produktivitas rata-rata minyak nilam: ± 240 kg/Ha/tahun** (seluruh kecamatan di Kabupaten Aceh Barat)

### Sumber C — Perhitungan Teknis dari Rendemen

| Parameter | Nilai |
|---|---|
| Hasil daun basah | 15–20 ton/ha |
| Hasil daun kering (setelah pengeringan) | ± 5 ton/ha |
| Rendemen penyulingan | 2,5–4% (rata-rata riset lain: 2,88–3,19%, rata-rata 3,00%) |
| **Hasil minyak nilam** | **100–200 kg/ha/tahun** |

### Sumber D — Studi Biaya Produksi Aceh (Jurnal Ekonomi Pertanian & Agribisnis)

| Item | Nilai |
|---|---|
| Rata-rata biaya produksi | Rp 6.822.250 |
| Rata-rata pendapatan petani | Rp 53.377.750 |

*(Satuan/skala area studi ini tidak dapat dipastikan penuh dari ringkasan yang tersedia — kemungkinan per luasan usaha tani spesifik, bukan tepat 1 ha. Perlu verifikasi ke jurnal aslinya sebelum dipakai sebagai angka final.)*

### Sumber E — Data Usahatani Aceh (rincian per komponen produksi)

| Item | Nilai |
|---|---|
| Pendapatan petani | ± Rp 60.200.000/ha |
| Produksi daun basah | 297 kg (rata-rata) |
| Daun nilam kering | 74,25 kg |
| Harga minyak nilam (asumsi studi) | ± Rp 430.000/kg |

## Rekonsiliasi: Estimasi HPP yang Direkomendasikan untuk Model KANANTARA

Menimbang **Sumber B dan C paling konsisten satu sama lain** (100–240 kg/ha/tahun) dan selaras dengan asumsi dasar KANANTARA sendiri (**100 kg/petani/tahun**, lihat `04-Target-Rata-rata-Petani-dan-Pendapatan.md` di folder induk — mengasumsikan skala petani kecil, kemungkinan <1 ha per petani), berikut estimasi kerja:

| Skenario | Hasil (kg/ha/tahun) | Estimasi Biaya Produksi/ha/tahun* |
|---|---|---|
| Konservatif (selaras Sumber B/C) | 100 – 240 | Rp 6.800.000 – 15.000.000 (proporsional dari Sumber D, perlu validasi) |
| Optimis (Sumber A, upper bound) | 1.125 – 1.500 | Rp 40.000.000 – 50.000.000 |

*Estimasi biaya proporsional pada baris "Konservatif" adalah **interpolasi kasar**, bukan hasil studi langsung — karena data biaya (Sumber D) dan data hasil (Sumber B/C) berasal dari studi berbeda dan tidak bisa digabung secara presisi tanpa metodologi sama.

## Komponen Biaya Produksi yang Umum Disebut dalam Literatur

Meski rincian item-per-item tidak selalu tersedia lengkap, struktur biaya usahatani nilam pada umumnya mencakup:

- **Bibit/stek nilam**
- **Pengolahan lahan** (pembajakan, pembersihan)
- **Pupuk** (organik/anorganik)
- **Tenaga kerja** (tanam, pemeliharaan, panen)
- **Biaya penyulingan** (jika petani menyuling sendiri: bahan bakar, penyusutan alat suling, tenaga kerja penyulingan) — atau **biaya jasa penyulingan** jika dititipkan ke penyuling pihak ketiga
- **Transportasi/logistik** ke titik jual

## Implikasi untuk Model KANANTARA

1. **Struktur biaya petani penting untuk memvalidasi Harga Dasar** — jika HPP realistis untuk petani kecil (skala <1 ha, hasil ~100 kg/tahun) berada di kisaran **Rp 5–15 juta/tahun**, maka Harga Dasar KANANTARA (Rp 1.000.000/kg × 100 kg = **Rp 100.000.000/tahun**) memberikan margin kotor yang **sangat sehat** bagi petani (lihat perbandingan detail di `04-Target-Rata-rata-Petani-dan-Pendapatan.md`).
2. **Variasi hasil per hektar yang besar antar-sumber (100 kg vs 1.500 kg)** menegaskan pentingnya **pendampingan budidaya dan bibit unggul** (sudah menjadi bagian model loyalitas KANANTARA) sebagai pengungkit produktivitas riil — potensi peningkatan hasil 2–5x dari praktik budidaya lebih baik bukan klaim berlebihan bila dibandingkan rentang di literatur.
3. **Rekomendasi riset lanjutan**: lakukan survei HPP primer langsung ke kelompok tani target (bukan hanya literatur sekunder) sebelum menetapkan Harga Dasar final — karena rentang biaya di literatur sangat lebar dan tahun studi bervariasi (biaya input seperti pupuk dan tenaga kerja terus naik akibat inflasi).

## Referensi

- [Keuntungan Budidaya Nilam per Hektar — Scribd](https://www.scribd.com/document/857911923/Estimasi-Keuntungan-Nilam-1-Hektar)
- [Analisis Struktur Biaya Produksi dan Kesenjangan Pendapatan Petani Akibat Fluktuasi Harga Minyak Nilam — Jurnal Ekonomi Pertanian dan Agribisnis](https://jepa.ub.ac.id/index.php/jepa/article/view/199) ([versi ResearchGate](https://www.researchgate.net/publication/332124164_Analisis_Struktur_Biaya_Produksi_Dan_Kesenjangan_Pendapatan_Petani_Akibat_Fluktuasi_Harga_Minyak_Nilam))
- [Analisis Break Even Point Dengan Sensitivitas Harga Pada Usaha Budidaya Tanaman Nilam — ResearchGate](https://www.researchgate.net/publication/404408014_Analisis_Break_Even_Point_Dengan_Sensitivitas_Harga_Pada_Usaha_Budidaya_Tanaman_Nilam)
- [Struktur Biaya Produksi dan Pendapatan Usahatani Nilam dan Pengolahan Nilam di Desa Raraatean, Kec. Tompaso Baru, Kab. Minahasa Selatan — Journal of Agribusiness and Rural Development (UNSRAT)](https://ejournal.unsrat.ac.id/v3/index.php/agrirud/article/view/65831)
- [Produksi dan Rendemen Pengolahan Nilam dari Hutan Rakyat di Desa Bone-Bone, Kec. Baraka, Kab. Enrekang — ResearchGate](https://www.researchgate.net/publication/334945716_PRODUKSI_DAN_RENDEMEN_PENGOLAHAN_NILAM_Pogostemon_cablin_Benth_DARI_HUTAN_RAKYAT_DI_DESA_BONE-BONE_KECAMATAN_BARAKA_KABUPATEN_ENREKANG) ([PDF via Neliti](https://media.neliti.com/media/publications/332787-produksi-dan-rendemen-pengolahan-nilam-p-a69347e1.pdf))
- [Nilam, Primadona Tanaman Aromatik Indonesia — BBPP Lembang, Kementerian Pertanian](https://bbpplembang.bppsdmp.pertanian.go.id/publikasi-detail/1132)
- [Nilam Diklaim Lebih Menggiurkan dari Sawit, Begini Hitung-hitungannya — elaeis.co](https://www.elaeis.co/berita/baca/nilam-diklaim-lebih-menggiurkan-dari-sawit-begini-hitung-hitungannya)
- [Data produktivitas nilam Aceh Barat (240 kg/Ha) — dikutip dari pemberitaan Bisnisia.id](https://bisnisia.id/harga-minyak-nilam-aceh-tertinggi-di-indonesia-ini-penyebabnya/)
