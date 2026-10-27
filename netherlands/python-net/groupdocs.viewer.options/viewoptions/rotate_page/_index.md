---
title: "rotate_page methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Past de klokwijzerrotatie toe op een pagina."
type: docs
url: /nl/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Past de klokwijzerrotatie toe op een pagina.

Voor details, zie de documentatie op https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het paginanummer moet strikt groter zijn dan 0. |
| rotation | `Rotation` | De rotatiewaarde. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als de rotatie voor de pagina met nummer `page_number` al was toegevoegd. |

### Zie ook
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
