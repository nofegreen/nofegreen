---
title: "Java Syntax"
date: 2018-12-11T10:36:26+07:00
archives: "2018"
tags: [Java]
author: Nofe Green

image: https://lorempixel.com/720/380
thumbnail: https://lorempixel.com/320/160
---

# Java Syntax

Contoh file java dasar `MyClass.java` yang akan menampilkan kata "Hello World" adalah

> MyClass.java
```js
public class MyClass {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

## Penjelasan kode diatas
Perlu di ingat semua baris kode dalam java selalu berjalan dalam `class` disini saya memberi nama class dengan MyClass, huruf pertama class harus dimulai dengan huruf besar/kapital. Java sensitif terhadap huruf besar dan kecil.

Nama file java harus sama dengan nama class disaat anda menyimpannya atau dalam melakukan `save` dan jangan lupa `extension` dibelakangnya harus .java 

Contoh : MyClass.java

![Java](/img/img_artikel_java/java.png)

## The main Method / Metode
Method `main()` akan selalu kita lihat dalam pemrograman java

>public static void **main**(String[] args)

Setiap barisan kode dalam method **main** akan dieksekusi atau dijalankan, untuk saat ini anda tidak perlu dulu mengenal lebih jauh, karena pada lanjutan tutorial-tutorial seterusnya akan membuat anda mengerti dengan sendirinya.

## System.out.println()
Didalam method `main()` kita dapat menggunakan method `println()` untuk menampilkan baris text ke layar dengan mudah.

```js
public static void main(String[] args) {
  System.out.println("Hello World");
}

// output teksnya Hello World
```
> **Catatan:** Setiap pernyataan dalam java harus diakhiri dengan semicolon atau titik koma " ; "