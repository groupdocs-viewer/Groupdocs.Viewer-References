---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بإنشاء نسخة جديدة من Line."
type: docs
url: /ar/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

ينشئ مثيلاً جديدًا من الفئة [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| line | `str` | السطر. |
| x | `float` | الإحداثي X لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على السطر. |
| y | `float` | الإحداثي Y لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على السطر. |
| width | `float` | عرض المستطيل الذي يحتوي على السطر (بالبكسل). |
| height | `float` | ارتفاع المستطيل الذي يحتوي على السطر (بالبكسل). |
| words | `List[Word]` | الكلمات التي يحتويها السطر. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يُرفع عندما تكون `line` فارغة أو null، أو عندما تكون `words` null. |

### انظر أيضًا
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
