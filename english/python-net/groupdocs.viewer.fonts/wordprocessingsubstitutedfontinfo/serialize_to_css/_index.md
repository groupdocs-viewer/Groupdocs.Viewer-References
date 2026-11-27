---
title: serialize_to_css method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Serializes the font info as a @font-face at-rule and writes it to the specified text writer."
type: docs
url: /python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/
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
| output | `System.IO.TextWriter` | Device into which the serialized text data should be written. |

| Raises | Description |
| :- | :- |
| `ValueError` | Output device is None. |

### Aliases

These names call `serialize_to_css` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `serialize_to_css_text_writer` | `serialize_to_css_text_writer(output)` |

### See Also
* class [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/)
