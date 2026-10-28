---
title: "search‑metoden"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Utför en textsökning och markerar den hittade texten i det inlästa dokumentet enligt de angivna alternativen."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Utför en textsökning och markerar den hittade texten i det inlästa dokumentet enligt de angivna alternativen.

```python
def search(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Sök‑ och markeringsalternativ, inklusive textfrasen att söka efter. Får inte vara None. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `options` är None. |

### Se även
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
