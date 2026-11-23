---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует параметры для рендеринга документов обработки текста."
type: docs
url: /ru/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует параметры для рендеринга документов обработки текста.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Включить рендеринг отслеживаемых изменений.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### См. также
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
