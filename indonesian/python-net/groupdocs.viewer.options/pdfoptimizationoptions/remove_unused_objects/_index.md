---
title: "remove_unused_objects properti"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini menghapus objek yang tidak terpakai (tertinggal) dari file PDF."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

Properti ini menghapus objek yang tidak terpakai (tertinggal) dari file PDF.

Objek-objek ini ditempatkan dalam dokumen PDF tetapi tidak dirujuk dari kamus sumber daya pada halaman mana pun sehingga tidak digunakan sama sekali. Mengaktifkan properti ini (`True`) akan mengurangi ukuran dokumen PDF yang dihasilkan. Secara default properti ini dinonaktifkan (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Lihat Juga
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
