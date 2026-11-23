---
title: "remove_unused_objects özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik, PDF dosyasından kullanılmayan (sahipsiz) nesneleri kaldırır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

Bu özellik, PDF dosyasından kullanılmayan (sahipsiz) nesneleri kaldırır.

Bu nesneler PDF belgesine yerleştirilir ancak herhangi bir sayfanın kaynak sözlüklerinden referans alınmaz ve bu yüzden hiç kullanılmaz. Bu özellik (`True`) etkinleştirildiğinde çıktı PDF belgesinin boyutu azalır. Varsayılan olarak devre dışıdır (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
