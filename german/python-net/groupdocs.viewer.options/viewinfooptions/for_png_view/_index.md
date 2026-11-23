---
title: "for_png_view-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der ViewInfoOptions-Klasse, um Informationen zur Ansicht beim Rendern in PNG abzurufen."
type: docs
url: /de/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Initialisiert eine Instanz der [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) Klasse, um Informationen zur Ansicht beim Rendern in PNG abzurufen.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Erstellt ViewInfoOptions für das PNG-Format
view_info_options_png = ViewInfoOptions.for_png_view()

# Lädt ein Dokument und ruft die Ansichtsinformationen für PNG ab
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Initialisiert eine Instanz der ViewInfoOptions-Klasse, um Informationen zur Ansicht beim Rendern in PNG abzurufen.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extract_text | `bool` | Aktiviert die Textextraktion. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Beispiel

```python
from groupdocs.viewer.options import ViewInfoOptions

# Erstellt ViewInfoOptions für das PNG-Format mit aktivierter Textextraktion
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Siehe auch
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
