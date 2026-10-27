---
title: "méthode view"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Crée une vue de toutes les pages du document."
type: docs
url: /fr/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Crée une vue de toutes les pages du document.

En savoir plus

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | Les options d'affichage. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `options` est None. |
| `PasswordRequiredException` | Lorsqu'un mot de passe est requis pour ouvrir le document. |
| `IncorrectPasswordException` | Lorsque le mot de passe spécifié est incorrect. |
| `GroupDocsViewerException` | Lorsque une pièce jointe n'a pas pu être trouvée. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Crée une vue de pages spécifiques du document.

En savoir plus

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | Les options d'affichage. |
| page_numbers | `list[int]` | Les numéros de page à afficher. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | lorsque `page_numbers` est vide. |
| `PasswordRequiredException` | lorsque le mot de passe est requis pour ouvrir le document. |
| `IncorrectPasswordException` | lorsque le mot de passe spécifié est incorrect. |
| `GroupDocsViewerException` | lorsque la pièce jointe est introuvable. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Crée une vue de pages spécifiques du document.

En savoir plus:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | Les options d'affichage. |
| cancellation_token | `CancellationToken` | Jeton d'annulation pour annuler le traitement. |
| page_numbers | `list[int]` | Les numéros de page à afficher. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `page_numbers` est vide. |
| `PasswordRequiredException` | Lorsque le mot de passe est requis pour ouvrir le document. |
| `IncorrectPasswordException` | Lorsque le mot de passe spécifié est incorrect. |
| `GroupDocsViewerException` | Lorsque la pièce jointe est introuvable. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Voir aussi
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
