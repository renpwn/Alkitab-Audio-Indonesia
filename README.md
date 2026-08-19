# 🎧 Alkitab Audio Indonesia

Koleksi file audio Alkitab dalam **Bahasa Indonesia** dan **Bahasa Daerah (Jawa)** dengan berbagai varian versi (**TB ver. Davar**, **Audio AI**, dan **Bahasa Jawa**) dalam format **MP3** dan **AMR**, bersumber dari **[AUDIO.SABDA.ORG](https://audio.sabda.org/)** — platform audio Alkitab dari Yayasan Lembaga SABDA (YLSA).

> *"Jadi, iman timbul dari pendengaran, dan pendengaran oleh firman Kristus."*
> — **Roma 10:17**

---

## 📌 Tentang Proyek

Repositori ini mengarsipkan audio Alkitab yang diorganisasikan ke dalam beberapa **branch terpisah** berdasarkan versi rekaman dan format audio:

| Versi Rekaman | Bahasa | Branch Tersedia | Jumlah Kitab | Jumlah File Audio |
|---|---|---|---|---|
| **Alkitab TB ver. Davar** | Indonesia (TB) | [`Davar-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-MP3) *(default)*, [`Davar-AMR`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-AMR) | 62 kitab (35 PL + 27 PB) | 1.077 file |
| **Alkitab Bahasa Jawa** | Bahasa Jawa | [`Jawa-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Jawa-MP3), [`Jawa-AMR`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Jawa-AMR) | 62 kitab (35 PL + 27 PB) | 1.077 file |
| **Alkitab Audio AI** | Indonesia (AYT) | [`AI-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/AI-MP3), [`AI-AMR`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/AI-AMR) | **66 kitab lengkap** (39 PL + 27 PB) | 1.189 file |

### Sumber Audio
- 🌐 Portal: [audio.sabda.org](https://audio.sabda.org/)
- 🏢 Penyedia: [Yayasan Lembaga SABDA (YLSA)](https://ylsa.org)
- 📻 Format Tersedia: `.mp3` (MP3) & `.amr` (AMR)

---

## 🌿 Penjelasan Branch GitHub

Repositori ini menggunakan **branch terpisah** untuk setiap kombinasi **versi bahasa** dan **format audio**. Klik nama branch di bawah untuk langsung menuju halaman branch di GitHub:

| Branch | Bahasa / Versi | Format | Jumlah File Audio | URL Sumber SABDA |
|---|---|---|---|---|
| [**`Davar-MP3`**](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-MP3) *(default)* | Indonesia — TB ver. Davar | `.mp3` | 1.077 file | [tb_davar](https://audio.sabda.org/bible.php?v=tb_davar) |
| [**`Davar-AMR`**](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-AMR) | Indonesia — TB ver. Davar | `.amr` | 1.077 file | [tb_davar](https://audio.sabda.org/bible.php?v=tb_davar) |
| [**`AI-MP3`**](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/AI-MP3) | Indonesia — Alkitab Yang Terbuka (AI) | `.mp3` | 1.189 file | [ai_davar](https://audio.sabda.org/bible.php?v=ai_davar) |
| [**`AI-AMR`**](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/AI-AMR) | Indonesia — Alkitab Yang Terbuka (AI) | `.amr` | 1.189 file | [ai_davar](https://audio.sabda.org/bible.php?v=ai_davar) |
| [**`Jawa-MP3`**](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Jawa-MP3) | Bahasa Jawa | `.mp3` | 1.077 file | [tb_jawa](https://audio.sabda.org/bible.php?v=tb_jawa) |
| [**`Jawa-AMR`**](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Jawa-AMR) | Bahasa Jawa | `.amr` | 1.077 file | [tb_jawa](https://audio.sabda.org/bible.php?v=tb_jawa) |

---

### 🔑 Arti Nama Branch

Nama branch terdiri dari dua bagian: **`[Versi/Bahasa]-[Format]`**

```
   Davar    -    MP3
     │            └─ Format audio: MP3 (kualitas jernih) atau AMR (kompresi hemat kuota)
     └────────────── Versi teks atau bahasa rekaman Alkitab
```

| Kode | Keterangan |
|---|---|
| `Davar` | Audio Alkitab Terjemahan Baru (TB) versi **Davar** — Narasi tunggal Bahasa Indonesia |
| `AI` | Audio Alkitab **AI** (Alkitab Yang Terbuka) — Bahasa Indonesia, memuat kitab PL secara lengkap 39 kitab |
| `Jawa` | Audio Alkitab dalam **Bahasa Jawa** — Rekaman pembacaan Alkitab terjemahan Basa Jawa |
| `MP3` | Format **MPEG Audio Layer 3** — Kualitas audio jernih, ukuran file ~1–4 MB per pasal |
| `AMR` | Format **Adaptive Multi-Rate** — Format audio kompresi tinggi, ukuran sangat kecil (ringan diunduh/kuota hemat) |

---

### 📊 Perbedaan Utama Antar Branch

| Aspek | Branch `Davar-MP3` / `Davar-AMR` | Branch `Jawa-MP3` / `Jawa-AMR` | Branch `AI-MP3` / `AI-AMR` |
|---|---|---|---|
| **Bahasa** | Bahasa Indonesia (TB) | Bahasa Jawa (*Basa Jawa*) | Bahasa Indonesia (AYT / AI) |
| **Versi SABDA** | `tb_davar` | `tb_jawa` | `ai_davar` |
| **Jumlah Kitab PL** | 35 kitab | 35 kitab | **39 kitab (Lengkap)** |
| **Kitab PL yang Tidak Ada** | 1 & 2 Raja-raja, 1 & 2 Tawarikh | 1 & 2 Raja-raja, 1 & 2 Tawarikh | *Tidak ada (Semua 39 kitab lengkap)* |
| **Jumlah Kitab PB** | 27 kitab (Lengkap) | 27 kitab (Lengkap) | 27 kitab (Lengkap) |
| **Total Kitab** | 62 kitab | 62 kitab | **66 kitab (Lengkap)** |
| **Total File Audio** | 1.077 file (817 PL + 260 PB) | 1.077 file (817 PL + 260 PB) | 1.189 file (929 PL + 260 PB) |
| **Format File** | `.mp3` (MP3) / `.amr` (AMR) | `.mp3` (MP3) / `.amr` (AMR) | `.mp3` (MP3) / `.amr` (AMR) |

```
[Davar-MP3 / Davar-AMR] ──> Bahasa Indonesia (TB Davar) ── 35 PL + 27 PB = 1.077 file
[Jawa-MP3  / Jawa-AMR ] ──> Bahasa Jawa                 ── 35 PL + 27 PB = 1.077 file
[AI-MP3    / AI-AMR   ] ──> Bahasa Indonesia (Audio AI) ── 39 PL + 27 PB = 1.189 file (Lengkap)
```

> 💡 **Branch Default**: Repositori ini secara default membuka branch **[`Davar-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-MP3)**.

---

## 📡 Tentang AUDIO.SABDA.ORG & Penjelasan Versi Audio

**[AUDIO.SABDA.ORG](https://audio.sabda.org/)** adalah situs resmi dari Yayasan Lembaga SABDA (YLSA) yang menyediakan ragam versi dan bahasa Alkitab Perjanjian Baru dan Perjanjian Lama dalam format audio.

### Versi yang tersedia di situs SABDA (sebagian):

| Kode URL (`?v=`) | Nama Versi di SABDA | Keterangan di Repositori Ini |
|---|---|---|
| `tb_davar` | **Alkitab TB ver. Davar** | Branch [`Davar-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-MP3) & [`Davar-AMR`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Davar-AMR) |
| `tb_jawa` | **Alkitab Bahasa Jawa** | Branch [`Jawa-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Jawa-MP3) & [`Jawa-AMR`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/Jawa-AMR) |
| `ai_davar` | **Alkitab Yang Terbuka 'Audio AI'** | Branch [`AI-MP3`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/AI-MP3) & [`AI-AMR`](https://github.com/renpwn/Alkitab-Audio-Indonesia/tree/AI-AMR) |
| `tb_alkitabsuara` | Alkitab TB 'Alkitab Suara' | Superdrama Alkitab Terjemahan Baru |
| `tb` | Alkitab TB Drama | Drama Alkitab Terjemahan Baru |
| `tb_otnt` | Alkitab TB Non Drama | Non Drama Alkitab Terjemahan Baru |
| `bis` | Alkitab BIS | Bahasa Indonesia Sehari-hari |
| `amd-ai` | Alkitab Mudah Dibaca 'Audio AI' | Versi AMD narasi AI |
| `avb` | Alkitab Versi Borneo | Bahasa Melayu Borneo |

---

### 📖 Penjelasan Versi yang Tersedia di Repositori:

#### 1. Versi TB Davar (`Davar-MP3` / `Davar-AMR`)
- **Arti Nama**: **Davar** (דָּבָר) adalah kata bahasa Ibrani yang berarti *"Firman"* atau *"Kata"*.
- **Teks**: Alkitab Terjemahan Baru (TB) edisi resmi LAI.
- **Karakteristik Audio**: Pembacaan teks secara narasi tunggal (non-drama), lugas, dan terstruktur.
- **Cakupan**: Memuat 35 Kitab PL dan 27 Kitab PB (total 62 kitab / 1.077 pasal). Kitab 1–2 Raja-raja dan 1–2 Tawarikh tidak disertakan dalam versi ini.

#### 2. Versi Audio AI / Alkitab Yang Terbuka (`AI-MP3` / `AI-AMR`)
- **Arti Nama**: **Audio AI** bersumber dari teks *Alkitab Yang Terbuka* (AYT) dengan teknologi narasi audio modern/AI dari SABDA.
- **Teks**: Alkitab Yang Terbuka (AYT) — terjemahan setia, akurat, dan mudah dipahami.
- **Karakteristik Audio**: Suara narasi yang konsisten dan jelas di seluruh pasal.
- **Cakupan**: **Lengkap 66 Kitab** (39 Kitab PL + 27 Kitab PB / 1.189 pasal), termasuk kitab 1 & 2 Raja-raja serta 1 & 2 Tawarikh.

#### 3. Versi Bahasa Jawa (`Jawa-MP3` / `Jawa-AMR`)
- **Arti Nama**: Audio Alkitab dalam bahasa daerah nusantara yaitu **Bahasa Jawa** (*Basa Jawa*).
- **Teks**: Terjemahan Alkitab Basa Jawa yang diterbitkan untuk penutur bahasa Jawa.
- **Karakteristik Audio**: Pembacaan Alkitab penutur asli Bahasa Jawa dengan intonasi dan pelafalan bahasa Jawa yang fasih.
- **Cakupan**: Memuat 35 Kitab PL dan 27 Kitab PB (total 62 kitab / 1.077 pasal), sejajar dengan struktur versi Davar.

---

## 📁 Struktur Direktori per Branch

### 1️⃣ Struktur Direktori Branch `Davar-MP3`, `Davar-AMR`, `Jawa-MP3`, & `Jawa-AMR` (62 Kitab)

Pada branch **`Davar-MP3`** (ekstensi `.mp3`), **`Davar-AMR`** (ekstensi `.amr`), **`Jawa-MP3`** (ekstensi `.mp3`), dan **`Jawa-AMR`** (ekstensi `.amr`), koleksi memuat **35 Kitab PL** (tanpa Raja-raja & Tawarikh) dan **27 Kitab PB**:

```
Alkitab-Audio-Indonesia/
│
├── Perjanjian Lama/                    # 35 Kitab PL (817 file)
│   ├── 01_kejadian/                    # 50 pasal (01_kej01 s/d 01_kej50)
│   ├── 02_keluaran/                    # 40 pasal
│   ├── 03_imamat/                      # 27 pasal
│   ├── 04_bilangan/                    # 36 pasal
│   ├── 05_ulangan/                     # 34 pasal
│   ├── 06_yosua/                       # 24 pasal
│   ├── 07_hakim/                       # 21 pasal
│   ├── 08_rut/                         # 4 pasal
│   ├── 09_1samuel/                     # 31 pasal
│   ├── 10_2samuel/                     # 24 pasal
│   ├── 15_ezra/                        # 10 pasal (No. 11-14 Raja/Tawarikh tidak ada)
│   ├── 16_nehemia/                     # 13 pasal
│   ├── 17_esther/                      # 10 pasal
│   ├── 18_ayub/                        # 42 pasal
│   ├── 19_mazmur/                      # 150 pasal
│   ├── 20_amsal/                       # 31 pasal
│   ├── 21_pengkhotbah/                 # 12 pasal
│   ├── 22_kidung/                      # 8 pasal
│   ├── 23_yesaya/                      # 66 pasal
│   ├── 24_yeremia/                     # 52 pasal
│   ├── 25_ratapan/                     # 5 pasal
│   ├── 26_yehezkiel/                   # 48 pasal
│   ├── 27_daniel/                      # 12 pasal
│   ├── 28_hosea/                       # 14 pasal
│   ├── 29_yoel/                        # 3 pasal
│   ├── 30_amos/                        # 9 pasal
│   ├── 31_obaja/                       # 1 pasal
│   ├── 32_yunus/                       # 4 pasal
│   ├── 33_mikha/                       # 7 pasal
│   ├── 34_nahum/                       # 3 pasal
│   ├── 35_habakuk/                     # 3 pasal
│   ├── 36_zefanya/                     # 3 pasal
│   ├── 37_hagai/                       # 2 pasal
│   ├── 38_zakharia/                    # 14 pasal
│   └── 39_maleakhi/                    # 4 pasal
│
└── Perjanjian Baru/                    # 27 Kitab PB (260 file)
    ├── 01_matius/                      # 28 pasal (01_mat01 s/d 01_mat28)
    ├── 02_markus/                      # 16 pasal
    ├── 03_lukas/                       # 24 pasal
    ├── 04_yohanes/                     # 21 pasal
    ├── 05_kisah/                       # 28 pasal
    ├── 06_roma/                        # 16 pasal
    ├── 07_1korintus/                   # 16 pasal
    ├── 08_2korintus/                   # 13 pasal
    ├── 09_galatia/                     # 6 pasal
    ├── 10_efesus/                      # 6 pasal
    ├── 11_filipi/                      # 4 pasal
    ├── 12_kolose/                      # 4 pasal
    ├── 13_1tesalonika/                 # 5 pasal
    ├── 14_2tesalonika/                 # 3 pasal
    ├── 15_1timotius/                   # 6 pasal
    ├── 16_2timotius/                   # 4 pasal
    ├── 17_titus/                       # 3 pasal
    ├── 18_filemon/                     # 1 pasal
    ├── 19_ibrani/                      # 13 pasal
    ├── 20_yakobus/                     # 5 pasal
    ├── 21_1petrus/                     # 5 pasal
    ├── 22_2petrus/                     # 3 pasal
    ├── 23_1yohanes/                    # 5 pasal
    ├── 24_2yohanes/                    # 1 pasal
    ├── 25_3yohanes/                    # 1 pasal
    ├── 26_yudas/                       # 1 pasal
    └── 27_wahyu/                       # 22 pasal
```

---

### 2️⃣ Struktur Direktori Branch `AI-MP3` & `AI-AMR` (Lengkap 66 Kitab)

Pada branch **`AI-MP3`** dan **`AI-AMR`**, seluruh **39 Kitab PL** tersedia secara lengkap termasuk kitab Raja-raja dan Tawarikh (ekstensi file `.mp3` atau `.amr`):

```
Alkitab-Audio-Indonesia/ (Branch AI-MP3 / AI-AMR)
│
├── Perjanjian Lama/                    # 39 Kitab PL Lengkap (929 file)
│   ├── 01_kejadian/ ... 10_2samuel/
│   ├── 11_1raja/                       # 22 pasal ✨ (Tersedia di branch AI)
│   ├── 12_2raja/                       # 25 pasal ✨ (Tersedia di branch AI)
│   ├── 13_1tawarikh/                   # 29 pasal ✨ (Tersedia di branch AI)
│   ├── 14_2tawarikh/                   # 36 pasal ✨ (Tersedia di branch AI)
│   ├── 15_ezra/ ... 39_maleakhi/
│
└── Perjanjian Baru/                    # 27 Kitab PB Lengkap (260 file)
```

---

## 🏷️ Konvensi Penamaan File

Setiap file audio mengikuti pola penamaan yang konsisten:

```
{no_urut_kitab}_{kode_kitab}{no_pasal}.mp3
```

**Contoh:**

| File | Keterangan |
|---|---|
| `01_kej01.mp3` | Kitab Kejadian, Pasal 1 |
| `01_kej50.mp3` | Kitab Kejadian, Pasal 50 |
| `19_mzm150.mp3` | Kitab Mazmur, Pasal 150 |
| `01_mat01.mp3` | Injil Matius, Pasal 1 |
| `27_why22.mp3` | Kitab Wahyu, Pasal 22 |

### Kode Singkatan Kitab

#### Perjanjian Lama

| No | Nama Kitab | Kode | Pasal |
|---|---|---|---|
| 01 | Kejadian | `kej` | 50 |
| 02 | Keluaran | `kel` | 40 |
| 03 | Imamat | `im` | 27 |
| 04 | Bilangan | `bil` | 36 |
| 05 | Ulangan | `ul` | 34 |
| 06 | Yosua | `yos` | 24 |
| 07 | Hakim-hakim | `hak` | 21 |
| 08 | Rut | `rut` | 4 |
| 09 | 1 Samuel | `1sam` | 31 |
| 10 | 2 Samuel | `2sam` | 24 |
| 11 | 1 Raja-raja *(khusus branch AI)* | `1ra` | 22 |
| 12 | 2 Raja-raja *(khusus branch AI)* | `2ra` | 25 |
| 13 | 1 Tawarikh *(khusus branch AI)* | `1ta` | 29 |
| 14 | 2 Tawarikh *(khusus branch AI)* | `2ta` | 36 |
| 15 | Ezra | `ezr` | 10 |
| 16 | Nehemia | `neh` | 13 |
| 17 | Ester / Esther | `est` | 10 |
| 18 | Ayub | `ayb` | 42 |
| 19 | Mazmur | `mzm` | 150 |
| 20 | Amsal | `ams` | 31 |
| 21 | Pengkhotbah | `pkh` | 12 |
| 22 | Kidung Agung | `kid` | 8 |
| 23 | Yesaya | `yes` | 66 |
| 24 | Yeremia | `yer` | 52 |
| 25 | Ratapan | `rat` | 5 |
| 26 | Yehezkiel | `yeh` | 48 |
| 27 | Daniel | `dan` | 12 |
| 28 | Hosea | `hos` | 14 |
| 29 | Yoel | `yl` | 3 |
| 30 | Amos | `am` | 9 |
| 31 | Obaja | `ob` | 1 |
| 32 | Yunus | `yun` | 4 |
| 33 | Mikha | `mi` | 7 |
| 34 | Nahum | `nah` | 3 |
| 35 | Habakuk | `hab` | 3 |
| 36 | Zefanya | `zef` | 3 |
| 37 | Hagai | `hag` | 2 |
| 38 | Zakharia | `za` | 14 |
| 39 | Maleakhi | `mal` | 4 |

#### Perjanjian Baru

| No | Nama Kitab | Kode | Pasal |
|---|---|---|---|
| 01 | Matius | `mat` | 28 |
| 02 | Markus | `mrk` | 16 |
| 03 | Lukas | `luk` | 24 |
| 04 | Yohanes | `yoh` | 21 |
| 05 | Kisah Para Rasul | `kis` | 28 |
| 06 | Roma | `rm` | 16 |
| 07 | 1 Korintus | `1kor` | 16 |
| 08 | 2 Korintus | `2kor` | 13 |
| 09 | Galatia | `gal` | 6 |
| 10 | Efesus | `ef` | 6 |
| 11 | Filipi | `flp` | 4 |
| 12 | Kolose | `kol` | 4 |
| 13 | 1 Tesalonika | `1tes` | 5 |
| 14 | 2 Tesalonika | `2tes` | 3 |
| 15 | 1 Timotius | `1tim` | 6 |
| 16 | 2 Timotius | `2tim` | 4 |
| 17 | Titus | `tit` | 3 |
| 18 | Filemon | `flm` | 1 |
| 19 | Ibrani | `ibr` | 13 |
| 20 | Yakobus | `yak` | 5 |
| 21 | 1 Petrus | `1ptr` | 5 |
| 22 | 2 Petrus | `2ptr` | 3 |
| 23 | 1 Yohanes | `1yoh` | 5 |
| 24 | 2 Yohanes | `2yoh` | 1 |
| 25 | 3 Yohanes | `3yoh` | 1 |
| 26 | Yudas | `yud` | 1 |
| 27 | Wahyu | `why` | 22 |

---

## 🔗 Tautan Langsung Sumber

Setiap kitab pada masing-masing versi dapat diakses langsung dari situs AUDIO.SABDA.ORG dengan format URL berikut:

```
https://audio.sabda.org/bible.php?v={kode_versi}&b={kode_kitab}
```

**Contoh Akses per Versi:**
- **Versi TB Davar**: [Kejadian](https://audio.sabda.org/bible.php?v=tb_davar&b=kej) (`v=tb_davar&b=kej`), [Matius](https://audio.sabda.org/bible.php?v=tb_davar&b=mat) (`v=tb_davar&b=mat`)
- **Versi AI (Alkitab Yang Terbuka)**: [Kejadian](https://audio.sabda.org/bible.php?v=ai_davar&b=kej) (`v=ai_davar&b=kej`), [1 Raja-raja](https://audio.sabda.org/bible.php?v=ai_davar&b=1raj) (`v=ai_davar&b=1raj`)
- **Versi Bahasa Jawa**: [Kejadian (Purwaning Dumadi)](https://audio.sabda.org/bible.php?v=tb_jawa&b=kej) (`v=tb_jawa&b=kej`), [Matius](https://audio.sabda.org/bible.php?v=tb_jawa&b=mat) (`v=tb_jawa&b=mat`)

---

## 📋 Catatan Tambahan

- **Perbedaan Kelengkapan Kitab**:
  - Pada branch **`Davar-MP3`**, **`Davar-AMR`**, **`Jawa-MP3`**, dan **`Jawa-AMR`**, penomoran folder PL melewati nomor **11–14** (kitab Raja-raja & Tawarikh tidak tersedia dalam rekaman versi ini).
  - Pada branch **`AI-MP3`** dan **`AI-AMR`**, seluruh **66 kitab (39 PL + 27 PB)** tersedia secara lengkap.
- **Dukungan Format**:
  - Format `.mp3` direkomendasikan untuk kualitas audio jernih dan kompatibilitas pemutar musik universal.
  - Format `.amr` direkomendasikan untuk perangkat seluler atau penggunaan hemat ruang/kuota.
- **Rencana Mendengar**: Audio ini cocok digunakan untuk program pendengaran Alkitab SABDA: **40 hari**, **60 hari**, maupun **90 hari**.

---

## 🏢 Tentang SABDA Audio

[SABDA audio](https://audio.sabda.org/) adalah situs yang menyediakan ragam versi dan bahasa Alkitab Perjanjian Baru dan Perjanjian Lama dalam format audio, dilengkapi bahan studi untuk mempelajari Alkitab secara lebih mendalam.

- 📷 Instagram: [@sabda_ylsa](https://instagram.com/sabda_ylsa)
- 📘 Facebook: [Yayasan Lembaga SABDA](https://facebook.com/sabda.org)
- ▶️ YouTube: [SABDA Alkitab](https://www.youtube.com/@sabdaalkitab)
- 🎙️ Podcast: [podcast.sabda.org](https://podcast.sabda.org/)
- 📧 Email: [ylsa@sabda.org](mailto:ylsa@sabda.org)
- 💬 WA: [0881-2979-100](https://wa.me/628812979100)

---

*© 2021–2025 [Yayasan Lembaga SABDA (YLSA)](https://ylsa.org). All Rights Reserved.*
