---
title: "from_other_with_alpha 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "从指定实例创建一个新的 Argb32Color 实例，但使用重新定义的 alpha（不透明度）值。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

从指定的实例创建一个新的 [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 实例，但使用重新定义的 alpha（不透明度）值。

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | `Argb32Color` | 其他 `Argb32Color` 实例，将从中创建新的实例。 |
| new_alpha | `int` | 重新定义的 alpha 通道值 (255 - 完全不透明，0 - 完全透明)。 |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

从指定的 Rgb24Color 创建一个新的 Argb32Color 实例，但使用指定的 alpha（不透明度）值。

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | `Rgb24Color` | 其他 Rgb24Color 实例，将从中创建新的实例。 |
| new_alpha | `int` | Alpha 通道值 (255 - 完全不透明，0 - 完全透明)。 |

**Returns:** New Argb32Color instance.

### 另见
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
