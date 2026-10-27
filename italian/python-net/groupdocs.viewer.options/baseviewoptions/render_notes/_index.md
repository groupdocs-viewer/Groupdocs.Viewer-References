---
title: "proprietà render_notes"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà abilita il rendering di note e annotazioni per alcuni formati."
type: docs
url: /it/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

La proprietà abilita il rendering di note e annotazioni per alcuni formati.

Alcuni formati, come presentazioni o file Microsoft Project, possono contenere note. Inoltre, i file PDF possono avere annotazioni popup (suggerimenti a fumetto) che sono nascoste per impostazione predefinita e sono visibili in un visualizzatore PDF solo quando si punta il cursore del mouse su di esse. Per impostazione predefinita, GroupDocs.Viewer non rende tali note e annotazioni (`False`). Per fare ciò, impostare questa proprietà su `True`.

Per un esempio di codice, vedere la documentazione.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Vedi anche
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
