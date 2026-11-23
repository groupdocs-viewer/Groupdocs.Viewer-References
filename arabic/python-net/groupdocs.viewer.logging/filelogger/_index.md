---
title: "فئة FileLogger"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يكتب رسائل السجل إلى الملف."
type: docs
url: /ar/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

يكتب رسائل السجل إلى الملف.

يعرض نوع FileLogger الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | يُهيئ مسجلاً يكتب الرسائل إلى ملف. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | يكتب رسالة خطأ إلى وحدة التحكم. رسائل سجل الأخطاء توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | يكتب رسالة تتبع إلى السجل. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | يكتب رسالة تحذير إلى وحدة التحكم. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

### مثال

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
