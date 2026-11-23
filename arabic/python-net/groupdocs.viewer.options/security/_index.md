---
title: "فئة Security"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "خيارات أمان مستند PDF."
type: docs
url: /ar/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

خيارات أمان مستند PDF.

للتفاصيل، راجع الوثائق.

يعرض نوع Security الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | يُهيء مثيلاً من الفئة [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | كلمة المرور المطلوبة لفتح مستند PDF. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | أذونات مستند PDF مثل الطباعة، والتعديل، واستخراج البيانات. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | كلمة المرور المطلوبة لتغيير إعدادات الأذونات. |

### مثال

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
دروس المهام التي تستخدم `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
