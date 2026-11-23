---
title: "for_rendering_by_width yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Genişliğe göre işlemek için CadOptions sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Genişliğe göre render etmek için [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) sınıfının bir örneğini başlatır.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | `int` | Çıktı sonucunun genişliği (piksel cinsinden). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `width` sıfırdan küçük veya eşit ise. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD dosyasını yükle
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Ayrıca Bakınız
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
