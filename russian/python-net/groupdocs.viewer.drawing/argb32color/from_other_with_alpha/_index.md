---
title: "from_other_with_alpha метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Создаёт новый экземпляр Argb32Color из указанного экземпляра, но с переопределённым значением альфа-канала (непрозрачности)."
type: docs
url: /ru/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

Создаёт новый экземпляр [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) из указанного экземпляра, но с переопределённым значением альфа (непрозрачности).

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | `Argb32Color` | Другой экземпляр `Argb32Color`, из которого будет создан новый. |
| new_alpha | `int` | Переопределённое значение альфа-канала (255 — полностью непрозрачный, 0 — полностью прозрачный). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

Создаёт новый экземпляр Argb32Color из указанного Rgb24Color, но с заданным значением альфа (непрозрачности).

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | `Rgb24Color` | Другой экземпляр Rgb24Color, из которого будет создан новый. |
| new_alpha | `int` | Значение альфа‑канала (255 - полностью непрозрачный, 0 - полностью прозрачный). |

**Returns:** New Argb32Color instance.

### См. также
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
