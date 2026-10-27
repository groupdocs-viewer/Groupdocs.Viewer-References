---
title: "properti fixed_layout"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Opsi tata letak tetap mengaktifkan perenderan dokumen PDF dan EPUB ke HTML dengan tata letak tetap."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

Opsi tata letak tetap mengaktifkan perenderan dokumen PDF dan EPUB ke HTML dengan tata letak tetap.

Dokumen PDF dan EPUB awalnya dirender ke HTML dengan tata letak tetap untuk mempertahankan tampilan dokumen sumber. Tata letak tetap ini berarti semua elemen HTML memiliki posisi yang tepat dalam sebuah wadah dengan ukuran yang ditetapkan. Mengubah ukuran jendela browser tidak memengaruhi posisi dan ukuran elemen dalam dokumen.

Opsi ini hanya tersedia saat merender ke HTML. Nilai default adalah `True`. Untuk merender dengan tata letak cair, set properti ini ke `False`.

Saat merender dengan tata letak cair, gambar diabaikan. Gunakan tata letak cair saat merender dokumen PDF dengan konten teks.

Untuk contoh kode, lihat dokumentasi.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Lihat Juga
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
