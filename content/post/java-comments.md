---
title: "Java Comments"
date: 2018-12-12T11:51:54+07:00
archives: "2018"
tags: []
author: Nofe Green

image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

# Java Comments

Comments atau komentar dapat digunakan untuk menjelaskan kode pada Java, dan membuatnya lebih mudah dibaca dan diingat jika kita akan melakukan pengeditan dikemudian hari. Comments juga dapat digunakan untuk mencegah eksekusi kode atau mencegah kode untuk dijalankan.

Comments pada satu baris teks dimulai dengan dua garis miring didepannya (//). Teks apa pun antara // dan akhir baris akan diabaikan oleh Java atau tidak akan diproses.

Dibawah ini adalah contoh menggunakan komentar pada baris tunggal sebelum baris kode:

```js
// Ini adalah komentar
System.out.println("Hello World");
```

Dibawah ini adalah contoh menggunakan komentar baris tunggal di akhir baris kode:

```js
System.out.println("Hello World"); // Ini adalah komentar
```

## Java Multi-line Comments

Komentar Multi-line dimulai dengan / * dan diakhiri dengan * /.

Teks atau kode apa pun antara / * dan * / akan diabaikan oleh Java.

Dibawah ini adalah contoh menggunakan komentar Multi-line pada baris kode:

```js
/* Kode dibawah ini akan mencetak teks Hello World ke layar */
System.out.println("Hello World");
```
Contoh lain Komentar Multi-line pada kode adalah :

```js
public class MyClass {
  public static void main(String[] args) {
/*  System.out.println("Hello World"); */
    System.out.println("Hello Dunia");
/*  System.out.println("Hello Programmer"); */
    System.out.println("Hello Kitty");
  }
}


//  outputnya adalah :
    Hello Dunia
    Hello Kitty
```
Program yang hanya akan dijalankan dan diproses adalah Hello Dunia dan Hello Kitty.