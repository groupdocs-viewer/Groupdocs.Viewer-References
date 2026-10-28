---
title: "rotate_page‑metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Tillämpar en medurs rotation på en sida."
type: docs
url: /sv/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Tillämpar en medurs rotation på en sida.

För detaljer, se dokumentationen på https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidnumret måste vara strikt större än 0. |
| rotation | `Rotation` | Rotationsvärdet. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om rotation för sidan med nummer `page_number` redan har lagts till. |

### Se även
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
