---
title: "ProjectManagementViewInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "MS Project belgesi için görünüm bilgilerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

MS Project belgesi için görünüm bilgilerini temsil eder.

ProjectManagementViewInfo türü aşağıdaki üyeleri ortaya çıkar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Yeni bir [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/) örneği başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | ProjectManagementViewInfo sınıfının yeni bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Geçerli nesneyi temsil eden bir dize döndürür. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | Projenin tamamlanması gereken tarih ve saat. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | Projenin başlatıldığı tarih ve saat. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Dosyanın türü. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Görüntülenecek sayfaların listesi. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Örnek

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
`ProjectManagementViewInfo` kullanan görev kılavuzları:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
