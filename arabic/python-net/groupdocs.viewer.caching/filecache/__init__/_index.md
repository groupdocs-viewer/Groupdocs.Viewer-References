---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُنشئ مثيلاً جديدًا من FileCache."
type: docs
url: /ar/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

يُنشئ مثيلاً جديدًا من FileCache.

```python
def __init__(self, cache_path):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| cache_path | `str` | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `cache_path` هو None. |

## __init__ {#cache_path-cache_sub_folder}

يُنشئ مثيلاً جديدًا من الفئة FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| cache_path | `str` | المسار النسبي أو المطلق حيث سيتم تخزين ذاكرة التخزين المؤقت للمستند. |
| cache_sub_folder | `str` | المجلد الفرعي لإضافته إلى `cache_path`. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `cache_sub_folder` هو None. |

### انظر أيضًا
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
