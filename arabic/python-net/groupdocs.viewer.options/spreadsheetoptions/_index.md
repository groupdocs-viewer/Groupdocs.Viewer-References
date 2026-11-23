---
title: "فئة SpreadsheetOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "خيارات عرض جداول البيانات."
type: docs
url: /ar/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

خيارات عرض جداول البيانات.

للتفاصيل، راجع الفروع التابعة لموضوع Render spreadsheet files.

يعرض نوع SpreadsheetOptions الأعضاء التالية:

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | يُهيئ مثالًا من [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) لتصوير الورقة كاملة في صفحة واحدة. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | يُهيئ مثالًا من [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) مُكوَّنًا لتقسيم أوراق العمل إلى صفحات حسب فواصل الصفحات. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | يُهيئ مثالًا من الفئة [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) لتصوير مناطق الطباعة فقط. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | يُهيئ مثالًا من الفئة [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) لتصوير مناطق الطباعة وفواصل الصفحات. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | يُهيئ مثالًا من SpreadsheetOptions لتصوير ورقة إلى صفحات. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | يُهيئ مثالًا من SpreadsheetOptions لتصوير ورقة إلى صفحات. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | الهامش السفلي للصفحة عند التحويل إلى PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | عدد الأعمدة التي تُدرج في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | عدد الصفوف التي تُدرج في كل صفحة عند تقسيم ورقة العمل إلى صفحات. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | الخاصية تمكّن من اكتشاف الفاصل لملفات CSV/TSV. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | الدقة الأفقية للصور المُولدة بالنقطة في البوصة. يُستخدم هذا الخيار عند تصوير جداول البيانات إلى صيغ PNG أو JPEG فقط. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | الهامش الأيسر للصفحة عند التحويل إلى PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | الخاصية تمكّن من تصوير خطوط الشبكة. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | الخاصية تمكّن من تصوير العناوين. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | الخاصية تمكّن من تصوير الأعمدة المخفية. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | الخاصية تمكّن من عرض الصفوف المخفية. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | الهامش الأيمن للصفحة عند التحويل إلى PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | الخاصية تعطل عرض الأعمدة الفارغة. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | الخاصية تعطل عرض الصفوف الفارغة. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | وضع تجاوز النص عند عرض مستندات الجداول الإلكترونية إلى HTML. الوضع الافتراضي هو `TextOverflowMode.OverlayIfNextIsEmpty`، والذي يحاكي سلوك MS Excel الافتراضي. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | الهامش العلوي للصفحة عند التحويل إلى PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار فقط عند عرض الجداول إلى صيغ PNG أو JPEG. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # تمكين عرض خطوط الشبكة في الجدول.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
