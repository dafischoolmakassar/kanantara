# 09 — Traceability & Blockchain: KANANTARA TRACE™

## Mengapa Traceability

Buyer internasional membutuhkan **bukti asal produk** — semakin penting untuk pasar minyak atsiri/nilam premium yang menuntut kepastian mutu dan asal-usul (origin).

## Traceability per Batch

Setiap batch minyak atsiri dapat dilacak, contoh:

```
BATCH: KANANTARA-2026-000127
Komoditas       : Minyak Atsiri
Petani          : Kelompok A
Desa            : XXXXX
Tanggal Panen   : XXXXX
Tanggal Distilasi: XXXXX
Volume          : 250 kg
Grade           : A
Hasil QC        : LULUS
```

## Basis Teknologi: Hyperledger Fabric

**Hyperledger Fabric** adalah platform **blockchain untuk organisasi/perusahaan (permissioned blockchain)** — memungkinkan beberapa pihak berbagi satu catatan transaksi yang dapat diverifikasi bersama, **tanpa harus membuka seluruh data ke publik**. Berbeda dari Bitcoin/Ethereum (blockchain publik), peserta jaringan Fabric memiliki identitas dan hak akses tertentu.

**Penting:** *Ini bukan cryptocurrency.* **KANANTARA tidak perlu membuat coin/token.** Alur logikanya:

> **BLOCKCHAIN → TRACEABILITY → TRANSPARENCY → TRUST**
>
> (bukan) BLOCKCHAIN → CRYPTO → TRADING TOKEN

## Alur Pencatatan

```
Petani → Penyuling → KANANTARA → Laboratorium → Gudang → Eksportir → Buyer
```

## Mengapa Cocok untuk KANANTARA

| Kebutuhan KANANTARA | Fungsi Hyperledger Fabric |
|---|---|
| Transparansi harga & transaksi | Ledger bersama |
| Traceability minyak | Riwayat setiap batch |
| Data petani tidak boleh terbuka ke semua orang | Permission & private data |
| Kontrak suplai | Business rules / smart contract |
| Verifikasi kualitas | QC dapat menjadi pihak pencatat/verifikator |
| Audit | Riwayat transaksi tersedia |
| Buyer membutuhkan bukti asal produk | QR + Digital Product Passport |

## Privasi Data

Buyer internasional yang memindai **QR Code KANANTARA TRACE** memperoleh informasi yang memang diizinkan untuk publik: asal Indonesia, daerah produksi, tanggal panen/penyulingan, spesifikasi kualitas, sertifikasi, dan batch number. Informasi sensitif seperti **rekening petani, harga kontrak tertentu, atau data pribadi tidak ditampilkan** ke buyer.

## Arsitektur yang Diusulkan: KANANTARA TRACE™

*Blockchain-Powered Essential Oil Traceability*

```
Petani → QR Farm ID → Harvest ID → Distillation Batch → Laboratory QC → Warehouse → Export → Global Buyer
```

### Contoh Digital Product Passport (QR Code)

```
KANANTARA TRACE™ — Digital Product Passport
Batch ID       : KNT-PCH-SULSEL-2026-0001
Product        : Patchouli Essential Oil
Origin         : Sulawesi, Indonesia
Producer       : Kelompok Tani KANANTARA
Harvest        : Agustus 2026
Distillation   : Verified
Quality Control: PASSED
Traceability   : Blockchain Verified
Status         : Authentic Product
```

## Relevansi untuk Investor

1. **Keunggulan kompetitif di pasar essential oils dunia** — traceability terverifikasi blockchain menjadi pembeda dibanding pemasok konvensional tanpa sistem pelacakan.
2. **Tidak memerlukan investasi/risiko terkait crypto-asset** — implementasi murni sebagai infrastruktur data terpercaya (permissioned ledger), meminimalkan risiko regulasi terkait aset digital.
3. **Mendukung harga premium** — bukti origin dan QC yang terverifikasi memperkuat justifikasi Premium Mutu di struktur pendapatan petani (lihat [04](04-Target-Rata-rata-Petani-dan-Pendapatan.md)).
