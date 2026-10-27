---
title: "Watermark klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt een tekstwatermerk voor."
type: docs
url: /nl/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Stelt een tekstwatermerk voor.

Zie de online documentatie voor meer informatie.

Het Watermark-type exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Initialiseert een instantie van de [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | De kleur van het watermerk. Standaardwaarde is `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | De naam van het lettertype dat wordt gebruikt voor het watermerk. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | De positie van het watermerk. Standaardwaarde is `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | De grootte van het watermerk. Standaardwaarde is [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | De tekst van het watermerk. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Document laden
    with Viewer("sample.docx") as viewer:
        # Maak een HTML‑bestand.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Watermerk toevoegen.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Taakgidsen die `Watermark` gebruiken:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
