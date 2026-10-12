# Penggunaan AI

| | |
|---|---|
| **Nama** | Ivan Dika Pratama |
| **NIM** | 252011082 |
| **Kelas** | IT - Eksekutif |
| **Tugas** | Softskill 1 (Individu) — Bedah Sistem Informasi & Repository Profesional Pertamaku |
| **Acuan** | Lembar tugas Bagian 7 (Kebijakan Penggunaan AI) dan Bagian 4 (Etika review) |
| **Tanggal** | 12 Oktober 2026 |

## Daftar isi

- [Penggunaan AI](#penggunaan-ai)
  - [Daftar isi](#daftar-isi)
  - [1. Kebijakan yang saya pegang](#1-kebijakan-yang-saya-pegang)
  - [2. Alat AI yang dipakai](#2-alat-ai-yang-dipakai)
  - [3. Log penggunaan](#3-log-penggunaan)
  - [4. Data yang terlihat oleh AI](#4-data-yang-terlihat-oleh-ai)
  - [5. Verifikasi hasil AI](#5-verifikasi-hasil-ai)
  - [6. Pembagian peran: manusia dan AI](#6-pembagian-peran-manusia-dan-ai)
  - [7. Batasan dan hal yang tidak dilakukan](#7-batasan-dan-hal-yang-tidak-dilakukan)
  - [8. Pernyataan](#8-pernyataan)

## 1. Kebijakan yang saya pegang

**AI boleh dipakai untuk:**
- memperbaiki bahasa;
- mencari ide pertanyaan analisis;
- memberi contoh format dokumen (mis. komitmen kerja, kerangka README);
- membantu pekerjaan teknis non-analisis (struktur berkas, tabel, diagram, penyusunan dokumen).

**AI tidak dipakai untuk:**
- mengarang temuan atau bukti;
- menulis analisis tanpa saya benar-benar memakai sistemnya;
- mengolah screenshot yang berisi data pribadi tanpa pemotongan atau penyamaran terlebih dahulu.

**Aturan tambahan:**
- Setiap penggunaan AI dicatat di bagian 3.
- Keluaran AI saya baca, ubah seperlunya, dan cocokkan dengan pengamatan saya sendiri sebelum dipakai.
- Penggunaan yang tidak dilaporkan, atau laporan yang mirip dengan mahasiswa lain, dapat dianggap pelanggaran integritas akademik.

## 2. Alat AI yang dipakai

| Alat | Peran |
|---|---|
| **Claude Code** (Anthropic) | Perencana dan reviewer: membaca lembar tugas, menyusun struktur Git dan daftar pekerjaan proses analisis, mereview struktur dokumen dan klaim saya, serta merapikan dokumen. |
| **Codex / ChatGPT** | Pembantu teknis: mengolah dokumen lokal, menyusun struktur portofolio lokal, membuat diagram di DOCX, mengambil screenshot dari browser pada akun yang saya izinkan, dan membuat gambar sampul. |

Tidak ada instalasi alat tambahan atau konektor eksternal tambahan yang digunakan di luar yang tercantum di atas.

## 3. Log penggunaan

| # | Tanggal | Alat | Dipakai untuk | Data yang terlibat | Cara verifikasi |
|---|---|---|---|---|---|
| 1 | 12 Okt 2026 08:45 | Claude Code | Membaca lembar tugas, merangkum ketentuan, menyusun rencana pengerjaan, dan membuat struktur Git serta draf README, komitmen kerja, penggunaan AI, dan lisensi | Isi lembar tugas dosen; identitas (nama, NIM, kelas, dosen, username GitHub) | Draf saya baca ulang dan isian saya lengkapi atau ubah sendiri |
| 2 | 12 Okt 2026 10:35 | Claude Code | Mereview klaim saya pada profil sistem dan bagian analisis (memberi masukan, bukan menulis temuan); memverifikasi secara read-only beberapa klaim terhadap halaman sistem setelah saya login sendiri | Hasil saya bandingkan dengan UI dan screenshot sendiri; koreksi saya terapkan pada tulisan saya |
| 3 | 12 Okt 2026 10:45 | Claude Code | Merapikan dokumen laporan: format, daftar isi bertaut, tautan subpath, rujukan Gambar bertaut, dan penyesuaian kalimat | Isi laporan | Hasil saya periksa ulang pada DOCX dan PDF |
| 4 | 12 Okt 2026 12:34 | Claude Code | Membuat versi Markdown laporan dan memperbarui README serta dokumen di folder `docs/` | Isi laporan dan repository | Hasil saya bandingkan dengan DOCX |
| 5 | 12 Okt 2026 12:45 | Codex / ChatGPT | Mengolah dokumen lokal, menyusun struktur portofolio lokal, dan membuat diagram alur (Diagram 1 dan 2) | Isi laporan dan pengamatan saya | Diagram saya cocokkan dengan proses yang diamati |
| 7 | 12 Okt 2026 17:55 | Codex / ChatGPT (ImageGen) | Membuat ilustrasi sampul dari dua screenshot yang telah dipotong | Dua screenshot terpotong | Ilustrasi bersifat dekoratif, bukan bukti antarmuka |
| 8 | 12 Okt 2026 22:18 | Claude Code | Final review struktur dokumen | DOCX, PDF, dan Markdown | Hasil saya periksa ulang pada DOCX dan PDF |

Catatan: baris baru ditambahkan setiap kali saya memakai AI untuk bagian lain.

## 4. Data yang terlihat oleh AI

Saya ingin terbuka tentang hal ini:
- Sistem yang dibedah adalah sistem internal tempat saya bekerja dan membutuhkan login. Saya melakukan login sendiri.
- Pengujian CRUD pada Dailylog dilakukan hanya pada entri dan tindakan yang secara spesifik saya izinkan. Keadaan akhir dicatat di laporan (Bagian 2.7).
- Saya tidak mencantumkan data pribadi dan data klien di teks laporan. Pada bukti yang dipublikasikan, identitas akun, klien/project, dan isi tugas yang tidak diperlukan dikeluarkan lewat pemotongan atau penyamaran.
- Password dan kredensial tidak ditulis di repository atau laporan.

## 5. Verifikasi hasil AI

Cara saya memverifikasi:
1. **Membandingkan dengan sumbernya:** keluaran AI saya cocokkan dengan tampilan antarmuka, screenshot, dan keadaan sistem (termasuk setelah muat ulang halaman).
2. **Menandai yang tidak terbukti:** klaim yang tidak punya bukti saya hapus atau saya tulis sebagai batas pengamatan.
3. **Membaca ulang hasil akhir:** DOCX, PDF, dan Markdown saya periksa lagi untuk kesesuaian isi, rujukan gambar, dan tautan.
4. **Memasukkan koreksi saya sendiri:** keterangan dari pengalaman kerja saya (mis. penyebab deadline kosong) saya tulis sebagai keterangan penulis, bukan temuan AI.

## 6. Pembagian peran: manusia dan AI

| Bagian pekerjaan | Pelaku |
|---|---|
| Memilih sistem dan menentukan cakupan | Saya |
| Mengamati sistem, menentukan uji, dan memberi izin tindakan | Saya |
| Menulis dan menyimpulkan analisis (People, Product, Process, Quality), gejala, problem statement, dan ide perbaikan | Saya (analisa manual) |
| Struktur Git dan daftar pekerjaan | Claude Code, saya tinjau |
| Review struktur dokumen dan pengecekan klaim | Claude Code, saya tindak lanjuti |
| Tabel, diagram, dan pengambilan screenshot | Codex / ChatGPT, saya periksa |
| Perapian format, daftar isi, tautan, dan versi Markdown | Claude Code, saya periksa |
| Gambar sampul | Codex / ChatGPT (dekoratif) |

## 7. Batasan dan hal yang tidak dilakukan

- Saya tidak menyerahkan penulisan analisis kepada AI. Jika AI membantu redaksi, itu dicatat di bagian 3.
- Saya tidak meminta AI mengarang bukti atau angka.
- Saya tidak mengunggah screenshot berisi data pribadi yang belum dipotong ke layanan AI publik secara sengaja.
- Saya tidak menyatakan bahwa tidak ada data internal yang pernah terlihat oleh AI; keadaan sebenarnya dijelaskan di bagian 4.
- Hasil AI yang tidak dapat saya verifikasi tidak dipakai.

## 8. Pernyataan

Saya memahami kebijakan penggunaan AI pada tugas ini. Informasi di dokumen ini saya tulis sebagai laporan penggunaan AI yang sebenarnya. Saya bertanggung jawab atas seluruh isi laporan dan repository, termasuk bagian yang dibantu AI.

Ivan Dika Pratama · 12 Oktober 2026
