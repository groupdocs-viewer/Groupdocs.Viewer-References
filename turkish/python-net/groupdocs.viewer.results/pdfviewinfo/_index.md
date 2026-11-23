---
title: "PdfViewInfo sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PDF belgesi için görünüm bilgilerini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

PDF belgesi için görünüm bilgilerini temsil eder.

PdfViewInfo türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | PdfViewInfo sınıfının yeni bir örneğini başlatır. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | PdfViewInfo sınıfının yeni bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Geçerli nesneyi temsil eden bir dize döndürür. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | printing_allowed özelliği, belgenin yazdırılmasının izinli olup olmadığını gösterir. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Dosyanın türü. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Görüntülenecek sayfaların listesi. ([`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/) üzerinden miras alınmıştır) |

### Örnek

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
`PdfViewInfo` kullanan görev kılavuzları:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Ayrıca Bakınız
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
