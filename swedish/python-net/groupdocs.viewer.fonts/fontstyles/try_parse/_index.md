---
title: "try_parse metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Försöker tolka den angivna råa strängen som ett typsnittsstilsnamn."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Försöker tolka den angivna råa strängen som ett typsnittsstilsnamn.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| style | `str` | Sträng som ska tolkas som en teckensnittsstil. |
| parsed | `FontStyles` | Tolkat teckensnittsstil vid framgång eller `FontStyles.Regular` vid misslyckande. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Se även
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
