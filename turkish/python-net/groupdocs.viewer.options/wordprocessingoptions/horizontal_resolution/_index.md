---
title: "horizontal_resolution özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlük."
type: docs
url: /tr/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlük. Bu seçenek yalnızca WordProcessing belgelerini PNG veya JPEG formatlarına render ederken kullanılır.

Varsayılan değer 96 DPI'dir. Minimum olası değer 72 DPI; maksimum olası değer 600 DPI'dir. Kullanıcı tarafından belirtilen değer bu sınırların dışındaysa, en yakın sınır (minimum veya maksimum) uygulanır.

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### Ayrıca Bakınız
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
