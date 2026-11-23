---
title: "فئة ViewerSettings"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحدد الإعدادات لتخصيص سلوك Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

يحدد الإعدادات لتخصيص سلوك [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

يعرض نوع ViewerSettings الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | يُنشئ نسخة جديدة من ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | يُنشئ نسخة جديدة من ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | يُنشئ نسخة جديدة من ViewerSettings. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | تنفيذ الذاكرة المؤقتة المستخدم لتخزين نتائج العرض. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | تنفيذ مسجل الأحداث المستخدم للتسجيل (الأخطاء، التحذيرات، المتتبعات). |

### مثال

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### انظر أيضًا
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
