---
title: "for_png_view-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av ViewInfoOptions-klassen för att hämta information om vyn när man renderar till PNG."
type: docs
url: /sv/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Initierar en instans av [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) klassen för att hämta information om vyn när man renderar till PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Skapa visningsinfoalternativ för PNG-format
view_info_options_png = ViewInfoOptions.for_png_view()

# Läs in ett dokument och hämta visningsinformation för PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Initierar en instans av ViewInfoOptions-klassen för att hämta information om vyn när man renderar till PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extract_text | `bool` | Aktiverar textutvinning. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Exempel

```python
from groupdocs.viewer.options import ViewInfoOptions

# Skapa visningsinfoalternativ för PNG-format med textutdragning aktiverad
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Se även
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
