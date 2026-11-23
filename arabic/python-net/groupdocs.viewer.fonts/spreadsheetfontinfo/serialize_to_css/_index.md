---
title: "طريقة serialize_to_css"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتسلسل معلومات الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/
is_root: false
weight: 1010
---


## serialize_to_css {#output}

يقوم بتسلسل معلومات الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد.

```python
def serialize_to_css(self, output):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| output | `System.IO.TextWriter` | كائن شبيه بالملف (مثال: `io.TextIOBase`) يُكتب فيه بيانات النص المتسلسلة. |

**Returns:** None.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `output` هو `None`. |

### انظر أيضًا
* class [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/)
