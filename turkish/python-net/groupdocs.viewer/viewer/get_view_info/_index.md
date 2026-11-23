---
title: "get_view_info yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Görünüm ve belgeye özgü bilgileri döndürür."
type: docs
url: /tr/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Görünüm ve belgeye özgü bilgileri döndürür.

Belge hakkında daha fazla bilgi edinin - dosya türü, sayfa sayısı ve diğer format özel özellikleri:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | `ViewInfoOptions` | Görünüm bilgi seçenekleri. |

**Returns:** Information about view and document specific information.

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | `options` None olduğunda. |
| `PasswordRequiredException` | Belgeyi açmak için bir şifre gerektiğinde. |
| `IncorrectPasswordException` | Belirtilen şifre yanlış olduğunda. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Ayrıca Bakınız
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
