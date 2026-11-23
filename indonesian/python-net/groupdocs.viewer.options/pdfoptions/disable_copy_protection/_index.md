---
title: "properti disable_copy_protection"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini menonaktifkan perlindungan penyalinan konten saat merender ke HTML."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

Properti ini menonaktifkan perlindungan penyalinan konten saat merender ke HTML.

Saat merender file PDF dengan perlindungan terhadap penyalinan teks dan gambar ke HTML, GroupDocs.Viewer menambahkan atribut HTML `inert` ke tag BODY HTML. Nilai default adalah `False`, yang berarti atribut `inert` hanya ditambahkan jika dokumen PDF dilindungi.

Untuk contoh kode, lihat dokumentasi.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Lihat Juga
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
