---
title: "свойство render_original_page_size"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Размер выходной страницы устанавливается в соответствии с размером страницы исходного PDF‑документа."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

Размер выходной страницы устанавливается в соответствии с размером страницы исходного PDF‑документа.

По умолчанию GroupDocs.Viewer вычисляет размер страницы выходного изображения для повышения качества рендеринга. Включите эту опцию, чтобы обеспечить одинаковый размер выходных страниц с размером страниц исходного PDF‑документа (в пикселях). Значение по умолчанию — False.

Эта опция доступна при рендеринге в форматы PNG или JPG.

Для примера кода см. документацию.

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
