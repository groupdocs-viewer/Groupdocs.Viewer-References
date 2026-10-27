---
title: "get_view_info‑Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt Informationen zur Ansicht und zum Dokument zurück."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Gibt Informationen zur Ansicht und zum Dokument zurück.

Erfahren Sie mehr über Dokument – Dateityp, Seitenanzahl und andere formatspezifische Eigenschaften:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `ViewInfoOptions` | Die Ansicht-Info-Optionen. |

**Returns:** Information about view and document specific information.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `options` None ist. |
| `PasswordRequiredException` | Wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| `IncorrectPasswordException` | Wenn das angegebene Passwort falsch ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Siehe auch
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
