# 16 — Analisis Risiko & Skenario

## 16.1 Matriks Risiko Utama

| # | Risiko | Dampak | Probabilitas | Mitigasi Utama |
|---|---|---|---|---|
| 1 | Harga internasional minyak nilam turun | Tinggi (surplus & kepastian harga dasar) | Sedang | Dana stabilisasi (5%), kontrak forward, multi-buyer ([08](08-Strategi-Eksportir-dan-Trading-Center.md)) |
| 2 | Fluktuasi kurs (IDR/USD) | Sedang | Tinggi | Penetapan harga dasar berkala berbasis kurs, kontrak USD, lindung nilai sederhana |
| 3 | Gangguan produksi (hama/penyakit nilam, kekeringan, iklim) | Tinggi (pasokan & kualitas) | Sedang | Pendampingan agronomi, bibit unggul, penyebaran wilayah, cadangan persediaan |
| 4 | Pasokan petani di bawah target (churn / panen kurang) | Tinggi | Sedang | Insentif loyalitas berlapis ([07](07-Model-Loyalitas-Petani.md)), target petani konservatif |
| 5 | Konsentrasi buyer | Sedang | Rendah | Target minimal 5 buyer aktif, kontrak multi-tahun |
| 6 | Risiko kualitas/QC gagal di buyer | Sedang | Sedang | Lab QC, CoA/GC-MS tiap batch, traceability ([09](09-Traceability-dan-Blockchain.md)) |
| 7 | Risiko operasional (logistik, penyimpanan, aset) | Sedang | Sedang | SOP, asuransi aset, gudang berstandar |
| 8 | Regulasi & perizinan berubah | Sedang | Rendah | Kepatuhan proaktif ([21](21-Legal-Perizinan-dan-Sertifikasi.md)) |
| 9 | Risiko teknologi (traceability/dashboard gagal) | Rendah | Sedang | Implementasi bertahap, integrasi sederhana dulu |
| 10 | Risiko kredit (buyer tidak bayar) | Sedang | Rendah | Uji tuntas buyer, letter of credit / pembayaran terjadwal |

## 16.2 Skenario Tahun 5 (dasar: 700 ton, Rp 1.500.000/kg → Rp 1.050 M)

| Skenario | Asumsi | Pendapatan Tahun 5 | Surplus (10%) | Makna |
|---|---|---|---|---|
| **Pesimis** | Harga −15% (Rp 1.275.000), volume −10% (630 ton) | Rp 803,25 M | Rp 80,33 M | Masih surplus positif; dana stabilisasi menahan harga dasar |
| **Moderat (dasar)** | Harga Rp 1.500.000, volume 700 ton | Rp 1.050,00 M | Rp 105,00 M | Sesuai proyeksi |
| **Optimis** | Harga +10% (Rp 1.650.000), volume +10% (770 ton) | Rp 1.270,50 M | Rp 127,05 M | Bonus dari kondisi pasar baik |

## 16.3 Skenario Komulatif 5 Tahun (ilustratif)

| Skenario | Pendapatan kumulatif | Surplus kumulatif |
|---|---|---|
| Pesimis (harga −15% sepanjang proyeksi, volume sesuai target) | ± Rp 2.002 M | ± Rp 194 M |
| Moderat | Rp 2.355 M | Rp 227,85 M |
| Optimis (harga +10%) | ± Rp 2.590 M | ± Rp 251 M |

*Perhitungan menyederhanakan dengan menggeser harga jual secara proporsional terhadap komitmen pembelian petani (70%); dalam praktik, dana stabilisasi ([06](06-Dana-Stabilisasi-Harga.md)) dan kontrak forward menahan dampak harga dasar saat pasar turun, sehingga dampak aktual ke surplus biasanya lebih ringan dari asumsi proporsional di atas.*

## 16.4 Sensitivitas Harga vs Volume (dampak surplus kumulatif)

| Δ Harga ↓ / Δ Volume → | −20% | −10% | 0 | +10% | +20% |
|---|---|---|---|---|---|
| **−20%** | ± Rp 146 M | ± Rp 164 M | ± Rp 182 M | ± Rp 201 M | ± Rp 219 M |
| **−10%** | ± Rp 164 M | ± Rp 185 M | ± Rp 205 M | ± Rp 226 M | ± Rp 246 M |
| **0 (dasar)** | ± Rp 182 M | ± Rp 205 M | **Rp 228 M** | ± Rp 251 M | ± Rp 273 M |
| **+10%** | ± Rp 201 M | ± Rp 226 M | ± Rp 251 M | ± Rp 276 M | ± Rp 301 M |

*Grid ilustratif (surplus kumulatif 5 tahun = 227,85 M × faktor harga × faktor volume) — menunjukkan ketahanan model: surplus tetap positif di semua kombinasi, dengan rentang ± Rp 146 M – Rp 301 M.*

## 16.5 Risk Register Prioritas untuk Mitigasi Dini

1. **Perlindungan harga** — aktifkan dana stabilisasi & mulai kontrak forward sejak Tahun 1 (buyer minimum 5).
2. **Ketahanan pasokan** — program bibit unggul & pendampingan sejak Fase 1, sebelum volume dinaikkan agresif di Tahun 2–3.
3. **Manajemen modal kerja** — pastikan struktur pendanaan mengakomodasi pembelian cepat ke petani ([14](14-Kebutuhan-Modal-dan-Return-Investor.md)).
4. **Diversifikasi** — multi-wilayah (Fase 4) mengurangi risiko gangguan iklim/hama terpusat.

## 16.6 Insight untuk Investor

- Model **tahan di skenario pesimis** berkat kombinasi dana stabilisasi, margin 7–10%, dan BEP rendah ([15](15-Break-Even-dan-Unit-Economics.md)).
- **Risiko terbesar bukan volume, melainkan harga & pasokan** — mitigasi difokuskan ke sana (kontrak buyer + program agronomi).
- Skenario optimis menambah nilai signifikan tanpa biaya tambahan — "upside gratis" bagi investor.
