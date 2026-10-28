---
title: "fonts_to_exclude özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "HTML belgesinden dışlanacak yazı tipi adlarının listesi."
type: docs
url: /tr/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

HTML belgesinden dışlanacak yazı tipi adlarının listesi.

HTML belgesine eklenen yazı tipleri, çıktı görünümünün kararlılığını artırır, aynı zamanda render sonucunun boyutunu da büyütür. Bu seçenek, kararlılık ile çıktı boyutu arasında denge kurmanıza olanak tanır. Çoğu sistemde popüler olan ve yüklü olan yazı tipi adlarını dahil edin.

Lütfen unutmayın, bu özellik yalnızca [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) seçeneği devre dışı bırakıldığında aktiftir.

Ayrıntılar ve kod örneği için belgeleri inceleyin.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### Ayrıca Bakınız
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
