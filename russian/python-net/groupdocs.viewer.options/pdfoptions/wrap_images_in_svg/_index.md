---
title: "свойство wrap_images_in_svg"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство, которое включает обёртывание каждого изображения в выходном HTML‑документе в тег SVG для повышения качества вывода."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

Свойство, которое включает обёртывание каждого изображения в выходном HTML‑документе в тег SVG для повышения качества вывода.

По умолчанию при рендеринге PDF и файлов Page Layout в HTML все изображения объединяются в одно PNG‑изображение. Сгенерированное PNG‑изображение используется как фон выходного HTML‑документа.

Эта опция доступна при рендеринге файлов форматов PDF и Page Layout в HTML с встроенными и внешними ресурсами. Она позволяет оборачивать каждое изображение в выходном HTML‑документе в тег SVG. Значение по умолчанию — False.

Для примера кода см. документацию.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
