---
title: "ViewInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Genel bir belge için görünüm bilgilerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

Genel bir belge için görünüm bilgilerini temsil eder.

ViewInfo türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | Yeni bir [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | Yeni bir ViewInfo örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Mevcut nesneyi temsil eden bir dize döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Dosyanın türü. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Görüntülenecek sayfaların listesi. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
