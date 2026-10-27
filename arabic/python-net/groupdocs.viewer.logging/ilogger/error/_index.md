---
title: "طريقة error"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يكتب رسالة خطأ."
type: docs
url: /ar/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

يكتب رسالة خطأ.

رسائل سجل الأخطاء توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.

```python
def error(self, message, exception):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| message | `str` | رسالة الخطأ. |
| exception | `Exception` | الاستثناء. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عند `exception` هو None. |

### انظر أيضًا
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
