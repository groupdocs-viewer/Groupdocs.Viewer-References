---
title: "properti disable_chars_grouping"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini menonaktifkan pengelompokan simbol untuk penempatan simbol yang tepat selama perenderan halaman."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

Properti ini menonaktifkan pengelompokan simbol untuk penempatan simbol yang tepat selama perenderan halaman.

Saat mengonversi file PDF, GroupDocs.Viewer mengelompokkan karakter individual menjadi kata-kata untuk meningkatkan kinerja rendering. Jika dokumen Anda mencakup hieroglif atau simbol khusus, Anda mungkin ingin melarang pengelompokan karakter untuk memastikan tata letak yang lebih tepat. Nilai default adalah False.

Untuk contoh kode, lihat dokumentasi.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### Lihat Juga
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
