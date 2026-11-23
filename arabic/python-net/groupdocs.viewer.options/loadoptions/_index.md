---
title: "فئة LoadOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخيارات المستخدمة لفتح ملف."
type: docs
url: /ar/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

الخيارات المستخدمة لفتح ملف.

يعرض نوع LoadOptions الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | يُهيء مثيلاً من الفئة [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | يُهيء مثيلاً جديداً من LoadOptions. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | الخاصية تمكّن اكتشاف الترميز للملفات [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)، [`FileType.csv`](/viewer/python-net/groupdocs.viewer.filetype/csv/)، و[`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | الترميز المستخدم عند فتح الملفات النصية أو رسائل البريد الإلكتروني مثل [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/)، [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)، و[`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). القيمة الافتراضية هي `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | نوع الملف المراد فتحه. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | كلمة المرور لفتح ملف مشفر. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | مهلة تحميل الموارد الخارجية. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | الخاصية تعطل تحميل جميع الموارد الخارجية مثل الصور، باستثناء تلك المدرجة في [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | الخاصية تمكّن GroupDocs.Viewer من محاولة إصلاح الفساد الهيكلي في مستندات PDF. القيمة الافتراضية هي False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | قائمة أجزاء URL المقابلة للموارد الخارجية التي يجب تحميلها عندما يتم ضبط [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) على `True`. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
