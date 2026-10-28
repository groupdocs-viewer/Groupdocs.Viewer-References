---
title: "Метод to_hex"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает этот цвет в шестнадцатеричном строковом представлении."
type: docs
url: /ru/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

Возвращает этот цвет в шестнадцатеричном строковом представлении.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### Пример

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### См. также
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
