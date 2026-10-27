---
title: "to_hex メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "この色を 16 進文字列表現で返します。"
type: docs
url: /ja/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

この色を 16 進文字列表現で返します。

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### 例

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### 参照
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
