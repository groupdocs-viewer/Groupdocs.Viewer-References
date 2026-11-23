---
title: "Layer sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "CAD çiziminde bulunan bir katmanı temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

CAD çiziminde bulunan bir katmanı temsil eder.

Layer türü aşağıdaki üyeleri içerir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Yeni bir [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) sınıfı örneği oluşturur. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Yeni bir Layer örneği oluşturur. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Yeni bir Layer örneği oluşturur. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Mevcut Layer'ın belirtilen Layer nesnesiyle aynı olup olmadığını belirler. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Mevcut [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) nesnesinin belirtilen nesneye eşit olup olmadığını denetler. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Mevcut Layer nesnesi için hash kodunu döndürür. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Mevcut nesneyi temsil eden bir dize döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Katmanın adı. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | Katman görünürlük göstergesi. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
