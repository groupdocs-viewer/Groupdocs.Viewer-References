---
title: "ViewerSettings sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Viewer davranışını özelleştirmek için ayarları tanımlar."
type: docs
url: /tr/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

[`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) davranışını özelleştirmek için ayarları tanımlar.

ViewerSettings türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Yeni bir ViewerSettings örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Yeni bir ViewerSettings örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Yeni bir ViewerSettings örneği başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | Render sonuçlarını depolamak için kullanılan önbellek uygulaması. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | Günlükleme (Hatalar, Uyarılar, İzlemeler) için kullanılan logger uygulaması. |

### Örnek

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
