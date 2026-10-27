---
title: "classe CadOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Le opzioni per il rendering dei disegni CAD."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Le opzioni per il rendering dei disegni CAD.

Per ulteriori informazioni ed esempi di codice, vedere la documentazione Render CAD drawings and models as HTML, PDF, and image files e Specify rendering options for CAD files.

Il tipo CadOptions espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Inizializza un'istanza di CadOptions per il rendering per altezza. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Inizializza un'istanza di CadOptions per il rendering per fattore di scala. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Inizializza un'istanza della classe [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) per il rendering per larghezza. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Inizializza un'istanza della classe CadOptions per il rendering per larghezza e altezza. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Il colore di sfondo dell'immagine. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Il flag che abilita una modalità di conversione orientata alle prestazioni per tutti i formati CAD, dove impostarlo su True accelera la conversione a costo di una qualità di output ridotta; il valore predefinito è False per la massima qualità. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | L'altezza del risultato in output (in pixel). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | I livelli di disegno CAD da renderizzare. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Il nome del layout specifico da renderizzare. Il nome del layout è sensibile al maiuscolo/minuscolo. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | Il file di configurazione del plotter PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Il flag che indica se i layout del documento CAD devono essere renderizzati. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Il fattore di scala. Un valore superiore a 1 ingrandisce il risultato in output; un valore compreso tra 0 e 1 riduce il risultato in output. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Le regioni di disegno da renderizzare. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | La larghezza del risultato in output (in pixel). |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Carica file CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # Render per larghezza e abilita la modalità prestazioni
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
