---
title: "proprietà remove_comments"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà disabilita il rendering dei commenti quando impostata su True."
type: docs
url: /it/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

La proprietà disabilita il rendering dei commenti quando impostata su True. Per impostazione predefinita è False, quindi tutti i commenti sono visualizzati.

Alcuni formati di documento come PDF e WordProcessing possono contenere commenti. Per impostazione predefinita GroupDocs.Viewer li renderizza. Con questa opzione impostata su True i commenti possono essere esclusi dal documento risultante.

Questa opzione sostituisce la proprietà obsoleta `RenderComments`.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Vedi anche
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
