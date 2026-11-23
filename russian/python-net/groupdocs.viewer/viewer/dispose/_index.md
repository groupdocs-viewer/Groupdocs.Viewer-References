---
title: "метод dispose"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Освобождает поток файла и управляемые внутренние ресурсы."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/dispose/
is_root: false
weight: 1010
---


## dispose

Освобождает поток файла и управляемые внутренние ресурсы.

```python
def dispose(self):
    ...
```

### Пример

```python
from groupdocs.viewer import Viewer

viewer = Viewer("./sample.docx")
# Выполнять операции с viewer
viewer.dispose()
```

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
