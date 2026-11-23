---
title: "свойство disable_copy_protection"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство отключает защиту от копирования контента при рендеринге в HTML."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

Свойство отключает защиту от копирования контента при рендеринге в HTML.

При рендеринге PDF‑файлов с защитой от копирования текста и изображений в HTML, GroupDocs.Viewer добавляет атрибут `inert` к тегу BODY HTML. Значение по умолчанию — `False`, что означает, что атрибут `inert` добавляется только если PDF‑документ защищён.

Для примера кода см. документацию.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
