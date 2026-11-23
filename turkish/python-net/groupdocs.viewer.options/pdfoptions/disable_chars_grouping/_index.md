---
title: "disable_chars_grouping özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik, sayfa işleme sırasında hassas sembol konumlandırması için sembol gruplandırmayı devre dışı bırakır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/
is_root: false
weight: 2010
---


## disable_chars_grouping property

Bu özellik, sayfa işleme sırasında hassas sembol konumlandırması için sembol gruplandırmayı devre dışı bırakır.

PDF dosyalarını dönüştürürken, GroupDocs.Viewer daha iyi işleme performansı için tek tek karakterleri kelimelere gruplar. Belgeniz hiyeroglifler veya özel semboller içeriyorsa, daha kesin bir düzen sağlamak için karakter gruplamayı engellemek isteyebilirsiniz. Varsayılan değer False'tur.

Kod örneği için, belgeleri inceleyin.

### Definition:
```python
@property
def disable_chars_grouping(self):
    ...
@disable_chars_grouping.setter
def disable_chars_grouping(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
