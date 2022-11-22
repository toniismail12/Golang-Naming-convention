# Golang-Naming-convention-Aturan-penamaan-
Golang Naming convention (Aturan penamaan)

A. Golang Path

golang-learning/array : berisi kodingan yang berhubungan dengan array
golang- learning /conditional : berisi kodingan yang berhubungan dengan conditional missal if-else conditional
Aturan penamaan struktur folder:
- Nama path/folder berupa huruf kecil tanpa under score

B. Package

Struktur aplikasi golang adalah berupa package, dimana di dalam package biasanya ada banyak fungsi. Nama package ini sangat penting karena nama package akan menjadi acuan untuk memanggil fungsi yang berada dalam package.

Aturan penamaan package :
- Nama package harus berupa huruf kecil tanpa under score
- Name package diusahakan pendek dan mengandung kata benda missal http, token
- Nama package bisa berisi singkatan yang merepresentasikan kata benda missal package fmt yang artinya formatted I/O
- Nama package biasanya sama dengan nama folder dimana package itu berada
- Jika dalam satu folder ada banyak file golang maka tiap tiap file memiliki nama package yang sama
- Jangan membuat nama package yang terlalu umum missal package util, common dll. Detailkan nama package menjadi lebih spesifik.

C. Nama file

Nama file aplikasi golang sebenarnya tidak begitu berarti, dalam artian nama file golang tidak menjadi acuan untuk memanggil fungsi-fungsi yang ada dalam file tersebut. Sebenarnya golang tidak ada aturan khusu dalam penamaan file, tetapi untuk memudahkan dalam pembacaan nama file berikut aturan umum penamaan nama file.
Aturan penamaan nama file :
- Nama file golang diusahakan berupa kecil semua
- Jika nama file lebih dari satu suku kata sebaiknya dipisahkan oleh dash(-) missal persegi-panjang.go, service-transfer.go dan lain lain
- Nama file yang memilki tujuan tertentu dikasih under-score(_) contoh persegi_test.go (khusus untuk test / unit test), main_win64.go (file main khusu untuk windoes 64)

D. Nama fungsi

Fungsi adalah sentral / jantung dari golang. Semua proses logic dilakukan dalam fungsi.
Aturan penamaan fungsi pada golang :
- Fungsi tidak boleh dimulai dengan angka
- Nama fungsi harus diawali dengan huruf alfabet, setalah diawali dengan huruf alfabet berikutnya dapat diikuti dengan angka atau huruf. Contoh nama fungsi adalah Sum12.
- Nama fungsi tidak boleh ada spasi
- Jika fungsi di awali dengan huruf besar berarti fungsi tersebut dapat diexport ke luar package. Jika package berawalan huruf kecil berarti tidak bisa dieksport ke luar package tetapi dapat di panggil oleh fungsi lain dalam satu package.
- Jika nama fungsi terdiri dari banyak suku kata maka tiap kata setelah kata pertama sebaiknya berupa huruf capital contoh hitungLuas, hitungVolume.
- Nama fungsi adalah case sensitive (beda antara huruf kecil dan huruf besar) contoh hitungluas vs hitungLuas vs HitungLuas.

source dari artikel:

https://www.golangprograms.com/naming-conventions-for-golang-functions.html
https://golang.org/doc/effective_go.html#names
https://blog.golang.org/package-names
https://www.quora.com/What-is-the-best-naming-convention-of-keeping-source-files-in-a-programming-language
https://wahyu-ehs.medium.com/golang-naming-convention-aturan-penamaan-fbd62f6d3ec2

