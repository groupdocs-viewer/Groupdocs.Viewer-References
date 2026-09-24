---
title: try_parse method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Tries to parse specified raw string as a font style name."
type: docs
url: /python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Tries to parse specified raw string as a font style name.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| style | `str` | String that should be parsed as a font style. |
| parsed | `FontStyles` | Parsed font style on success or `FontStyles.Regular` on failure. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### See Also
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
