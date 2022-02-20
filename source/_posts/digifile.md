---
title: DIGIFILE
categories:
  - [projects]
tags:
  - [reactjs]
  - [postgresql]
  - [go]
featured_image: /assets/img/posts/digifile.jpg
date: 2021-08-21 20:08:54
---

# Pendahuluan

Project ini adalah pengembangan sebuah perangkat lunak yang membantu dalam melakukan penyimpanan file / folder secara online dan aman. Digifile dibangun dengan menggunakan Progressive Web Application (PWA), DBMS PostgreSQL, dan API Golang. Digifile merupakan perangkat lunak yang menjadi tugas dalam kegiatan magang perusahaan di CV Digital Creative.

# Permasalahan

Dalam kegiatannya, CV. Digital Creative tidak lepas dari hal-hal yang berkaitan dengan pengelolaan dan penyimpanan data, dimana banyak sekali kegiatan yang harus diselesaikan berkenaan dengan file dan folder yang menampung data baik data internal perusahaan maupun data eksternal perusahaan. Penyimpanan data secara tradisional memiliki banyak kelemahan yaitu keamanan data yang tidak terjamin, media yang menggunakan ruang fisik, dan tidak efisiennya dalam proses menemukan data lama yang telah diarsipkan. Oleh karena itu, CV. Digital Creative membutuhkan perangkat lunak Storage System yang dapat digunakan untuk menyimpan, dan mengelola data perusahaan yang dapat mempermudah pekerjaan serta mengamankan data-data penting perusahaan yang disimpan secara aman pada server perusahaan.

# Pengguna

Pengguna dari DIGIFILE adalah Admin dari pihak CV Digital Creative yang akan melakukan manajemen pengguna, serta memantau log aktifitas pada system, dan para pegawai, serta client CV Digital Creative yang mampu menyimpan, dan mengelola data pada system.

# Roles dan Tanggung Jawab

## Mentor

Mentor merupakan Senior Software Developer dari CV Digital Creative yang mengarahkan kami dalam mengembangkan perangkat lunak ini. Mentor pada pengembangan Progressive Web Application ini yaitu sebagai berikut :
|**Nama**|**Mentor**|
|----|----|
|Achmad Ichsan | Database Engineer.|
|Dede Alfaruq | Frontend Developer.|
|Calvin Fadhil | API Developer & Crew Albatross.|

## Backend Developer

Dalam proses pengembangan Progressive Web Application ini terdapat dua programmer yang menghandle sisi backend yaitu saya Adi Kurniawan, dan Roni Starko. Saya memiliki tanggung jawab disisi database, dimana saya merancang Entity Relationship Diagram (ERD), membangun database sesuai rancangan, membuat stored function, stored procedure, view, dan trigger function, melakukan testing pada database, dan memastikan setiap relasi data berjalan dengan baik tanpa kendala. Rekan saya, Roni Starko memiliki tanggung jawab untuk API yang akan mengintegrasi program dari sisi antarmuka grafis dengan logic, dan data yang ada di database.

## Frontend Developer

Frontend developer dalam pengembangan ini memiliki tanggung jawab dalam membangun antarmuka grafis dari Progressive Web Application DIGIFILE ini berdasarkan UI/UX Design yang telah diberikan. Dimana posisi ini dipegang oleh Febyk Alek.

# Ruang Lingkup dan Batasan

Pengembangan basis data ini memiliki lingkup pada kegiatan penyimpanan, dan pengelolaan file, & folder dimana tedapat kegiatan sebagai berikut:

1. Manajemen file, dan folder,
2. Manajemen user, dan admin,
3. Pencatatan log aktifitas user,
4. Komputasi size file, dan folder yang telah disimpan user,
5. UI/UX berdasarkan desain yang telah diberikan CV Digital Creative.

# Proses

## Gathering Requirement

Proses pengumpulan kebutuhan ini diawali dengan briefing antara Chief Technology Officer (CTO) Digital Creative, dan intern Albatross Crew, dimana proses diskusi ini dilakukan secara tatap muka dikantor CV Digital Creative setiap minggunya. Berikut merupakan catatan pada diskusi di minggu pertama :

1. Aplikasi dibangun menggunakan React JS,
   PostgreSQL, dan Golang,
2. User dapat melakukan Create, Upload, Rename, Delete, Recovery, Search, Filter View pada
   File, dan Folder,
3. Admin mampu mengelola informasi user,
4. Admin mampu mengelola ukuran storage yang dapat dimiliki user,
5. Setiap kegiatan harus tercatat kedalam log activity, dan dapat dipantau oleh admin.

## Perancangan Database

Saya menggunakan aplikasi draw.io dalam melakukan pembuatan diagram relasi dari perancangan database ini. Dalam perancangan ini saya menentukan tabel tabel apa saja yang akan dibangun beserta dengan column, tipe data, panjang data, primary key, dan foreign key dari masing masing tabel. Kemudian dilakukan proses normalisasi tabel ketika ditemukan data yang redudansi, proses ini juga menjamin bahwa data akan berada pada tabel yang tepat (dependensi).

## Membangun Database

Pembangunan database pada Progressive Web Application ini menggunakan Relational Database Management System (RDBMS) dari PostgreSQL dengan menerapkan rancangan database yang telah dibuat sebelumnya.

## Pengujian Database

Tahapan ini dilakukan dengan menggunakan program Jetbrains Datagrip, tahapan ini memastikan setiap relasi bekerja dengan baik, Setiap tipe data tepat dan sesuai dengan kebutuhan, function, procedure, view, dan trigger berfungsi dengan baik sesuai dengan yang diharapkan. Tahapan ini juga dilaksanakan pada Progressive Web Application secara langsung untuk memastikan seluruh bagian dari database berfungsi secara baik, dan tanpa kendala.

# Hasil

Dengan beberapa umpan balik, bimbingan, dan revisi dari Mentor, dan Chief Executive Officer (CEO) CV Digital Creative, proses pengembangan Progressive Web Application ini akhirnya selesai, baik dari sisi backend maupun frontend. Dalam waktu kurang lebih 1 bulan pengembangan, DIGIFILE telah siap untuk digunakan.

Funfact: Pada final presentation, Albatross Crew mendapatkan penilaian yang sangat bagus, dan memuaskan dari CEO dan seluruh pegawai CV Digital Creative yang menghadiri final presentation.
