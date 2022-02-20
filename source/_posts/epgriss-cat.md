---
title: EPGRISS CAT | Computer Assisted Test
categories:
  - [projects]
tags:
  - [codeigniter]
  - [mysql]
featured_image: /assets/img/posts/epgriss-cat.jpeg
date: 2021-08-15 20:00:00
---

# Pendahuluan

Project ini adalah pengembangan sebuah website ujian berbasis komputer atau dikenal dengan Computer Assisted Test (CAT) dari Persatuan Guru Republik Indonesia (PGRI) Sumatera Selatan yang merupakan client dari CV. Digital Creative.

# Permasalahan

Banyaknya peserta, proses administrasi pendaftaran peserta yang tidak efektif, dan sulitnya menyimpan, serta menemukan data dari masing masing peserta dalam jangka panjang menjadi permasalahan yang dihadapi oleh PGRI SUMSEL dalam proses seleksi, ujian, dan tryout terhadap tenaga pendidik di Sumatera Selatan. Sehingga mereka membutuhkan suatu sistem yang mampu mengatasi permasalahan tersebut, baik sebelum ujian, saat ujian, hingga pasca ujian untuk meningkatkan kinerja dari kegiatan tersebut.

# Pengguna

Pengguna dari website ini adalah Admin dari pihak PGRI SLCC yang akan melakukan manajemen data dari kegiatan, dan para peserta dari kegiatan yang diselenggarakan oleh PGRI SLCC, baik simulasi ujian, tryout, ujian seleksi, dan lain sebagainya.

# Roles dan Tanggung Jawab

1. Project Manager
   Project manager melakukan perencanaan projek, menjaga komunikasi antar anggota tim, melakukan kalkulasi anggaran, monitoring perkembangan projek, dan melakukan meeting, serta report kepada pihak client. Projek manager pada pengembangan website ini yaitu Kak Malian Zikri.
2. Backend Developer
   Dalam proses pengembangan website ini terdapat dua programmer yang menghandle sisi backend yaitu saya Adi Kurniawan, dan Roni Starko. Saya memiliki tanggung jawab disisi database, dimana saya merancang Entity Relationship Diagram (ERD), membangun database sesuai rancangan, membuat stored function, stored procedure, view, dan trigger function, melakukan testing pada database, dan memastikan setiap relasi data berjalan dengan baik tanpa kendala. Rekan saya, Roni Starko memiliki tanggung jawab untuk mengintegrasi program dari sisi antarmuka grafis dengan logic, dan data yang ada di database.
3. Frontend Developer
   Frontend developer dalam pengembangan ini memiliki tanggung jawab dalam membangun antarmuka grafis dari website EPGRISS CAT. Dimana posisi ini dipegang oleh Febyk Alek.

# Ruang Lingkup dan Batasan

Pengembangan basis data ini memiliki lingkup pada kegiatan ujian pada umumnya dimana tedapat kegiatan sebagai berikut:

1. Manajemen peserta,
2. Manajemen bank soal, kategori, jawaban dan bobot nilai,
3. Manajemen sesi ujian,
4. Komputasi, dan pemeringkatan nilai peserta.

# Proses

## Gathering Requirement

Proses pengumpulan kebutuhan ini diawali dengan meeting oleh projek manajer dengan pihak client, dan kemudian dilanjutkan dengan berdiskusi antara projek manager, frontend developer, dan backend developer, dimana proses diskusi ini dilakukan secara daring dikarenakan setiap individu programmer berada pada lokasi atau regional yang berbeda, dan dalam keadaan yang tidak memungkinkan untuk tatap muka secara fisik dikarenakan keadaan pandemi Covid-19 yang sedang dialami oleh seluruh dunia pada saat ini. Berikut merupakan catatan pada diskusi ini:

1. Client menginginkan jumlah jawaban yang benar dari pertanyaan dapat lebih dari 1 opsi,
2. Setiap opsi jawaban memiliki bobot nilai tersendiri,
3. Setiap kategori memiliki bobot nilai tersendiri,
4. Peserta dapat login dengan menggunakan No hp, atau Username,
5. Sistem dapat menerima data dalam bentuk excel/spreadsheet,
6. Sistem pengacakan soal,
7. Dapat mengatur jumlah soal, dan kategori dari setiap sesi ujian.

## Perancangan Database

Saya menggunakan aplikasi draw.io dalam melakukan pembuatan diagram relasi dari perancangan database ini. Dalam perancangan ini saya menentukan tabel tabel apa saja yang akan dibangun beserta dengan column, tipe data, panjang data, primary key, dan foreign key dari masing masing tabel. Kemudian dilakukan proses normalisasi tabel ketika ditemukan data yang redudansi, proses ini juga menjamin bahwa data akan berada pada tabel yang tepat (dependensi).

## Membangun Database

Pembangunan database pada website ini menggunakan Relational Database Management System (RDBMS) dari MariaDB dengan menerapkan rancangan database yang telah dibuat sebelumnya.

## Pengujian Database

Tahapan ini dilakukan dengan menggunakan program Jetbrains Datagrip, tahapan ini memastikan setiap relasi bekerja dengan baik, Setiap tipe data tepat dan sesuai dengan kebutuhan, function, procedure, view, dan trigger berfungsi dengan baik sesuai dengan yang diharapkan. Tahapan ini juga dilaksanakan pada website secara langsung untuk memastikan seluruh bagian dari database berfungsi secara baik, dan tanpa kendala.

# Hasil

Dengan beberapa umpan balik dan revisi dari client, dan projek manager, proses pengembangan website ini akhirnya selesai, baik dari sisi backend maupun frontend. Dalam waktu kurang lebih 10 hari pengembangan, web EPGRISS CAT siap beraksi, dan digunakan.

Funfact: Pada minggu pertama deployment, website ini mampu menghandle hingga 8 Sesi Ujian dengan masing masing sesi menampung peserta kurang lebih 100 peserta ujian.
