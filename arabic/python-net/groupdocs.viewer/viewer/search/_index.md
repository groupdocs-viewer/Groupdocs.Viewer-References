---
title: "طريقة البحث"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "ينفّذ بحثًا نصيًا ويُبرز النص الموجود في المستند المحمّل وفقًا للخيارات المقدمة."
type: docs
url: /ar/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

ينفّذ بحثًا نصيًا ويُبرز النص الموجود في المستند المحمّل وفقًا للخيارات المقدمة.

```python
def search(self, options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | `SearchHighlightOptions` | خيارات البحث والتسليط، بما في ذلك عبارة النص للبحث. يجب ألا تكون None. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `options` هو None. |

### انظر أيضًا
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
