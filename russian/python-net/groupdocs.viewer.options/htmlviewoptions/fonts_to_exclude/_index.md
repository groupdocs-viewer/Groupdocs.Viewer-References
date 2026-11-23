---
title: "свойство fonts_to_exclude"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Список названий шрифтов, исключаемых из HTML‑документа."
type: docs
url: /ru/python-net/groupdocs.viewer.options/htmlviewoptions/fonts_to_exclude/
is_root: false
weight: 2020
---


## fonts_to_exclude property

Список названий шрифтов, исключаемых из HTML‑документа.

Шрифты, добавленные в HTML‑документ, повышают стабильность отображения вывода, но одновременно увеличивают размер результата рендеринга. Эта опция позволяет сбалансировать стабильность и размер вывода. Включайте названия шрифтов, которые популярны и установлены в большинстве систем.

Обратите внимание, это свойство активно только когда опция [`HtmlViewOptions.ExcludeFonts`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/exclude_fonts/) отключена.

Подробности и пример кода см. в документации.

### Definition:
```python
@property
def fonts_to_exclude(self):
    ...
@fonts_to_exclude.setter
def fonts_to_exclude(self, value):
    ...
```

### См. также
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
