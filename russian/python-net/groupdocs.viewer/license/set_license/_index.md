---
title: "метод set_license"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Применить лицензию к текущему процессу."
type: docs
url: /ru/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Применить лицензию к текущему процессу.

```python
def set_license(self, license_source):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| license_source |  | Либо строковый путь к файлу ``.lic``, либо читаемый объект, похожий на файл, который предоставляет байты лицензии. Такие объекты записываются во временный файл перед передачей в мост. |

| Исключения | Описание |
| :- | :- |
| `TypeError` | Если ``license_source`` не является ни строковым путем, ни читаемым объектом, похожим на файл. |

### См. также
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
