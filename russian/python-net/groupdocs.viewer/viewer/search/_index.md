---
title: "метод поиска"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Выполняет поиск текста и выделяет найденный текст в загруженном документе в соответствии с указанными параметрами."
type: docs
url: /ru/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Выполняет поиск текста и выделяет найденный текст в загруженном документе в соответствии с указанными параметрами.

```python
def search(self, options):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Параметры поиска и подсветки, включая фразу текста для поиска. Не должно быть None. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `options` равно None. |

### См. также
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
