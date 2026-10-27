---
title: "Classe Watermark"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta una filigrana di testo."
type: docs
url: /it/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Rappresenta una filigrana di testo.

Consulta la documentazione online per ulteriori informazioni.

Il tipo Watermark espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Inizializza un'istanza della classe [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Il colore del watermark. Il valore predefinito è `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Il nome del carattere utilizzato per il watermark. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | La posizione del watermark. Il valore predefinito è `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | La dimensione del watermark. Il valore predefinito è [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Il testo del watermark. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Carica documento
    with Viewer("sample.docx") as viewer:
        # Crea un file HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Aggiungi watermark.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Guide operative che utilizzano `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
