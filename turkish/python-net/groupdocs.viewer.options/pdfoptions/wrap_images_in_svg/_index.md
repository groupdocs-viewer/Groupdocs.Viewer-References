---
title: "wrap_images_in_svg özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik, çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü bir SVG etiketi içinde sarmalamayı etkinleştirir."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

Bu özellik, çıktı kalitesini artırmak için çıktı HTML belgesindeki her görüntüyü bir SVG etiketi içinde sarmalamayı etkinleştirir.

Varsayılan olarak, PDF ve Sayfa Düzeni dosyaları HTML'ye render edildiğinde, tüm görseller tek bir PNG görüntüsü olarak render edilir. Oluşturulan PNG görüntüsü, çıktı HTML belgesinin arka planı olarak kullanılır.

Bu seçenek, gömülü ve harici kaynaklarla PDF ve Sayfa Düzeni dosya formatları HTML'ye render edildiğinde kullanılabilir. Çıktı HTML belgesindeki her görseli bir SVG etiketi içinde sarmayı sağlar. Varsayılan değer False'tur.

Bir kod örneği için belgelere bakın.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
