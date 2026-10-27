---
title: "to_hex 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "以十六进制字符串形式返回此颜色。"
type: docs
url: /zh/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

以十六进制字符串形式返回此颜色。

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### 示例

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### 另见
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
