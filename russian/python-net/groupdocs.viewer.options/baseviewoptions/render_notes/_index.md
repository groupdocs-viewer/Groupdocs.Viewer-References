---
title: "свойство render_notes"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство включает отображение заметок и аннотаций для некоторых форматов."
type: docs
url: /ru/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

Свойство включает отображение заметок и аннотаций для некоторых форматов.

Некоторые форматы, такие как презентации или файлы Microsoft Project, могут содержать заметки. Кроме того, PDF‑файлы могут иметь всплывающие аннотации (подсказки‑баллоны), которые по умолчанию скрыты и видны в PDF‑просмотрщике только при наведении курсора мыши. По умолчанию GroupDocs.Viewer не отображает такие заметки и аннотации (`False`). Чтобы включить их, установите это свойство в `True`.

Для примера кода см. документацию.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### См. также
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
