---
title: "свойство enable_layered_rendering"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство включает рендеринг текста и графики в оригинальном порядке слоёв (z-order) PDF‑документа при рендеринге в HTML."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

Свойство включает рендеринг текста и графики в оригинальном порядке слоёв (z-order) PDF‑документа при рендеринге в HTML.

По умолчанию GroupDocs.Viewer рендерит текст и графику в HTML как один слой. Эта опция позволяет располагать объекты в том же порядке, что и в исходном файле. Значение по умолчанию — False.

Для примера кода см. документацию.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
