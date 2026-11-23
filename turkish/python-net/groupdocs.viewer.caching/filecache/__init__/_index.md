---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Yeni bir FileCache örneği başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Yeni bir FileCache örneği başlatır.

```python
def __init__(self, cache_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cache_path | `str` | Belge önbelleğinin saklanacağı göreceli ya da mutlak yol. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `cache_path` None ise. |

## __init__ {#cache_path-cache_sub_folder}

FileCache sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cache_path | `str` | Belge önbelleğinin saklanacağı göreceli ya da mutlak yol. |
| cache_sub_folder | `str` | `cache_path`'e eklenecek alt klasör. |

| Yükseltir | Açıklama |
| :- | :- |
| `ValueError` | Eğer `cache_sub_folder` None ise. |

### Ayrıca Bakınız
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
