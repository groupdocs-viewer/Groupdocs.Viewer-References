---
title: "Watermark-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt ein Textwasserzeichen dar."
type: docs
url: /de/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Stellt ein Textwasserzeichen dar.

Siehe die Online-Dokumentation für weitere Informationen.

Der Watermark-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Initialisiert eine Instanz der [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Die Wasserzeichenfarbe. Standardwert ist `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Der für das Wasserzeichen verwendete Schriftname. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | Die Position des Wasserzeichens. Standardwert ist `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | Die Größe des Wasserzeichens. Standardwert ist [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Der Wasserzeichentext. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Dokument laden
    with Viewer("sample.docx") as viewer:
        # Eine HTML-Datei erstellen.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Wasserzeichen hinzufügen.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Aufgabenleitfäden, die `Watermark` verwenden:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
