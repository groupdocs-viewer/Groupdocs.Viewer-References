---
title: "metodo view"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Crea una vista di tutte le pagine del documento."
type: docs
url: /it/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Crea una vista di tutte le pagine del documento.

Per saperne di più

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `ViewOptions` | Le opzioni di visualizzazione. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `options` è None. |
| `PasswordRequiredException` | Quando è richiesta una password per aprire il documento. |
| `IncorrectPasswordException` | Quando la password specificata è errata. |
| `GroupDocsViewerException` | Quando un allegato non è stato trovato. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Crea una vista di pagine specifiche del documento.

Per saperne di più

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `ViewOptions` | Le opzioni di visualizzazione. |
| page_numbers | `list[int]` | I numeri di pagina da visualizzare. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | quando `page_numbers` è vuoto. |
| `PasswordRequiredException` | quando è necessaria una password per aprire il documento. |
| `IncorrectPasswordException` | quando la password specificata è errata. |
| `GroupDocsViewerException` | quando l'allegato non è stato trovato. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Crea una vista di pagine specifiche del documento.

Per saperne di più:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | `ViewOptions` | Le opzioni di visualizzazione. |
| cancellation_token | `CancellationToken` | Token di cancellazione per annullare l'elaborazione. |
| page_numbers | `list[int]` | I numeri di pagina da visualizzare. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `page_numbers` è vuoto. |
| `PasswordRequiredException` | Quando è necessaria una password per aprire il documento. |
| `IncorrectPasswordException` | Quando la password specificata è errata. |
| `GroupDocsViewerException` | Quando l'allegato non è stato trovato. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Vedi anche
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
