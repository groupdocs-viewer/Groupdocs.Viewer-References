---
title: "metodo di ricerca"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Esegue una ricerca di testo e evidenzia il testo trovato nel documento caricato in base alle opzioni fornite."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/search/
is_root: false
weight: 1110
---


## search {#options}

Esegue una ricerca di testo e evidenzia il testo trovato nel documento caricato in base alle opzioni fornite.

```python
def search(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `SearchHighlightOptions` | Opzioni di ricerca e evidenziazione, inclusa la frase di testo da cercare. Non deve essere None. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `options` è None. |

### Vedi anche
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
