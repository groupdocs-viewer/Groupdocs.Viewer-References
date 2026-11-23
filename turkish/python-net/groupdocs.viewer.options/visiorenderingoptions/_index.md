---
title: "VisioRenderingOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Visio belgelerinin oluşturulması için seçenekleri temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Visio belgelerinin oluşturulması için seçenekleri temsil eder.

Ayrıntılar için belgelere bakın.

VisioRenderingOptions türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/) sınıfının bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | Şekil genişliği; yükseklik otomatik olarak hesaplanır. Varsayılan değer 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | Bu özellik yalnızca Visio şekillerini render eder, diyagramı değil. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Visio belgesini yükle
    with Viewer("map.vsdx") as viewer:
        # Visio dosyasını PDF'ye dönüştür.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Yalnızca ana şekilleri render et.
        view_options.visio_rendering_options.render_figures_only = True
        # Şekil genişliğini piksel olarak belirt.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
