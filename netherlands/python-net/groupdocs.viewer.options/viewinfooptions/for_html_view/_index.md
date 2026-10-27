---
title: "for_html_view methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een ViewInfoOptions‑instantie om weergave‑informatie op te halen bij het renderen naar HTML."
type: docs
url: /nl/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Initialiseert een ViewInfoOptions‑instantie om weergave‑informatie op te halen bij het renderen naar HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Voorbeeld

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Maak view‑info‑opties aan voor HTML-indeling (enkele pagina)
    options = ViewInfoOptions.for_html_view(True)

    # Laad een document en haal weergave‑informatie op
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Initialiseert een ViewInfoOptions‑instantie om weergave‑informatie op te halen bij het renderen naar HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| render_single_page | `bool` | Schakelt HTML‑inhoudsweergave naar een enkele pagina in. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Haalt weergave-informatie op voor HTML met één pagina
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Zie ook
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
