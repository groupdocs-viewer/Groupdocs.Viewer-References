---
title: "get_view_info‑metoden"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar vy- och dokumentspecifik information."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Returnerar vy- och dokumentspecifik information.

Läs mer om dokumentet – filtyp, sidantal och andra format‑specifika egenskaper:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `ViewInfoOptions` | Visningsinformationsalternativen. |

**Returns:** Information about view and document specific information.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `options` är None. |
| `PasswordRequiredException` | När ett lösenord krävs för att öppna dokumentet. |
| `IncorrectPasswordException` | När det angivna lösenordet är felaktigt. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Se även
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
