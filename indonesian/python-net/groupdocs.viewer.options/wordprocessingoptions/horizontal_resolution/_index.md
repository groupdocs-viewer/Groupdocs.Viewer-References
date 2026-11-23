---
title: "properti horizontal_resolution"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Resolusi horizontal untuk gambar yang dihasilkan dalam titik per inci."
type: docs
url: /id/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

Resolusi horizontal untuk gambar yang dihasilkan dalam dot per inci. Opsi ini hanya digunakan saat merender dokumen WordProcessing ke format PNG atau JPEG.

Nilai default adalah 96 DPI. Nilai minimum yang mungkin adalah 72 DPI; nilai maksimum yang mungkin adalah 600 DPI. Jika nilai yang ditentukan pengguna berada di luar batas ini, batas terdekat (minimum atau maksimum) akan diterapkan.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Lihat Juga
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
