---
title: "for_png_view methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de ViewInfoOptions‑klasse om informatie over de weergave op te halen bij het renderen naar PNG."
type: docs
url: /nl/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Initialiseert een instantie van de [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) klasse om informatie over de weergave op te halen bij het renderen naar PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Maak weergave-informatieopties voor PNG-formaat
view_info_options_png = ViewInfoOptions.for_png_view()

# Laad een document en verkrijg weergave-informatie voor PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Initialiseert een instantie van de ViewInfoOptions‑klasse om informatie over de weergave op te halen bij het renderen naar PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extract_text | `bool` | Schakelt tekstextractie in. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Voorbeeld

```python
from groupdocs.viewer.options import ViewInfoOptions

# Maak weergave-informatieopties voor PNG-formaat met tekstextractie ingeschakeld
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Zie ook
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
