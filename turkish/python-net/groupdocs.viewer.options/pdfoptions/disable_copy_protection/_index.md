---
title: "disable_copy_protection özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik, HTML'ye işleme sırasında içerik kopyalama korumasını devre dışı bırakır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

Bu özellik, HTML'ye işleme sırasında içerik kopyalama korumasını devre dışı bırakır.

Metin ve görsellerin kopyalanmasına karşı koruma içeren PDF dosyaları HTML'ye render edildiğinde, GroupDocs.Viewer HTML BODY etiketine bir `inert` HTML özniteliği ekler. Varsayılan değer `False`dır, bu da `inert` özniteliğinin yalnızca PDF belgesi korumalıysa ekleneceği anlamına gelir.

Bir kod örneği için belgelere bakın.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
