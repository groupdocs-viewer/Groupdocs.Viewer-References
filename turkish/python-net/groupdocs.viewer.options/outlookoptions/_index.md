---
title: "OutlookOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Outlook veri dosyalarını renderlemek için seçenekler içerir."
type: docs
url: /tr/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Outlook veri dosyalarını renderlemek için seçenekler içerir.

Ayrıntılar için GroupDocs belgelerine bakın.

OutlookOptions türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | Gönderen veya alıcıya göre mesajları filtrelemek için kullanılan e-posta adresi. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Render edilecek klasörün adı (ör. Inbox, Sent Item veya Deleted Items). |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Bir klasörden render edilebilecek maksimum mesaj veya öğe sayısı. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Mesajları filtrelemek için kullanılan anahtar kelimeler. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Klasör başına render edilen öğe sayısını sınırlayın.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
