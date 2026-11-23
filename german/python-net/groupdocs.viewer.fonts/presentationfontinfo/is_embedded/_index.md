---
title: "is_embedded Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft gibt an, ob die Schriftart im Dokument eingebettet und in die Viewer-Instanz geladen ist (True) oder ob es eine Systemschriftart ist (False)."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/
is_root: false
weight: 2040
---


## is_embedded property

Die Eigenschaft gibt an, ob die Schrift im Dokument eingebettet und in die [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) Instanz (`True`) geladen ist, oder ob es sich um eine Systemschrift handelt (`False`).

Tabellendokumente können keine eingebetteten Schriftarten enthalten, daher gibt diese Eigenschaft für sie immer `False` zurück.

### Definition:
```python
@property
def is_embedded(self):
    ...
```

### Siehe auch
* class [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/)
