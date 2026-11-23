---
title: "for_rendering_by_scale_factor yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Ölçek faktörüne göre render etmek için bir CadOptions örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Ölçek faktörüne göre render etmek için bir CadOptions örneği başlatır.

Kod örneği için, belgeleri inceleyin.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scale_factor | `float` | 1'den büyük değer çıktı sonucunu büyütür; 0 ile 1 arasındaki değer çıktı sonucunu azaltır. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `scale_factor` sıfırdan küçük veya eşit olduğunda ortaya çıkar. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### Ayrıca Bakınız
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
