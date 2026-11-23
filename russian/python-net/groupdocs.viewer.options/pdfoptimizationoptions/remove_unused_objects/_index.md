---
title: "свойство remove_unused_objects"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство удаляет неиспользуемые (осиротевшие) объекты из PDF‑файла."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

Свойство удаляет неиспользуемые (осиротевшие) объекты из PDF‑файла.

Эти объекты размещены в PDF‑документе, но не находятся в словарях ресурсов ни одной страницы и поэтому полностью не используются. Включение этого свойства (`True`) уменьшит размер выходного PDF‑документа. По умолчанию оно отключено (`False`).

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### См. также
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
