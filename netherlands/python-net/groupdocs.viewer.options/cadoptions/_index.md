---
title: "CadOptions klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De opties voor het renderen van CAD-tekeningen."
type: docs
url: /nl/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

De opties voor het renderen van CAD-tekeningen.

Voor meer informatie en codevoorbeelden, zie de Render CAD drawings and models as HTML, PDF, and image files en Specify rendering options for CAD files documentatie.

Het type CadOptions biedt de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Initialiseert een CadOptions‑instantie voor weergave op basis van hoogte. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Initialiseert een CadOptions‑instantie voor weergave op basis van schaalfactor. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Initialiseert een instantie van de [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) klasse voor weergave op basis van breedte. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Initialiseert een instantie van de CadOptions‑klasse voor weergave op basis van breedte en hoogte. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | De achtergrondkleur van de afbeelding. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | De vlag die een prestatiegerichte conversiemodus voor alle CAD-formaten inschakelt, waarbij het instellen op True de conversie versnelt ten koste van een lagere uitvoerkwaliteit; standaard is False voor maximale kwaliteit. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | De hoogte van het uitvoerresultaat (in pixels). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | De CAD-tekenlagen die moeten worden weergegeven. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | De naam van de specifieke lay-out die moet worden weergegeven. De lay-outnaam is hoofdlettergevoelig. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | Het PC3-plotterconfiguratiebestand. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | De vlag die aangeeft of lay-outs uit het CAD-document moeten worden weergegeven. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | De schaalfactor. Een waarde hoger dan 1 vergroot het uitvoerresultaat; een waarde tussen 0 en 1 verkleint het uitvoerresultaat. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | De tekenregio's die moeten worden weergegeven. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | De breedte van het uitvoerresultaat (in pixels). |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Laad CAD‑bestand
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Renderen op breedte en prestatiemodus inschakelen
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
