---
title: "from_other_with_alpha メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "指定されたインスタンスから新しい Argb32Color インスタンスを作成しますが、アルファ（不透明度）値は再定義されます。"
type: docs
url: /ja/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/
is_root: false
weight: 1060
---


## from_other_with_alpha {#other-new_alpha}

指定されたインスタンスから新しい [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) インスタンスを作成しますが、アルファ（不透明度）値は再定義されます。

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| other | `Argb32Color` | 新しいインスタンスが作成される元となる他の `Argb32Color` インスタンスです。 |
| new_alpha | `int` | 再定義されたアルファチャンネルの値 (255 - 完全に不透明、0 - 完全に透明)。 |

**Returns:** Argb32Color: New `Argb32Color` instance.

## from_other_with_alpha {#other-new_alpha}

指定された Rgb24Color から新しい Argb32Color インスタンスを作成しますが、アルファ（不透明度）値を指定します。

```python
def from_other_with_alpha(cls, other, new_alpha):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| other | `Rgb24Color` | 新しいインスタンスが作成される元となる他の Rgb24Color インスタンスです。 |
| new_alpha | `int` | アルファチャンネルの値 (255 - 完全に不透明、0 - 完全に透明)。 |

**Returns:** New Argb32Color instance.

### 参照
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
