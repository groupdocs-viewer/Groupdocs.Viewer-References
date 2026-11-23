---
title: "rotate_page Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Wendet die Drehung im Uhrzeigersinn auf eine Seite an."
type: docs
url: /de/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Wendet die Drehung im Uhrzeigersinn auf eine Seite an.

Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Seitennummer muss strikt größer als 0 sein. |
| rotation | `Rotation` | Der Rotationswert. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn die Rotation für die Seite mit der Nummer `page_number` bereits hinzugefügt wurde. |

### Siehe auch
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
