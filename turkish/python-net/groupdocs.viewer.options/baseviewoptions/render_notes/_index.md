---
title: "render_notes özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik bazı formatlar için notların ve ek açıklamaların render edilmesini etkinleştirir."
type: docs
url: /tr/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

Bu özellik bazı formatlar için notların ve ek açıklamaların render edilmesini etkinleştirir.

Sunumlar veya Microsoft Project dosyaları gibi bazı formatlar notlar içerebilir. Ayrıca, PDF dosyalarında varsayılan olarak gizli olan ve yalnızca fare imlecini üzerine getirdiğinizde bir PDF görüntüleyicide görülen açılır ek açıklamalar (balon ipuçları) bulunabilir. Varsayılan olarak, GroupDocs.Viewer bu notları ve ek açıklamaları render etmez (`False`). Bunu yapmak için bu özelliği `True` olarak ayarlayın.

Bir kod örneği için belgelere bakın.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Ayrıca Bakınız
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
