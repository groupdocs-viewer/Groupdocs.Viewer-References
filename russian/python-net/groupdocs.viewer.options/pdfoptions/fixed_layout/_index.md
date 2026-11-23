---
title: "свойство fixed_layout"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опция фиксированного макета включает рендеринг PDF‑ и EPUB‑документов в HTML с фиксированным макетом."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

Опция фиксированного макета включает рендеринг PDF‑ и EPUB‑документов в HTML с фиксированным макетом.

Документы PDF и EPUB первоначально рендерятся в HTML с фиксированным макетом, чтобы сохранить внешний вид исходного документа. Этот фиксированный макет означает, что все HTML‑элементы имеют точные позиции внутри контейнера с заданным размером. Изменение размера окна браузера не влияет на положение и размер элементов в документе.

Эта опция доступна только при рендеринге в HTML. Значение по умолчанию — `True`. Чтобы выполнить рендеринг с плавающим макетом, установите это свойство в `False`.

При рендеринге с плавающим макетом изображения пропускаются. Используйте плавающий макет при рендеринге PDF‑документов с текстовым содержимым.

Для примера кода см. документацию.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### См. также
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
