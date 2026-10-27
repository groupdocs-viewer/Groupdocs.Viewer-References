---
title: "metodo for_png_view"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe ViewInfoOptions per recuperare le informazioni della vista durante il rendering in PNG."
type: docs
url: /it/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/
is_root: false
weight: 1060
---


## for_png_view

Inizializza un'istanza della classe [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) per recuperare le informazioni della vista durante il rendering in PNG.

```python
def for_png_view(cls):
    ...
```

**Returns:** ViewInfoOptions: New instance of the `ViewInfoOptions` class.

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

# Crea le opzioni di informazioni di visualizzazione per il formato PNG
view_info_options_png = ViewInfoOptions.for_png_view()

# Carica un documento e ottieni le informazioni di visualizzazione per PNG
with Viewer("sample.xml") as viewer:
    result_png = viewer.get_view_info(view_info_options_png)
```

## for_png_view {#extract_text}

Inizializza un'istanza della classe ViewInfoOptions per recuperare le informazioni della vista durante il rendering in PNG.

```python
def for_png_view(cls, extract_text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extract_text | `bool` | Abilita l'estrazione del testo. |

**Returns:** ViewInfoOptions: New instance of the ViewInfoOptions class.

### Esempio

```python
from groupdocs.viewer.options import ViewInfoOptions

# Crea le opzioni di informazioni di visualizzazione per il formato PNG con estrazione del testo abilitata
options = ViewInfoOptions.for_png_view(extractText=True)
```

### Vedi anche
* class [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/)
