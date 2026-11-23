---
title: "get_view_info-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert weergave- en documentspecifieke informatie."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Retourneert weergave- en documentspecifieke informatie.

Meer informatie over document - bestandstype, paginatelling en andere formatspecifieke eigenschappen:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `ViewInfoOptions` | De view‑info‑opties. |

**Returns:** Information about view and document specific information.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `options` None is. |
| `PasswordRequiredException` | Wanneer een wachtwoord vereist is om het document te openen. |
| `IncorrectPasswordException` | Wanneer het opgegeven wachtwoord onjuist is. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Zie ook
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
