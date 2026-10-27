---
title: "فئة Viewer"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل الفئة الرئيسية التي تتحكم في عملية عرض المستند."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

يمثل الفئة الرئيسية التي تتحكم في عملية عرض المستند.

نوع Viewer يكشف عن الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | يُنشئ مثيلًا جديدًا من فئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | يُنشئ مثيلًا جديدًا من Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | يُنشئ مثيلًا جديدًا من الفئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | يُنشئ مثيلًا جديدًا من Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | يُنشئ مثيلًا جديدًا من Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | يُنشئ مثيلًا جديدًا من Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | يُنشئ مثيلًا جديدًا من Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | يُنشئ مثيلًا جديدًا من Viewer. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | يُنشئ مثيلًا جديدًا من فئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | يُنشئ مثيلًا جديدًا من الفئة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | يُنشئ مثيلًا جديدًا من [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | يُنشئ مثيلًا جديدًا من Viewer. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | يطلق تدفق الملف والموارد الداخلية المُدارة. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | يرجع جميع الخطوط المستخدمة في المستند المحمَّل، بما في ذلك الخطوط المدمجة وخطوط النظام المثبتة على نظام التشغيل. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | يرجع المرفقات الموجودة في المستند. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | يرجع معلومات حول الملف مثل نوع الملف وعلامة تشير إلى ما إذا كان الملف مشفرًا. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | يعيد العرض ومعلومات محددة للوثيقة. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | يحفظ ملف المرفق إلى تدفق `destination`. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | ينفّذ بحثًا نصيًا ويُبرز النص الموجود في المستند المحمّل وفقًا للخيارات المقدمة. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | ينشئ عرضًا لجميع صفحات المستند. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | ينشئ عرضًا لصفحات محددة من المستند. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | ينشئ عرضًا لصفحات محددة من المستند. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# تحويل DOCX إلى HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# تحويل PDF إلى PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
دليل المهام الذي يستخدم `Viewer`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### انظر أيضًا
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
