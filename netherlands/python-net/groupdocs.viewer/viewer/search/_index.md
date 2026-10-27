---
title: "zoekmethode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Voert een tekstzoekopdracht uit en markeert de gevonden tekst in het geladen document volgens de opgegeven opties."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Voert een tekstzoekopdracht uit en markeert de gevonden tekst in het geladen document volgens de opgegeven opties.

```python
def search(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Zoek- en markeeropties, inclusief de te zoeken tekstzin. Mag niet None zijn. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `options` None is. |

### Zie ook
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
