---
title: "remove_comments Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Eigenschaft deaktiviert das Rendern von Kommentaren, wenn sie auf True gesetzt ist."
type: docs
url: /de/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

Die Eigenschaft deaktiviert das Rendern von Kommentaren, wenn sie auf True gesetzt ist. Standardmäßig ist sie False, sodass alle Kommentare angezeigt werden.

Einige Dokumentformate wie PDF und WordProcessing können Kommentare enthalten. Standardmäßig rendert der GroupDocs.Viewer sie. Wenn diese Option auf True gesetzt ist, können die Kommentare aus dem resultierenden Dokument ausgeschlossen werden.

Diese Option ersetzt die veraltete `RenderComments` Eigenschaft.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Siehe auch
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
