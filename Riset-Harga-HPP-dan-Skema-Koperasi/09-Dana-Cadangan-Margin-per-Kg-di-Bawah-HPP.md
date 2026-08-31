# 09 — Dana Cadangan per Kg: Menjamin Margin Petani Saat Harga Jual di Bawah HPP

> **Pertanyaan sumber**: *"Hasil kelola data poin 1 s.d 6, berapakah nilai rupiah terbaik yang disisihkan dalam setiap kilogram transaksi Nilam yang akan kemudian digunakan sebagai dana cadangan untuk menjamin petani tetap ada margin saat menjual di harga terendah di bawah harga HPP yang telah ditentukan?"* — Ust Ranto, Bendahara YDF

## Ringkasan Jawaban

> **Rekomendasi: Rp 60.000 – 90.000 disisihkan per kg transaksi** (setara **5–6% dari harga jual referensi Rp 1.200.000–1.500.000/kg**), dengan **skema penyisihan progresif** (bukan persentase flat) — porsi lebih besar disisihkan saat harga sedang tinggi, porsi lebih kecil (atau nol) saat harga sedang rendah, karena dana justru dibutuhkan saat harga rendah, bukan saat harga tinggi.

Angka ini **memvalidasi ulang** — dan sedikit menyempurnakan — asumsi awal "Dana Stabilisasi Atsiri 5% dari nilai transaksi" yang sudah ada pada model dasar KANANTARA (lihat `05-Simulasi-Tahun-Pertama.md` dan `06-Dana-Stabilisasi-Harga.md` di folder induk).

---

## Langkah 1 — Mendefinisikan Ulang "HPP yang Telah Ditentukan"

Ada **dua kemungkinan makna HPP** yang perlu dibedakan dengan jelas, karena keduanya menghasilkan rekomendasi yang sangat berbeda:

| Definisi | Nilai (dari riset poin 6) | Risiko Tembus |
|---|---|---|
| **(A) Biaya produksi riil petani (cash cost)** | ± Rp 28.000 – 150.000/kg (estimasi konservatif dari data Aceh, lihat `06-Harga-Pokok-Produksi-per-Hektar.md`) | **Jarang tembus** — bahkan harga terendah historis (Rp 500.000–600.000/kg, September 2022, lihat `02-Harga-Terendah-Nilam-5-Tahun-Terakhir.md`) masih **3–10x lipat** di atas level ini |
| **(B) Harga Dasar yang dijanjikan KANANTARA ke petani** | Rp 1.000.000/kg (contoh simulasi, lihat `04-Target-Rata-rata-Petani-dan-Pendapatan.md`) | **Berpotensi tembus** saat harga jual pasar KANANTARA sendiri turun ke titik rendah historis (Rp 500.000–900.000/kg) |

**Kesimpulan penting**: Risiko nyata yang perlu diasuransikan **bukan** petani jatuh ke bawah biaya produksi riil (itu jarang terjadi berdasarkan data historis) — melainkan **KANANTARA gagal memenuhi janji Harga Dasar ke petani** karena harga jual ke buyer sedang anjlok. **Dana cadangan ini pada dasarnya melindungi KREDIBILITAS JANJI KANANTARA**, bukan sekadar "margin petani" dalam pengertian akuntansi murni. Ini konsisten dengan definisi (B) — dan seterusnya file ini memakai definisi (B) sebagai dasar hitung.

---

## Langkah 2 — Menghitung Potensi "Gap" yang Harus Ditutup Dana Cadangan

Menggunakan data harga dari poin 1–5 (lihat file `01`–`05`):

| Skenario | Harga Jual Pasar (Rp/kg) | Harga Dasar Dijanjikan (Rp/kg) | Gap per kg |
|---|---|---|---|
| Krisis berat (harga terendah historis) | 500.000 – 600.000 | 1.000.000 | **Rp 400.000 – 500.000** |
| Koreksi tajam (awal 2026) | 700.000 – 900.000 | 1.000.000 | Rp 100.000 – 300.000 |
| Normal (modus historis) | 700.000 – 900.000 | 1.000.000 | Rp 100.000 – 300.000 |
| Rata-rata konservatif | 1.000.000 – 1.100.000 | 1.000.000 | ± Rp 0 (impas) |
| Boom (2024–2025) | 1.500.000 – 2.300.000 | 1.000.000 | **Surplus**, bukan gap |

## Langkah 3 — Estimasi Frekuensi Skenario Krisis

Dari 9 titik data harga (2017–2026, lihat `01-Trend-Harga-Nilam-10-Tahun-Terakhir.md`):

- **2 dari ± 9 tahun** menunjukkan harga di titik rendah krisis (Sept 2022, awal 2026) → **± 20–25% probabilitas tahunan** kondisi harga jatuh signifikan di bawah Harga Dasar.
- Periode boom (harga di atas Rp 1,3 juta) tercatat ± 1,5 tahun dari 9 tahun data → **± 15–17%** dari waktu.
- Sisanya (± 60%) berada di kondisi "normal" mendekati atau sedikit di atas Harga Dasar.

## Langkah 4 — Kalkulasi Kebutuhan Dana Cadangan (Metode Amortisasi Risiko)

Rumus dasar: **Kebutuhan cadangan per kg (rata-rata) = Probabilitas krisis × Gap rata-rata saat krisis**

```
Kebutuhan cadangan per kg ≈ 22% × Rp 450.000/kg (titik tengah gap krisis Rp400rb–500rb)
                           ≈ Rp 99.000/kg
```

Dengan **margin keamanan tambahan** (fund tidak boleh pas-pasan; perlu buffer untuk kejadian back-to-back atau krisis lebih dalam dari histori 5 tahun), rentang yang disarankan: **Rp 90.000 – 120.000/kg** sebagai kebutuhan cadangan **jika dihitung murni dari skenario krisis penuh (gap Rp400–500rb)**.

Namun, dalam praktiknya, KANANTARA tidak wajib mempertahankan Harga Dasar **statis** — sesuai catatan `06-Dana-Stabilisasi-Harga.md`, Harga Dasar **"diumumkan secara berkala"** dan dapat disesuaikan turun sebagian saat krisis (tidak 1:1 mengikuti pasar, tapi juga tidak kaku 100%). Jika Harga Dasar diperbolehkan turun **hingga 30–40% dari level normal** saat krisis (bukan dipertahankan penuh), maka gap riil yang perlu ditutup dana cadangan **menyusut menjadi ± Rp 150.000–250.000/kg**, dan kebutuhan cadangan turun proporsional menjadi:

```
Kebutuhan cadangan per kg (skenario Harga Dasar fleksibel) ≈ 22% × Rp 200.000/kg ≈ Rp 44.000/kg
```

## Langkah 5 — Rekonsiliasi dengan Asumsi 5% yang Sudah Ada

Model dasar KANANTARA sudah mengasumsikan **Dana Stabilisasi Atsiri = 5% dari nilai transaksi**. Pada harga jual referensi Rp 1.500.000/kg (asumsi simulasi 5 tahun), ini setara:

```
5% × Rp 1.500.000/kg = Rp 75.000/kg
```

**Angka Rp 75.000/kg ini berada tepat di tengah rentang hasil kalkulasi Langkah 4 (Rp 44.000 – 120.000/kg)** — artinya **asumsi 5% yang sudah ada di model KANANTARA cukup solid dan tervalidasi** oleh data pasar yang baru dikumpulkan, dengan catatan penting di Langkah 6.

## Langkah 6 — Masalah Desain Kritis: Persentase Flat Justru Melemah Saat Paling Dibutuhkan

**Temuan penting**: skema "5% dari nilai transaksi" **secara matematis lemah tepat di saat dibutuhkan**, karena:

- Saat harga **tinggi** (Rp 1.500.000–2.300.000/kg): 5% menghasilkan **Rp 75.000 – 115.000/kg** disisihkan → banyak.
- Saat harga **rendah** (Rp 500.000–700.000/kg, justru saat dana paling dibutuhkan untuk menutup gap ke Harga Dasar): 5% hanya menghasilkan **Rp 25.000 – 35.000/kg** → sedikit, padahal gap yang harus ditutup justru sedang membesar.

Ini adalah **kelemahan struktural skema flat-percentage** untuk instrumen stabilisasi harga.

### Rekomendasi: Skema Penyisihan Progresif/Kontra-Siklikal

| Kondisi Harga Pasar | % Disisihkan | Rp/kg (indikatif) | Rasional |
|---|---|---|---|
| **Boom** (> Rp 1.300.000/kg) | 8–10% | Rp 104.000 – 230.000 | Akumulasi agresif saat surplus besar, tanpa terasa berat bagi petani (harga masih sangat tinggi) |
| **Normal** (Rp 900.000 – 1.300.000/kg) | 5–6% | Rp 45.000 – 78.000 | Baseline sesuai asumsi awal model |
| **Rendah/Modus** (Rp 700.000 – 900.000/kg) | 2–3% | Rp 14.000 – 27.000 | Minim penyisihan, fokus jaga arus kas petani |
| **Krisis** (< Rp 700.000/kg) | 0% — dana **ditarik**, bukan disisihkan | — | Fund payout mode: dana cadangan dipakai menutup gap ke Harga Dasar |

## Rekomendasi Akhir

| Item | Nilai |
|---|---|
| **Nilai disisihkan (baseline/normal price)** | **Rp 60.000 – 90.000/kg** |
| **Metode terbaik** | Skema **progresif/kontra-siklikal** (Langkah 6), bukan flat 5% |
| **Ekuivalen sederhana bila tetap ingin memakai flat rate** | **6%** dari nilai transaksi (sedikit di atas 5% awal, untuk memberi buffer keamanan tambahan) |
| **Syarat tambahan** | Modal awal (seed capital) untuk Dana Stabilisasi dari investor Tahun 1, karena dana hasil akumulasi transaksi murni **baru cukup dalam setelah 2–3 tahun operasi** (lihat Langkah 7) |

## Langkah 7 — Mengapa Perlu Suntikan Modal Awal, Bukan Hanya Akumulasi Internal

Simulasi Tahun 1 (`05-Simulasi-Tahun-Pertama.md`): volume 50.000 kg, dana stabilisasi terkumpul murni dari transaksi = 5% × Rp 75 miliar = **Rp 3,75 miliar**.

Jika krisis harga (gap ± Rp 450.000/kg) terjadi **di Tahun 1 atau 2** (saat dana cadangan belum sempat terakumulasi penuh) dan mengenai, misalnya, 30% dari volume tahun tersebut (15.000 kg dari 50.000 kg):

```
Kebutuhan dana talangan = 15.000 kg × Rp 450.000/kg = Rp 6,75 miliar
```

Ini **melebihi** dana stabilisasi yang baru terkumpul (Rp 3,75 miliar) di tahun yang sama. **Implikasi untuk investor**: sebagian dari kebutuhan modal awal (lihat `14-Kebutuhan-Modal-dan-Return-Investor.md` jika tersedia di folder induk) sebaiknya mengalokasikan **dana talangan awal (seed reserve) sebesar ± Rp 3–5 miliar** khusus untuk Dana Stabilisasi, agar janji Harga Dasar tetap kredibel sejak tahun-tahun awal operasi — sebelum akumulasi internal cukup dalam untuk berdiri sendiri (diproyeksikan tercapai sekitar Tahun 3, seiring volume tumbuh ke 250 ton/tahun).

## Referensi

- Data harga (poin 1–5): [01-Trend-Harga-Nilam-10-Tahun-Terakhir.md](01-Trend-Harga-Nilam-10-Tahun-Terakhir.md), [02-Harga-Terendah-Nilam-5-Tahun-Terakhir.md](02-Harga-Terendah-Nilam-5-Tahun-Terakhir.md), [03-Harga-Tertinggi-Nilam-5-Tahun-Terakhir.md](03-Harga-Tertinggi-Nilam-5-Tahun-Terakhir.md), [04-Harga-Paling-Sering-Terjadi-Modus.md](04-Harga-Paling-Sering-Terjadi-Modus.md), [05-Harga-Rata-rata-Nilam-5-Tahun-Terakhir.md](05-Harga-Rata-rata-Nilam-5-Tahun-Terakhir.md)
- Data HPP (poin 6): [06-Harga-Pokok-Produksi-per-Hektar.md](06-Harga-Pokok-Produksi-per-Hektar.md)
- Model dasar Dana Stabilisasi (5% dari nilai transaksi) dan struktur harga: `05-Simulasi-Tahun-Pertama.md`, `06-Dana-Stabilisasi-Harga.md`, `04-Target-Rata-rata-Petani-dan-Pendapatan.md` (folder induk)

## Catatan Penting — Batasan Perhitungan

Perhitungan pada file ini adalah **model finansial sintesis (financial engineering)** berbasis data historis terbatas (9 titik data harga selama 2017–2026, lihat catatan metodologi di `01-Trend-Harga-Nilam-10-Tahun-Terakhir.md`), **bukan hasil aktuaria formal**. Sebelum dijadikan kebijakan resmi dana cadangan:

1. Libatkan **aktuaris/konsultan keuangan koperasi** untuk memvalidasi probabilitas krisis dan ukuran gap dengan data time-series yang lebih panjang dan granular.
2. Uji skema progresif ini dengan **simulasi Monte Carlo** sederhana menggunakan variasi skenario harga, bukan hanya titik-titik historis yang tersedia.
3. Tinjau ulang setiap tahun berdasarkan **realisasi transaksi Trading Center KANANTARA sendiri**, yang akan menjadi sumber data primer paling akurat setelah operasi berjalan.
