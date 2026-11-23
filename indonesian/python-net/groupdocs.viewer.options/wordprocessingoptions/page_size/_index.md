---
title: "properti page_size"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Ukuran halaman output."
type: docs
url: /id/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

Ukuran halaman output.

Nilai default adalah `PageSize.Unspecified`, yang berarti ukuran halaman yang ditetapkan dalam pengaturan halaman (Page Setup) akan digunakan.

Saat merender file HTM dan HTML, ukuran halaman default diatur ke Letter 792 x 612 poin.

Akibatnya, sebagian konten mungkin tidak muat dalam bingkai halaman.

Atur ukuran halaman yang lebih besar, misalnya `PageSize.A3`, untuk menyesuaikan konten.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Lihat Juga
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
