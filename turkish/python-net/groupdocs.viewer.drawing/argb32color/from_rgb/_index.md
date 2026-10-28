---
title: "from_rgb yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Belirtilen Kırmızı, Yeşil, Mavi kanallardan bir Argb32Color değeri oluşturur ve Alfa kanalını tamamen opak olarak ayarlar."
type: docs
url: /tr/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Belirtilen Kırmızı, Yeşil, Mavi kanallardan bir Argb32Color değeri oluşturur ve Alfa kanalını tamamen opak olarak ayarlar.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| red | `int` | Kırmızı kanal değeri. |
| green | `int` | Yeşil kanal değeri. |
| blue | `int` | Mavi kanal değeri. |

**Returns:** Argb32Color: New Argb32Color value.

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Ayrıca Bakınız
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
