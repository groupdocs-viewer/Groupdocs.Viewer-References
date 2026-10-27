---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ الخيارات لتصيير مستندات معالجة الكلمات."
type: docs
url: /ar/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ الخيارات لتصيير مستندات معالجة الكلمات.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # تمكين عرض التغييرات المتتبعة.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### انظر أيضًا
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
