---
title: "for_html_view-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine ViewInfoOptions-Instanz zum Abrufen von Ansichtsinformationen beim Rendern zu HTML."
type: docs
url: /de/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Initialisiert eine ViewInfoOptions-Instanz zum Abrufen von Ansichtsinformationen beim Rendern zu HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Beispiel

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Erstellt ViewInfoOptions für das HTML-Format (Einzelseite)
    options = ViewInfoOptions.for_html_view(True)

    # Lädt ein Dokument und ruft die Ansichtsinformationen ab
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Initialisiert eine ViewInfoOptions-Instanz zum Abrufen von Ansichtsinformationen beim Rendern zu HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| render_single_page | `bool` | Aktiviert das Rendern von HTML-Inhalten auf einer einzelnen Seite. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Ruft ViewInfo-Informationen für HTML mit einer einzelnen Seite ab
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Siehe auch
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
