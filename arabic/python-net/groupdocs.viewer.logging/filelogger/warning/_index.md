---
title: "طريقة warning"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يكتب رسالة تحذير إلى وحدة التحكم."
type: docs
url: /ar/python-net/groupdocs.viewer.logging/filelogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

يكتب رسالة تحذير إلى وحدة التحكم.

رسائل سجل التحذير توفر معلومات حول الأحداث غير المتوقعة والقابلة للاسترداد في تدفق التطبيق.

```python
def warning(self, message):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| message | `str` | رسالة التحذير. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم الرفع عندما تكون `message` None. |

### انظر أيضًا
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
