---
title: "Klasse CadOptions"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Die Optionen zum Rendern von CAD-Zeichnungen."
type: docs
url: /de/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Die Optionen zum Rendern von CAD-Zeichnungen.

Für weitere Informationen und Codebeispiele siehe die Dokumentation Render CAD drawings and models as HTML, PDF, and image files sowie Specify rendering options for CAD files.

Der Typ CadOptions stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Initialisiert eine CadOptions-Instanz für die Darstellung nach Höhe. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Initialisiert eine CadOptions-Instanz für die Darstellung nach Skalierungsfaktor. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Initialisiert eine Instanz der [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) Klasse für die Darstellung nach Breite. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Initialisiert eine Instanz der CadOptions-Klasse für die Darstellung nach Breite und Höhe. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Die Hintergrundfarbe des Bildes. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Das Flag, das einen leistungsorientierten Konvertierungsmodus für alle CAD-Formate aktiviert, wobei das Setzen auf True die Konvertierung beschleunigt, jedoch die Ausgabequalität reduziert; standardmäßig ist es auf False eingestellt für maximale Qualität. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | Die Höhe des Ausgabeergebnisses (in Pixeln). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Die CAD-Zeichnungsebenen, die gerendert werden sollen. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Der Name des spezifischen Layouts, das gerendert werden soll. Der Layout-Name ist case-sensitive. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | Die PC3-Plotter-Konfigurationsdatei. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Das Flag, das angibt, ob Layouts aus dem CAD-Dokument gerendert werden sollen. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Der Skalierungsfaktor. Ein Wert größer als 1 vergrößert das Ausgaberesultat; ein Wert zwischen 0 und 1 reduziert das Ausgaberesultat. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Die zu rendernden Zeichenbereiche. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | Die Breite des Ausgaberesultats (in Pixeln). |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD-Datei laden
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Nach Breite rendern und Leistungsmodus aktivieren
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
