---
title: "Classe Layer"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta un livello contenuto nel disegno CAD."
type: docs
url: /it/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Rappresenta un livello contenuto nel disegno CAD.

Il tipo Layer espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Inizializza una nuova istanza della classe [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Inizializza una nuova istanza di Layer. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Inizializza una nuova istanza di Layer. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Determina se il Layer corrente è lo stesso dell'oggetto Layer specificato. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Verifica se il [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) corrente è uguale all'oggetto specificato. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Restituisce il codice hash per l'oggetto Layer corrente. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Il nome del layer. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | L'indicatore di visibilità del layer. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Vedi anche
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
