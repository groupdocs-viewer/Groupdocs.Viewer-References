---
title: serialize_to_css method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Serializes the font info as a @font-face at-rule and writes it to the specified text writer."
type: docs
url: /python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/
is_root: false
weight: 1010
---


## serialize_to_css {#output}

Serializes the font info as a @font-face at-rule and writes it to the specified text writer.

```python
def serialize_to_css(self, output):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| output | `System.IO.TextWriter` | A file-like object (e.g., an `io.TextIOBase`) into which the serialized text data should be written. |

**Returns:** None.

| Raises | Description |
| :- | :- |
| `ValueError` | If `output` is `None`. |

### See Also
* class [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/)
