---
title: "طريقة for_rendering_by_page_breaks"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة كائن SpreadsheetOptions مُكوَّن لتقسيم أوراق العمل إلى صفحات باستخدام فواصل الصفحات."
type: docs
url: /ar/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

يُهيئ مثالًا من [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) مُكوَّنًا لتقسيم أوراق العمل إلى صفحات حسب فواصل الصفحات.

للتفاصيل، راجع الوثائق.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # تحميل جدول البيانات
    with Viewer("products.xlsx") as viewer:
        # تحويل جدول البيانات إلى PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # تقسيم باستخدام فواصل الصفحات.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### انظر أيضًا
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
