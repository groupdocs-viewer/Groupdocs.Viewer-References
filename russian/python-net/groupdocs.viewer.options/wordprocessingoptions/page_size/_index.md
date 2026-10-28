---
title: "свойство page_size"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Размер выходной страницы."
type: docs
url: /ru/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

Размер выходной страницы.

Значение по умолчанию — `PageSize.Unspecified`, что означает использование размера страницы, установленного в настройках страницы (Page Setup).

При рендеринге файлов HTM и HTML размер страницы по умолчанию устанавливается как Letter 792 x 612 пунктов.

В результате часть содержимого может не помещаться в рамку страницы.

Установите больший размер страницы, например `PageSize.A3`, чтобы разместить содержимое.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### См. также
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
