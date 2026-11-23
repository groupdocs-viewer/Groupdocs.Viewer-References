---
title: "fixed_layout özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Sabit düzen seçeneği, PDF ve EPUB belgelerinin HTML'ye sabit bir düzenle render edilmesini sağlar."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

Sabit düzen seçeneği, PDF ve EPUB belgelerinin HTML'ye sabit bir düzenle render edilmesini sağlar.

PDF ve EPUB belgeleri, kaynak belgenin görünümünü korumak için başlangıçta sabit bir düzenle HTML'ye işlenir. Bu sabit düzen, tüm HTML öğelerinin belirli bir boyuta sahip bir kapsayıcı içinde kesin konumlara sahip olduğu anlamına gelir. Tarayıcı penceresini yeniden boyutlandırmak, belgedeki öğelerin konum ve boyutunu etkilemez.

Bu seçenek yalnızca HTML'ye işleme sırasında kullanılabilir. Varsayılan değer `True`'dır. Akışkan bir düzenle işlemek için bu özelliği `False` olarak ayarlayın.

Akışkan düzenle işleme yaparken görüntüler atlanır. Metin içeriğine sahip PDF belgelerini işlerken akışkan düzeni kullanın.

Bir kod örneği için belgelere bakın.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
