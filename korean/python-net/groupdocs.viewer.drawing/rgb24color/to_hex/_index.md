---
title: "to_hex 메서드"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "이 색상을 16진수 문자열 형태로 반환합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/
is_root: false
weight: 1110
---


## to_hex

이 색상을 16진수 문자열 형태로 반환합니다.

```python
def to_hex(self):
    ...
```

**Returns:** str: Color hex representation string.

### 예시

```python
    from GroupDocs.Viewer.Drawing import Rgb24Color

    hex_str = Rgb24Color.KnownColors.CssLevel1.Red.to_hex()
    print(hex_str)  # "#FF0000"
    ```

### 참고
* class [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)
