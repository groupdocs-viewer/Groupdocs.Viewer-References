---
title: "Metodo get_view_info"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce informazioni specifiche della vista e del documento."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Restituisce informazioni specifiche della vista e del documento.

Scopri di più sul documento - tipo di file, conteggio delle pagine e altre proprietà specifiche del formato:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `ViewInfoOptions` | Le opzioni delle informazioni di visualizzazione. |

**Returns:** Information about view and document specific information.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `options` è None. |
| `PasswordRequiredException` | Quando è richiesta una password per aprire il documento. |
| `IncorrectPasswordException` | Quando la password specificata è errata. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Vedi anche
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
