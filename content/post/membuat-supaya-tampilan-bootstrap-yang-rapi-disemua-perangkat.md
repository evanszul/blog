---
title: "Membuat Supaya Tampilan Bootstrap Yang Rapi Disemua Perangkat"
date: 2018-04-25T23:20:50+07:00
tags: ["html","bootstrap"]
categories: ["web"]
draft: false

image: /img/membuat-supaya-tampilan-bootstrap-yang-rapi-disemua-perangkat/html.png
thumbnail: /img/membuat-supaya-tampilan-bootstrap-yang-rapi-disemua-perangkat/html.png
---

Jika teman-teman selesai membuat halaman html pada komputer menggunakan bootsrap, setelah di coba di smartphone tampilannya menjadi berantakan di pc. Teman-teman dapat menggunakan kode dibawah ini untuk merapikannya. Letakkan kode dibawah ini didalam <head> pada halaman html.
{{< highlight html "linenos=table" >}}
<meta name="viewport" content="width=device-width,initial-scale=1">
{{< / highlight >}}</br>
Nah, jika sudah memasukkan kode diatas kedalam <head> maka tampilan html yang kamu buat menjadi tidak berantakan.
