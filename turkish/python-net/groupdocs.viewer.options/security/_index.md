---
title: "Security sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "PDF belge güvenlik seçenekleri."
type: docs
url: /tr/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

PDF belge güvenlik seçenekleri.

Ayrıntılar için belgelere bakın.

Security türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | [`Security`](/viewer/python-net/groupdocs.viewer.options/security/) sınıfının bir örneğini başlatır. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | PDF belgesini açmak için gereken parola. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | PDF belgesi izinleri, örneğin yazdırma, değiştirme ve veri çıkarma. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | İzin ayarlarını değiştirmek için gereken şifre. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
`Security` kullanan görev kılavuzları:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
