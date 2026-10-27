---
title: "view-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Maakt een weergave van alle documentpagina's."
type: docs
url: /nl/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Maakt een weergave van alle documentpagina's.

Meer informatie

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `ViewOptions` | De weergaveopties. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `options` None is. |
| `PasswordRequiredException` | Wanneer een wachtwoord vereist is om het document te openen. |
| `IncorrectPasswordException` | Wanneer het opgegeven wachtwoord onjuist is. |
| `GroupDocsViewerException` | Wanneer een bijlage niet gevonden kon worden. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Maakt een weergave van specifieke documentpagina's.

Meer informatie

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `ViewOptions` | De weergaveopties. |
| page_numbers | `list[int]` | De paginanummers om te bekijken. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | wanneer `page_numbers` leeg is. |
| `PasswordRequiredException` | wanneer een wachtwoord vereist is om het document te openen. |
| `IncorrectPasswordException` | wanneer het opgegeven wachtwoord onjuist is. |
| `GroupDocsViewerException` | wanneer de bijlage niet gevonden kon worden. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Maakt een weergave van specifieke documentpagina's.

Meer informatie:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | `ViewOptions` | De weergaveopties. |
| cancellation_token | `CancellationToken` | Annuleringstoken om de verwerking te annuleren. |
| page_numbers | `list[int]` | De paginanummers om te bekijken. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `page_numbers` leeg is. |
| `PasswordRequiredException` | Wanneer een wachtwoord vereist is om het document te openen. |
| `IncorrectPasswordException` | Wanneer het opgegeven wachtwoord onjuist is. |
| `GroupDocsViewerException` | Wanneer de bijlage niet gevonden kon worden. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Zie ook
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
