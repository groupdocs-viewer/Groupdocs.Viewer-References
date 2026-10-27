---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بإنشاء نسخة جديدة من Word."
type: docs
url: /ar/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

ينشئ مثيلاً جديدًا من [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

ينشئ مثيلاً جديدًا من [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| word | `str` | الكلمة. |
| x | `float` | الإحداثي X لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على الكلمة. |
| y | `float` | الإحداثي Y لأعلى نقطة يسرى في تخطيط الصفحة حيث يبدأ المستطيل الذي يحتوي على الكلمة. |
| width | `float` | عرض المستطيل الذي يحتوي على الكلمة. |
| height | `float` | ارتفاع المستطيل الذي يحتوي على الكلمة. |
| characters | `List[Character]` | الأحرف التي يحتويها الكلمة. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `characters` null. |

### انظر أيضًا
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
