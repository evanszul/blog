---
title: "Cara Mengatasi Error Console Firefox the Character Encoding of the Html Document..."
date: 2018-04-25T23:47:03+07:00
tags: ["html"]
categories: ["html"]
draft: false

image: http://evanszul.ga/image_negara_asean/jpg/Image-Malaysia.jpg
thumbnail: http://evanszul.ga/image_negara_asean/jpg/Image-Malaysia.jpg
---

Pernah mengalami error pada halaman html yang sudah diberi beberapa sintaks dan menemukan error seperti dibawah ini?
{{< highlight "linenos=table">}}
The character encoding of the HTML document was not declared. The document will render with garbled text in some browser configurations if the document contains characters from outside the US-ASCII range. The character encoding of the page must be declared in the document or in the transfer protocol.
{{< / highlight >}}

Cara memperbaiki ini gampang banget, kamu cukup memasang kode dibawah ini didalam head.
{{< highlight "linenos=table" >}}
<meta charset="utf-8"/>
{{< / highlight >}}

Setelah kode tersebut ditambahkan maka nantinya hilang deh errornya.
