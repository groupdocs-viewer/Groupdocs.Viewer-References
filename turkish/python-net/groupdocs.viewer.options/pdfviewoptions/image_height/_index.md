---
title: "image_height özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Çıktı görüntüsünün piksel cinsinden yüksekliği."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

Çıktı görüntüsünün piksel cinsinden yüksekliği.

Bu özelliği, çıktı görüntüsünün yüksekliğini (piksel cinsinden) ayarlamak için kullanın. GroupDocs.Viewer, tek bir görüntüyü yalnızca HTML'ye render ederken bu özelliği uygular. Ayrıntılar için https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/ adresindeki belgelere bakın.

Bu özelliği ayarlarsanız, [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) özelliği yok sayılır.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
