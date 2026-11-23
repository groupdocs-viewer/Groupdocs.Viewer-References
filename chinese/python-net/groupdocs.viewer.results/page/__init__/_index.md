---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Page 的新实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

初始化一个新的 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 实例。

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

初始化一个新的 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 实例。

```python
def __init__(self, number, visible):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| number | `int` | 页码。 |
| visible | `bool` | 页面可见性指示器。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `number` 小于或等于零时。 |

## __init__ {#number-name-visible}

初始化一个新的 Page 实例。

```python
def __init__(self, number, name, visible):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| number | `int` | 页码。 |
| name | `str` | 工作表或页面名称。 |
| visible | `bool` | 页面可见性指示器。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `number` 小于或等于零时。 |

## __init__ {#number-visible-width-height}

初始化一个新的 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 实例。

```python
def __init__(self, number, visible, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| number | `int` | 页码。 |
| visible | `bool` | 页面可见性指示器。 |
| width | `int` | 以 JPG 或 PNG 查看时页面的宽度（像素）。 |
| height | `int` | 以 JPG 或 PNG 查看时，页面的像素高度。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `height` 小于或等于零时。 |

## __init__ {#number-name-visible-width-height}

初始化一个新的 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 实例。

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| number | `int` | 页码。 |
| name | `str` | 工作表或页面名称。 |
| visible | `bool` | 页面可见性指示器。 |
| width | `int` | 以 JPG 或 PNG 查看时页面的宽度（像素）。 |
| height | `int` | 以 JPG 或 PNG 查看时，页面的像素高度。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `height` 小于或等于零时。 |

## __init__ {#number-visible-width-height-lines}

初始化一个新的 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 实例。

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| number | `int` | 页码。 |
| visible | `bool` | 页面可见性指示器。 |
| width | `int` | 以 JPG 或 PNG 查看时页面的宽度（像素）。 |
| height | `int` | 以 JPG 或 PNG 查看时，页面的像素高度。 |
| lines | `List[Line]` | 以启用文本提取的 JPG 或 PNG 查看时，页面包含的行。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 如果 `lines` 为 None。 |

## __init__ {#number-name-visible-width-height-lines}

初始化一个新的 [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) 实例。

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| number | `int` | 页码。 |
| name | `str` | 工作表或页面名称。 |
| visible | `bool` | 页面可见性指示器。 |
| width | `int` | 以 JPG 或 PNG 查看时页面的宽度（像素）。 |
| height | `int` | 以 JPG 或 PNG 查看时，页面的像素高度。 |
| lines | `List[Line]` | 以启用文本提取的 JPG 或 PNG 查看时，页面包含的行。 |

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `lines` 为 None 时。 |

### 另见
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
