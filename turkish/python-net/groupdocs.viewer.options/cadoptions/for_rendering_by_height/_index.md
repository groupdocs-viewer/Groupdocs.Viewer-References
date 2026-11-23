---
title: "for_rendering_by_height yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yüksekliğe göre render etmek için bir CadOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Yüksekliğe göre render etmek için bir CadOptions örneği başlatır.

Kod örneği için, belgeleri inceleyin.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| height | `int` | Çıktı sonucunun yüksekliği (piksel cinsinden). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `height` sıfırdan küçük veya eşit olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Ayrıca Bakınız
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
