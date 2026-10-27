---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Word 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

初始化一个新的 [`Word`](/viewer/python-net/groupdocs.viewer.results/word/) 实例。

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| word | `str` | 该单词。 |
| x | `float` | 包含单词的矩形在页面布局中左上角的 X 坐标。 |
| y | `float` | 包含单词的矩形在页面布局中左上角的 Y 坐标。 |
| width | `float` | 包含单词的矩形的宽度。 |
| height | `float` | 包含单词的矩形的高度。 |
| characters | `List[Character]` | 单词包含的字符。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `characters` 为 null 时。 |

### 另见
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
