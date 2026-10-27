---
title: "metodo for_html_view"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di ViewInfoOptions per recuperare le informazioni della vista durante il rendering in HTML."
type: docs
url: /it/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/
is_root: false
weight: 1010
---


## for_html_view

Inizializza un'istanza di ViewInfoOptions per recuperare le informazioni della vista durante il rendering in HTML.

```python
def for_html_view(cls):
    ...
```

**Returns:** ViewInfoOptions: A new ViewInfoOptions instance.

### Esempio

```python
    from groupdocs.viewer import Viewer
    from groupdocs.viewer.options import ViewInfoOptions

    # Crea opzioni di informazioni di visualizzazione per il formato HTML (pagina singola)
    options = ViewInfoOptions.for_html_view(True)

    # Carica un documento e recupera le informazioni di visualizzazione
    with Viewer("sample.xml") as viewer:
        info = viewer.get_view_info(options)
    ```

## for_html_view {#render_single_page}

Inizializza un'istanza di ViewInfoOptions per recuperare le informazioni della vista durante il rendering in HTML.

```python
def for_html_view(cls, render_single_page):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| render_single_page | `bool` | Abilita il rendering del contenuto HTML in una singola pagina. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Recupera le informazioni di visualizzazione per HTML con una singola pagina
options = ViewInfoOptions.for_html_view(True)

with Viewer("sample.xml") as viewer:
    info = viewer.get_view_info(options)
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Vedi anche
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
