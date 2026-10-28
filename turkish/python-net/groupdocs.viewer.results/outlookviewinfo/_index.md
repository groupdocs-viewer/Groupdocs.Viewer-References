---
title: "OutlookViewInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Outlook Veri dosyası için görünüm bilgilerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Outlook Veri dosyası için görünüm bilgilerini temsil eder.

OutlookViewInfo türü aşağıdaki üyeleri gösterir:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Yeni bir [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Yeni bir OutlookViewInfo örneği başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Geçerli nesneyi temsil eden bir dize döndürür. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Outlook veri dosyasında bulunan klasörlerin listesi. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Dosyanın türü. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Görüntülenecek sayfaların listesi. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Örnek

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
`OutlookViewInfo` kullanan görev kılavuzları:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
