---
title: "proprietà is_embedded"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà indica se il carattere è incorporato nel documento e caricato nell'istanza Viewer (True), oppure è un carattere di sistema (False)."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/
is_root: false
weight: 2040
---


## is_embedded property

La proprietà indica se il font è incorporato nel documento e caricato nell'istanza [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), oppure è un font di sistema (`False`).

I documenti di foglio di calcolo non possono contenere caratteri incorporati, quindi questa proprietà restituisce sempre `False` per essi.

### Definition:
```python
@property
def is_embedded(self):
    ...
```

### Vedi anche
* class [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/)
