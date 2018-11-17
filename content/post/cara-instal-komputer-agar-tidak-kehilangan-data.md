---
title: "Cara Instal Komputer Agar Tidak Kehilangan Data"
date: 2018-10-25T11:47:05+07:00
archives: "2018"
tags: [Tutorial]
author: Nofe Green

image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---
## Cara Instal Komputer Agar Tidak Kehilangan Data
Menginstal komputer saat ini termasuk mudah, terlebih sudah ada beberapa software yang bisa digunakan untuk membuat booting dengan flashdisk, jadi kita tidak perlu lagi menggunakan cd/dvd. Bagi yang belum tau cara membuat Booting dengan Flashdisk saya sudah membuat tutorial terpisah disini [Cara Membuat Flashdisk Bootable Untuk Windows](https://nofegreen.github.io/2018/cara-membuat-flashdisk-bootable-untuk-windows/)

Sangat saya sarankan membaca sedetail mungkin supaya nanti ada pelajaran terpisah yang anda petik. Sebelum melakukan instalasi tentu kita harus berhati-hati terhadap data yang ada, apalagi tersimpan data penting pada sistem lama. Hati-hati disini yaitu lebih fokus pada saat melakukan partisi hardisk yang ada. 

Ok lanjut pada saat komputer mulai menyala atau saat tombol power ditekan cara gampang booting nya anda harus cepat-cepat menekan `tombol yang ada di tabel` untuk melakukan booting, dengan cara ini kita tidak perlu lagi repot untuk melakukan seting Bios. Tabel Boot Menu sudah saya sediakan dibawah ini, sesuaikan dengan hardware yang anda punya.

<b>Flashdisk yang sudah Bootable jangan lupa dicolokkan terlebih dahulu !!!</b>

## Motherboards

| Motherboards | Boot menu     | Bios setup   |
|--------------|:-------------:|-------------:|
| ASRock       | `F11`         | `F2, Del`    |
| Asus         | `F8, Esc`     | `Del, F2`    |
| Biostar      | `F9`          | `Del`        |
| ECS          | `F8`          | `Del`        |
| EPoX         | `Esc`         | `Del`        |
| GigaByte     | `F12`         | `Del`        |
| HP           | `F9, Esc, F7` | `F10`        |
| IBM          | `---`         | `F1`         |
| Intel        | `F10, Esc`    | `F2`         |
| MSI          | `F11`         | `Del`        |
|

## Notebooks

| Notebooks    | Boot menu     | Bios setup   |
|--------------|:-------------:|-------------:|
| Acer         | `F12`         | `F2`         |
| Aquarius     | `F11`         | `---`        |
| Asus         | `Esc`         | `F2`         |
| Dell         | `F12`         | `F2`         |
| DNS          | `F12`         | `---`        |
| HP           | `Esc, F9`     | `Esc, F10`   |
| IBM          | `F12`         | `F1`         |
| Lenovo       | `F12`         | `F2, F1`     |
| Packard Bell | `F12`         | `F2`         |
| Samsung      | `F10, Esc`    | `F2`         |
| Sony         | `F11`         | `F2`         |
|

Pilihan booting yang akan tampil tidak lebih seperti <b>gambar 1</b>, jika telat menekan tombol yang sesuai atau tidak tampil seperti gambar, anda harus mengulang lagi dari awal, yaitu shutdown komputer lagi lalu tekan tombol yang sesuai. "Sebagai contoh saya hanya menekan tombol Boot Menu `F9` karena Motherboard saya Biostar"

<h5>Gambar 1</h5>

![Boot](/img/img_artikel_install/boot_menu.png)

<b>Ket : gambar 1</b> Pilihlah USB dengan tombol panah atas bawah pada keyboard lalu tekan Enter.

<h5>Gambar 2</h5>

![Instal](/img/img_artikel_install/w1.png)

<b>Ket : gambar 2</b> Lanjut pilih `Next`

<h5>Gambar 3</h5>

![Instal](/img/img_artikel_install/w2.png)

<b>Ket : gambar 3</b> Klik `Instal now`

<h5>Gambar 4</h5>

![Instal](/img/img_artikel_install/w3.png)

<b>Ket : gambar 4</b> Silahkan pilih sesuai spek komputer anda, jika Motherboard (Papan Iduk Utama) anda support `Core i3` keatas dan memori lebih dari 4Gb saya rekomendasikan pilih yang 64 Bit (x64) tapi jika Motherboard `Dual Core` atau `Core 2 Duo` dan Memori 2Gb silahkan pilih yang 32 Bit (x86) saja. Ok sebagai contoh saya pilih yang 64 Bit (x64) lalu klik `Next`.

<h5>Gambar 5</h5>

![Instal](/img/img_artikel_install/w4.png)

<b>Ket : gambar 5</b> Lanjut ceklis `I accept the license terms` dan klik `Next`

<h5>Gambar 6</h5>

![Instal](/img/img_artikel_install/w5.png)

<b>Ket : gambar 6</b> Lalu pilihlah `Custom (advanced)` yang dilingkari garis hijau, mengapa kita memilih ini, karena dengan ini kita dapat mengulang membuat partisi atau melakukan format hardisk secara langsung. Untuk pilihan `Upgrade` kita abaikan, `Upgrade` merupakan pilihan untuk melakukan pembaharuan sistem secara timpa, jadi tidak dipastikan error atau virus hilang secara keseluruhan. Meskipun registry nya diperbaiki masih berkemungkinan di terinveksi virus yang masih ada disistem kumputer sebelumnya.

<h5>Gambar 7</h5>

![Instal](/img/img_artikel_install/w6.png)

<b>Ket : gambar 7</b> Penjelasan partition 1 adalah system yang berjalan pada hardisk sa'at ini jadi tidak perlu di delete atau format juga, dengan kata lain, biarkan sajalah :).

!!! Dan yang akan kita Instal adalah `C`. Ingat ! <strong>" C " atau " Disk0 partition 2 "</strong> yang dilingkari kotak warna hijau.

Disini nih yang perlu diperhatikan !!!, Jangan sekali-kali melakukan Delete, Format pada `Disk0 partition 3` yang dilingkari kotak warna merah atau turunan dibawahnya jika masih terdapat partition lagi. Ini adalah data lama pada hardisk yang tidak akan kita ganggu. Contoh disini adalah hardisk saya hanya terdapat 2 partition sebelumnya (C dan D saja). oia... Standar/Normal susunan partitonnya adalah `Disk0 partiton 2` itu `C` dan `Disk0 partiton 3` itu `D` kemudian `Disk0 partition 4` itu `E` dan seterusnya.

Setelah memilih yang dilingkari kotak warna hijau sebaiknya kita format dulu partitionnya. Ok pastikan anda benar2 melakukan klik awal pada `Disk0 partition 2` lalu pilih format dibawahnya, dan setelah selesai lanjut dengan klik ` Next`.

<h5>Gambar 8</h5>

![Instal](/img/img_artikel_install/w7.png)

<b>Ket : gambar 8</b> Ini biarkan saja sampai selesai, setelah `Installing updates` komputer akan merestart secara sendirinya dan baru melakukan `Completing installation`.

<h5>Gambar 9</h5>

![Instal](/img/img_artikel_install/w8.png)

<b>Ket : gambar 9</b> Masukkan nama untuk Profil komputer anda, terserah nama apa yang diminati. Lanjut `Next`.

<h5>Gambar 10</h5>

![Instal](/img/img_artikel_install/w9.png)

<b>Ket : gambar 10</b> Kasih password jika mau, kalau tidak abaikan saja lalu klik `Next`. Contoh : saya tidak memberi password karena sering lupa dan terpaksa melakukan instal ulang lagi dikemudian hari :D, bisa diakali sih kalau lupa password tapi gak mau pusing ya gak usah dikasih password saja.

<h5>Gambar 11</h5>

![Instal](/img/img_artikel_install/w10.png)

<b>Ket : gambar 11</b> Pada pilihan `Use recommended settings` dan `Install important updates only` kita abaikan saja karena akan menghabiskan kuota internet / `bandwidth` dikemudian hari, jadi pilih saja yang `ASK ME LATER` yang dilingkari kotak berwarna hijau biar kita bisa mengatur update maupun setingan aplikasi yang memakai bandwidth nantinya.

<h5>Gambar 12</h5>

![Instal](/img/img_artikel_install/w11.png)

<b>Ket : gambar 12</b> Scrol dan pilih `(UTC+07:00)Bangkok, Hanoi, Jakarta` yang ada ibukota tercinta ini yang ditandai panah hijau pada gambar, lalu kilk `Next`.

Untuk setting waktu biar sikron online yang baik, firewall dan Update Windows nya `akan` saya buat artikel terpisah `langkah-langkah setingan Windows 7 dan Windows 10 bagi pemula`

<h5>Gambar 13</h5>

![Instal](/img/img_artikel_install/w12.png)

<b>Ket : gambar 14</b> Tunggu beberapa saat...

<h5>Gambar 14</h5>

![INstal](/img/img_artikel_install/w13.png)

<b>Ket : gambar 14</b> Alhamdulillah selesai juga.

 jika ada penjelasan agak rumit atau kurang jelas silahkan tinggalkan komentar dibawah artikel ini, dan terima kasih sudah berkunjung. Dan jangan lupa bagikan pada teman, sahabat atau kerabat jika dirasa bermanfaat :)