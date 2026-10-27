---
title: "فئة PdfViewInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل معلومات العرض لمستند PDF."
type: docs
url: /ar/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

يمثل معلومات العرض لمستند PDF.

يعرض نوع PdfViewInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | يُهيئ نسخة جديدة من PdfViewInfo. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | يُهيئ نسخة جديدة من PdfViewInfo. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | يرجع سلسلة تمثل الكائن الحالي. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | تشير خاصية printing_allowed إلى ما إذا كان طباعة المستند مسموحًا بها. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | نوع الملف. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | قائمة الصفحات للعرض. (موروث من [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### مثال

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
دلائل المهام التي تستخدم `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### انظر أيضًا
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
