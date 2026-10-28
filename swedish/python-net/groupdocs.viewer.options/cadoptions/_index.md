---
title: "CadOptions-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Alternativen för att rendera CAD-ritningar."
type: docs
url: /sv/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Alternativen för att rendera CAD-ritningar.

För mer information och kodexempel, se Render CAD drawings and models as HTML, PDF, and image files och Specify rendering options for CAD files-dokumentationen.

Typen CadOptions visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Initierar en CadOptions-instans för rendering efter höjd. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Initierar en CadOptions-instans för rendering efter skalningsfaktor. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Initierar en instans av klassen [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) för rendering efter bredd. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Initierar en instans av CadOptions-klassen för rendering efter bredd och höjd. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Bildens bakgrundsfärg. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Flaggan som aktiverar ett prestandaorienterat konverteringsläge för alla CAD-format, där inställning till True påskyndar konverteringen på bekostnad av reducerad utdata kvalitet; standardvärdet är False för maximal kvalitet. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | Höjden på utdataresultatet (i pixlar). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | CAD-ritningslagren som ska renderas. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Namnet på den specifika layouten som ska renderas. Layoutnamnet är skiftlägeskänsligt. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | PC3-plotterns konfigurationsfil. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Flaggan som indikerar om layouter från CAD-dokumentet ska renderas. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Skalfaktorn. Värde högre än 1 förstorar utdataresultatet; värde mellan 0 och 1 minskar utdataresultatet. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Ritningsområdena som ska renderas. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | Bredden på utdataresultatet (i pixlar). |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Läs in CAD-fil
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Rendera efter bredd och aktivera prestandaläge
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
