---
title: "свойство try_repair"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Это свойство позволяет GroupDocs.Viewer попытаться исправить структурные повреждения в PDF‑документах."
type: docs
url: /ru/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

Свойство позволяет GroupDocs.Viewer попытаться восстановить структурные повреждения в PDF‑документах. По умолчанию — False.

Эта функция решает следующие проблемы в PDF‑документе:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### См. также
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
