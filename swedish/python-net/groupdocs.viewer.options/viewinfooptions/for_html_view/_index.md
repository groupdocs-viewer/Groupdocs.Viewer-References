---
title: "for_html_view metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ViewInfoOptions-instans för att hämta visningsinformation när man renderar till HTML."
type: docs
url: /sv/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Initierar en ViewInfoOptions-instans för att hämta visningsinformation när man renderar till HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Exempel

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Skapa view‑info‑alternativ för HTML‑format (enkel sida)
    options = ViewInfoOptions.for_html_view(True)

    # Läs in ett dokument och hämta vyinformation
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Initierar en ViewInfoOptions-instans för att hämta visningsinformation när man renderar till HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| render_single_page | `bool` | Aktiverar rendering av HTML‑innehåll till en enkel sida. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Hämta vyinfo för HTML med en enkel sida
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Se även
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
