# Komitmen Kerja

| | |
|---|---|
| **Nama** | Ivan Dika Pratama |
| **NIM** | 252011082 |
| **Kelas** | IT - Eksekutif |
| **Mata kuliah** | Rekayasa Perangkat Lunak (MKW TI_RPL.24) |
| **Dosen** | Fadhli Almuiini Ahda, S.Kom., M.Kom. |
| **Tugas** | Softskill 1 (Individu) — Bedah Sistem Informasi & Repository Profesional Pertamaku |
| **Tanggal** | 12 Oktober 2026 |

## Daftar isi

1. [Tujuan](#1-tujuan)
2. [Integritas dan kejujuran akademik](#2-integritas-dan-kejujuran-akademik)
3. [Etika review sistem](#3-etika-review-sistem)
4. [Perlindungan data dan privasi](#4-perlindungan-data-dan-privasi)
5. [Standar bukti dan dokumentasi](#5-standar-bukti-dan-dokumentasi)
6. [Praktik Git dan pengelolaan repository](#6-praktik-git-dan-pengelolaan-repository)
7. [Penggunaan AI](#7-penggunaan-ai)
8. [Pengelolaan waktu dan beban kerja](#8-pengelolaan-waktu-dan-beban-kerja)
9. [Lisensi dan hak atas materi](#9-lisensi-dan-hak-atas-materi)
10. [Koreksi, pelaporan masalah, dan tanggung jawab](#10-koreksi-pelaporan-masalah-dan-tanggung-jawab)

## 1. Tujuan

Dokumen ini menjelaskan cara saya bekerja pada tugas dan repository mata kuliah Rekayasa Perangkat Lunak. Isinya adalah komitmen yang saya pegang selama mengerjakan, mengamati sistem, menulis laporan, dan mengelola repository ini sebagai portofolio sepanjang semester. Komitmen ini mengacu pada lembar tugas dosen (Bagian 4 etika review dan Bagian 7 kebijakan AI).

## 2. Integritas dan kejujuran akademik

- Semua temuan, bukti, dan analisis berasal dari pengamatan saya sendiri terhadap sistem yang saya pakai.
- Saya tidak mengarang data, bukti, angka, atau kutipan. Jika sesuatu belum saya uji, saya menulis bahwa hal itu belum diuji.
- Pernyataan yang tidak terbukti tidak saya tulis sebagai fakta. Dugaan ditulis sebagai dugaan, dan keterangan dari pihak lain disebut sumbernya.
- Sumber yang saya pakai (lembar tugas, halaman sistem, keterangan rekan kerja) saya cantumkan di laporan.
- Saya tidak menyalin pekerjaan orang lain dan tidak membagikan pekerjaan saya untuk disalin. Sistem boleh sama dengan teman, tetapi temuan dan analisis tetap hasil saya sendiri.
- Penggunaan AI dilaporkan secara terbuka (lihat bagian 7).

## 3. Etika review sistem

Sistem yang saya bedah adalah Project Sekawan, sistem internal tempat saya bekerja. Saya mereview sebagai pengguna, bukan sebagai penyerang.

**Yang saya lakukan**
- Memakai hanya akun saya sendiri dan fitur yang memang tersedia untuk akun saya.
- Menjalankan uji hanya pada data atau tindakan yang secara spesifik saya izinkan, dan mencatat keadaan akhirnya agar data kerja tidak berubah tanpa catatan.
- Menulis kritik secara profesional dan berbasis bukti. Tujuannya memperbaiki, bukan menjatuhkan pengembang atau rekan kerja.

**Yang tidak saya lakukan**
- Menebak password atau melewati kontrol akses (mis. mencoba mengganti peran).
- Mengubah ID pada URL untuk melihat data orang lain.
- Memasukkan kode atau skrip ke form.
- Melakukan uji beban atau mengirim permintaan berulang secara massal.
- Mengakses, membuka rinci, atau mengubah data pengguna lain, termasuk penilaian personel.

**Jika menemukan celah keamanan**
1. Saya berhenti mengeksplorasi.
2. Saya tidak menyebarkannya, termasuk di repository ini.
3. Saya melaporkannya secara pribadi kepada dosen.

## 4. Perlindungan data dan privasi

Repository ini **public**, jadi saya memperlakukan seluruh isinya sebagai informasi yang dapat dibaca siapa pun.

- Identitas akun, nama klien/project, nama orang, dan isi tugas yang tidak diperlukan dikeluarkan dari bukti lewat pemotongan atau penyamaran.
- Data pribadi (NIM orang lain, nilai, foto, nomor telepon) tidak dicantumkan. NIM saya sendiri boleh tampil atas keputusan saya.
- Password, token, API key, cookie sesi, dan file kredensial tidak dimasukkan ke repository, laporan, atau pesan commit. `.gitignore` membantu, tetapi pemeriksaan manual tetap saya lakukan.
- Izin menampilkan NIM berlaku untuk data saya sendiri saja dan tidak berlaku untuk data privat lain.
- Antarmuka sistem yang membutuhkan login dibaca dalam sesi AI, sehingga sebagian data internal yang tampil di layar dapat terlihat oleh alat AI tersebut. Hal ini saya laporkan secara terbuka di [`PENGGUNAAN-AI.md`](PENGGUNAAN-AI.md) dan pada Bagian 7 laporan.
- Setelah mengunggah file, saya memeriksa kembali isi **sebelum** commit dan push. Riwayat Git bersifat permanen: data sensitif yang terlanjur ter-push diperlakukan sebagai insiden (dicabut dari riwayat, bukan sekadar dihapus dari berkas terakhir).

## 5. Standar bukti dan dokumentasi

- Setiap gambar bernomor, bertanggal, dan mencantumkan sumber halamannya.
- Setiap klaim analisis mengacu pada bukti (nomor gambar) atau menyebut bahwa bukti belum ada.
- Batas pengamatan dicatat: apa yang diuji, apa yang tidak diuji, dan apa yang tidak boleh disimpulkan dari bukti yang ada.
- Keadaan akhir pengujian dicatat setelah selesai.
- Laporan tersedia dalam tiga format yang isinya sama (DOCX, PDF, Markdown). Jika ada perbedaan, DOCX dan PDF yang dikumpulkan di LMS menjadi acuan.
- Nama file laporan mengikuti ketentuan dosen: `SS1_<NIM>_<Nama>.pdf`.

## 6. Praktik Git dan pengelolaan repository

**Struktur dan isi minimal**
- `README.md`, `LICENSE` (MIT), `docs/KOMITMEN-KERJA.md` (dokumen ini), `docs/PENGGUNAAN-AI.md`, laporan, dan folder `assets/`.

**Commit**
- Commit kecil dan bertahap dengan satu tujuan per commit.
- Pesan commit memakai format `jenis: ringkasan singkat dalam bentuk perintah`, dengan jenis `docs`, `chore`, atau `fix`. Contoh: `docs: add work commitment`.
- Sebelum commit saya menjalankan `git status` dan `git diff --staged` untuk memastikan tidak ada berkas sensitif atau tidak diperlukan yang ikut.

**Branch**
- `main` dijaga tetap rapi dan siap dinilai. Untuk pekerjaan yang lebih besar saya memakai branch kerja lalu menggabungkannya ke `main`.

**Berkas yang tidak masuk repository**
- Screenshot yang belum dipotong atau disamarkan, kredensial, dan berkas arsip atau sementara.

## 7. Penggunaan AI

Ringkasan komitmen:
- AI hanya alat bantu. Ia tidak menggantikan pengamatan dan analisis saya.
- AI tidak dipakai untuk mengarang temuan atau bukti, atau untuk menulis analisis tanpa saya benar-benar memakai sistemnya.
- Setiap penggunaan dicatat beserta alat, tujuan, dan cara verifikasinya.
- Keluaran AI saya baca, ubah seperlunya, dan cocokkan dengan pengamatan saya sebelum dipakai.

Rincian lengkap ada di [`PENGGUNAAN-AI.md`](PENGGUNAAN-AI.md).

## 8. Pengelolaan waktu dan beban kerja

- Sebagai mahasiswa kelas karyawan (IT - Eksekutif), saya membagi waktu antara pekerjaan dan perkuliahan. Pekerjaan direncanakan mundur dari tenggat, dengan waktu cadangan untuk pemeriksaan akhir dan pengumpulan.
- Urutan kerja: memilih sistem, mengamati dan mengambil bukti, menyamarkan data, menulis analisis, menyiapkan repository, menyusun laporan, memeriksa ulang, lalu mengumpulkan.
- Pemeriksaan akhir mencakup: nama file, link repository pada halaman pertama laporan dan kolom komentar LMS, akses dosen ke repository, serta data pribadi dan data klien pada bukti.
- Jika ada kendala yang mempengaruhi tenggat, saya menyampaikannya kepada dosen sedini mungkin.

## 9. Lisensi dan hak atas materi

- Repository berlisensi **MIT** (lihat [`LICENSE`](../LICENSE)), hak cipta atas nama Ivan Dika Pratama.
- Lisensi ini mencakup tulisan dan berkas buatan saya. Lisensi tidak mencakup merek, antarmuka, data milik perusahaan atau klien, maupun dokumen milik dosen.
- Dokumen tugas dari dosen tidak disalin ke repository.

## 10. Koreksi, pelaporan masalah, dan tanggung jawab

- Jika saya menemukan kesalahan pada laporan atau repository (fakta, data sensitif, atau klaim yang tidak sesuai), saya memperbaikinya segera dan mencatat perubahannya di riwayat commit.
- Jika ada pihak (mis. dosen atau perusahaan) yang meminta bahan tertentu ditarik, saya menurutinya dan menghapusnya dari repository.
- Saya bertanggung jawab penuh atas seluruh isi repository ini, termasuk bagian yang dibantu AI.

Ivan Dika Pratama · 12 Oktober 2026
