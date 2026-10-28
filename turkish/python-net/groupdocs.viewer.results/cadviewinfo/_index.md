---
title: "CadViewInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "CAD çizimi için görünüm bilgilerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

CAD çizimi için görünüm bilgilerini temsil eder.

CadViewInfo türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | CadViewInfo sınıfının yeni bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Geçerli nesneyi temsil eden bir dize döndürür. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | CAD çiziminde bulunan katmanların listesi. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | CAD çiziminde bulunan yerleşimlerin listesi. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Dosyanın türü. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Görüntülenecek sayfaların listesi. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Örnek

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
`CadViewInfo` kullanan görev kılavuzları:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
