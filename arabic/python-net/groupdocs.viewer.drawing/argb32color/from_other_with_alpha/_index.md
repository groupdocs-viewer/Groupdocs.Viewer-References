---
title: "طريقة from_other_with_alpha"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينشئ عينة جديدة من Argb32Color من العينة المحددة، ولكن بقيمة ألفا (الشفافية) معاد تعريفها."
type: docs
url: /ar/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

ينشئ كائنًا جديدًا من [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) من الكائن المحدد، ولكن مع قيمة ألفا (شفافية) معاد تعريفها.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | `Argb32Color` | العينة الأخرى `Argb32Color` التي سيتم إنشاء الجديدة منها. |
| new_alpha | `int` | قيمة قناة ألفا المعاد تعريفها (255 - معتم بالكامل، 0 - شفاف بالكامل). |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

ينشئ كائن Argb32Color جديدًا من Rgb24Color المحدد، ولكن مع قيمة ألفا (شفافية) محددة.

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | `Rgb24Color` | العينة الأخرى Rgb24Color، التي سيتم إنشاء الجديدة منها. |
| new_alpha | `int` | قيمة قناة ألفا (255 - غير شفاف تمامًا، 0 - شفاف تمامًا). |

**Returns:** New Argb32Color instance.

### انظر أيضًا
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
