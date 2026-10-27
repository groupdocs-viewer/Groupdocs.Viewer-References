---
title: "try_parse 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "尝试将指定的原始字符串解析为字体样式名称。"
type: docs
url: /zh/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

尝试将指定的原始字符串解析为字体样式名称。

```python
def try_parse(cls, style, parsed):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| style | `str` | 应解析为字体样式的字符串。 |
| parsed | `FontStyles` | 成功时返回解析后的字体样式，失败时返回 `FontStyles.Regular`。 |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### 另见
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
