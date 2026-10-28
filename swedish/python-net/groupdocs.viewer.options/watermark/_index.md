---
title: "Watermark-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar ett textvattenmärke."
type: docs
url: /sv/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Representerar ett textvattenmärke.

Se den online-dokumentationen för mer information.

Watermark-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Initierar en instans av klassen [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Vattenstämpelns färg. Standardvärdet är `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Typsnittets namn som används för vattenstämpeln. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | Vattenstämpelns position. Standardvärdet är `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | Vattenstämpelns storlek. Standardvärdet är [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Vattenstämpelns text. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Läs in dokument
    with Viewer("sample.docx") as viewer:
        # Skapa en HTML-fil.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Lägg till vattenstämpel.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Uppgiftsguider som använder `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
