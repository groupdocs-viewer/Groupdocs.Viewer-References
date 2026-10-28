---
title: "page_size özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Çıktı sayfasının boyutu."
type: docs
url: /tr/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

Çıktı sayfasının boyutu.

Varsayılan değer `PageSize.Unspecified`'dır, bu da sayfa ayarlarında (Sayfa Ayarı) belirlenen bir sayfa boyutunun kullanıldığı anlamına gelir.

HTM ve HTML dosyaları işlenirken varsayılan sayfa boyutu Letter 792 x 612 puan olarak ayarlanır.

Sonuç olarak, içeriğin bir kısmı sayfa çerçevesine sığmayabilir.

İçeriği sığdırmak için örneğin `PageSize.A3` gibi daha büyük bir sayfa boyutu ayarlayın.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Ayrıca Bakınız
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
