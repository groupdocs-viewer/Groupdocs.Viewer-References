---
title: "Свойство is_embedded"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство указывает, встроен ли шрифт в документ и загружен в экземпляр Viewer (True), или является системным шрифтом (False)."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/
is_root: false
weight: 2040
---


## is_embedded property

Свойство указывает, встроен ли шрифт в документ и загружен в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), или это системный шрифт (`False`).

Табличные документы не могут содержать встроенные шрифты, поэтому это свойство всегда возвращает `False` для них.

### Definition:
```python
@property
def is_embedded(self):
    ...
```

### См. также
* class [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/)
