---
title: "properti wrap_images_in_svg"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti yang mengaktifkan pembungkus setiap gambar dalam dokumen HTML keluaran dengan tag SVG untuk meningkatkan kualitas keluaran."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

Properti yang mengaktifkan pembungkus setiap gambar dalam dokumen HTML keluaran dengan tag SVG untuk meningkatkan kualitas keluaran.

Secara default, saat merender file PDF dan Page Layout ke HTML, semua gambar dirender sebagai satu gambar PNG. Gambar PNG yang dirender digunakan sebagai latar belakang untuk dokumen HTML output.

Opsi ini tersedia saat merender format file PDF dan Page Layout ke HTML dengan sumber daya tersemat dan eksternal. Ini memungkinkan membungkus setiap gambar dalam dokumen HTML output dengan tag SVG. Nilai default adalah False.

Untuk contoh kode, lihat dokumentasi.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Lihat Juga
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
