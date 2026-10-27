---
title: "Klasse CadViewInfo"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Ansichtsinformationen für eine CAD-Zeichnung dar."
type: docs
url: /de/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Stellt Ansichtsinformationen für eine CAD-Zeichnung dar.

Der Typ CadViewInfo stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Initialisiert eine neue CadViewInfo-Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | Die Liste der im CAD-Zeichnung enthaltenen Ebenen. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | Die Liste der im CAD-Zeichnung enthaltenen Layouts. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Der Typ der Datei. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Die Liste der anzuzeigenden Seiten. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Beispiel

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
Aufgabenleitfäden, die `CadViewInfo` verwenden:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
