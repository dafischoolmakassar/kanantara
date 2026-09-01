# Bundel Data Investor — KANANTARA (Koperasi Atsiri Nusantara)
## Replikasi Model ALKO untuk Komoditas Nilam (Patchouli / Minyak Atsiri)

> Dokumen ini adalah kumpulan bahan presentasi investor, disusun dari data simulasi bisnis 5 tahun KANANTARA. Setiap file membahas satu topik agar mudah dipetakan ke dalam slide deck.

---

## Daftar Isi

| # | File | Topik |
|---|---|---|
| 00 | [00-Ringkasan-Eksekutif.md](00-Ringkasan-Eksekutif.md) | Ringkasan untuk investor — masalah, solusi, angka kunci |
| 01 | [01-Konsep-Replikasi-ALKO.md](01-Konsep-Replikasi-ALKO.md) | Konsep dasar: mengapa pola ALKO direplikasi ke Nilam |
| 02 | [02-Model-Rantai-Pasok.md](02-Model-Rantai-Pasok.md) | Alur rantai pasok Petani → Buyer Internasional |
| 03 | [03-Target-Pertumbuhan-5-Tahun.md](03-Target-Pertumbuhan-5-Tahun.md) | Proyeksi petani, produksi, dan nilai penjualan |
| 04 | [04-Target-Rata-rata-Petani-dan-Pendapatan.md](04-Target-Rata-rata-Petani-dan-Pendapatan.md) | **Fokus utama**: asumsi produksi/petani + struktur & simulasi pendapatan (Harga Dasar + Premium + Bonus Loyalitas + SHU) |
| 05 | [05-Simulasi-Tahun-Pertama.md](05-Simulasi-Tahun-Pertama.md) | Simulasi keuangan Tahun 1 (500 petani) |
| 06 | [06-Dana-Stabilisasi-Harga.md](06-Dana-Stabilisasi-Harga.md) | Mekanisme dana stabilisasi harga |
| 07 | [07-Model-Loyalitas-Petani.md](07-Model-Loyalitas-Petani.md) | Strategi "Loyalty by Benefit" agar petani tidak pindah ke tengkulak |
| 08 | [08-Strategi-Eksportir-dan-Trading-Center.md](08-Strategi-Eksportir-dan-Trading-Center.md) | Diversifikasi buyer & fungsi trading center |
| 09 | [09-Traceability-dan-Blockchain.md](09-Traceability-dan-Blockchain.md) | KANANTARA TRACE™ — traceability berbasis Hyperledger Fabric |
| 10 | [10-Strategi-Investasi-dan-Roadmap.md](10-Strategi-Investasi-dan-Roadmap.md) | Fase investasi 5 tahun |
| 11 | [11-Produk-Turunan-dan-Visi-Jangka-Panjang.md](11-Produk-Turunan-dan-Visi-Jangka-Panjang.md) | Hilirisasi produk & visi akhir KANANTARA |
| 12 | [12-Digital-Dashboard.md](12-Digital-Dashboard.md) | Dashboard digital untuk petani, pengurus, dan buyer |
| 13 | [13-Proyeksi-Keuangan-5-Tahun.md](13-Proyeksi-Keuangan-5-Tahun.md) | Proyeksi P&L, arus kas, neraca 5 tahun |
| 14 | [14-Kebutuhan-Modal-dan-Return-Investor.md](14-Kebutuhan-Modal-dan-Return-Investor.md) | Capex/opex per fase, struktur pendanaan, skema return investor |
| 15 | [15-Break-Even-dan-Unit-Economics.md](15-Break-Even-dan-Unit-Economics.md) | BEP volume/harga & margin per kg per grade |
| 16 | [16-Analisis-Risiko-dan-Skenario.md](16-Analisis-Risiko-dan-Skenario.md) | Matriks risiko & skenario pesimis/moderat/optimis |
| 17 | [17-Analisis-Pasar-Global-Nilam.md](17-Analisis-Pasar-Global-Nilam.md) | Pasar global patchouli oil, kompetitor, buyer |
| 18 | [18-Dampak-Sosial-dan-ESG.md](18-Dampak-Sosial-dan-ESG.md) | Dampak pendapatan petani, SDGs, metrik impact |
| 19 | [19-Analisis-Kompetitif-dan-Benchmark.md](19-Analisis-Kompetitif-dan-Benchmark.md) | Benchmark tengkulak, ALKO, koperasi sejenis & moat |
| 20 | [20-Kapasitas-Operasional-dan-Organisasi.md](20-Kapasitas-Operasional-dan-Organisasi.md) | Kapasitas infrastruktur, struktur SDM, SOP |
| 21 | [21-Legal-Perizinan-dan-Sertifikasi.md](21-Legal-Perizinan-dan-Sertifikasi.md) | Struktur koperasi, perizinan, ekspor, sertifikasi |
| 22 | [22-Branding-origin-dan-Go-to-Market.md](22-Branding-origin-dan-Go-to-Market.md) | Brand origin Indonesia, GTM, onboarding buyer |

---

## Cara Pakai untuk Presentasi

1. Urutan file (00 → 22) sudah disusun mengikuti alur narasi investor pitch: **masalah → model → angka → mekanisme → risiko dikelola → roadmap → visi → analisis lanjutan (keuangan, modal, risiko, pasar, ESG, kompetitif, operasional, legal, GTM)**.
2. File **04** adalah inti argumen ekonomi ke petani — gunakan tabel sensitivitas pendapatan di sana sebagai slide "value proposition ke petani".
3. Setiap file bisa langsung ditempel jadi 1–2 slide; tabel sudah dalam format Markdown siap-konversi (bisa di-paste ke Google Slides/Notion/Word).
4. Sumber data mentah: `NILAM2.md` dan `NILAM2.docx` (folder induk `D:\Nilam`), serta diagram konsep `penjelasan-diagram-alko-kopi.md`.
5. Riset pasar pendukung (trend harga 10 tahun, harga terendah/tertinggi/rata-rata 5 tahun, HPP per hektar, skema koperasi, skema BPJS/asuransi/pendidikan, dan perhitungan dana cadangan per kg) ada di subfolder [Riset-Harga-HPP-dan-Skema-Koperasi/](Riset-Harga-HPP-dan-Skema-Koperasi/README.md).
6. Perbandingan dua asumsi harga jual rata-rata (Rp 1,5 juta vs Rp 1,2 juta/kg) — termasuk analisis tekanan terhadap Harga Dasar petani dan rekomendasi mitigasi — ada di subfolder [Skenario-Harga-1.5jt-vs-1.2jt/](Skenario-Harga-1.5jt-vs-1.2jt/00-Kenapa-Ada-Dua-Asumsi-Harga.md). Materi di folder induk tidak diubah — folder ini murni pembanding.

## Catatan Penting

Semua angka dalam bundel ini adalah **asumsi simulasi** untuk keperluan diskusi model bisnis, bukan angka aktual pasar. Harga jual, harga dasar, dan margin harus divalidasi ulang dengan kondisi pasar minyak nilam/atsiri terkini, kontrak buyer, dan kurs saat presentasi berlangsung.