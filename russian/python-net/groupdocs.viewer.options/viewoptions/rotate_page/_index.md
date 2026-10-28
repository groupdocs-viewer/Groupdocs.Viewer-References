---
title: "rotate_page метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Применяет вращение по часовой стрелке к странице."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Применяет вращение по часовой стрелке к странице.

Для получения подробностей см. документацию по адресу https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы должен быть строго больше 0. |
| rotation | `Rotation` | Значение вращения. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если вращение для страницы с номером `page_number` уже было добавлено. |

### См. также
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
