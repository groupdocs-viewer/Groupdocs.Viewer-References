---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化新的 FileCache 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

初始化新的 FileCache 实例。

```python
def __init__(self, cache_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cache_path | `str` | 文档缓存将被存储的相对或绝对路径。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `cache_path` 为 None。 |

## __init__ {#cache_path-cache_sub_folder}

初始化 FileCache 类的新实例。

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cache_path | `str` | 文档缓存将被存储的相对或绝对路径。 |
| cache_sub_folder | `str` | 要追加到 `cache_path` 的子文件夹。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `cache_sub_folder` 为 None。 |

### 另见
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
