---
title: "view-Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Erstellt eine Ansicht aller Dokumentseiten."
type: docs
url: /de/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Erstellt eine Ansicht aller Dokumentseiten.

Mehr erfahren

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `ViewOptions` | Die Ansichtoptionen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `options` None ist. |
| `PasswordRequiredException` | Wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| `IncorrectPasswordException` | Wenn das angegebene Passwort falsch ist. |
| `GroupDocsViewerException` | Wenn ein Anhang nicht gefunden werden konnte. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Erstellt eine Ansicht bestimmter Dokumentseiten.

Mehr erfahren

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `ViewOptions` | Die Ansichtoptionen. |
| page_numbers | `list[int]` | Die Seitenzahlen, die angezeigt werden sollen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | wenn `page_numbers` leer ist. |
| `PasswordRequiredException` | wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| `IncorrectPasswordException` | wenn das angegebene Passwort falsch ist. |
| `GroupDocsViewerException` | wenn der Anhang nicht gefunden werden konnte. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Erstellt eine Ansicht bestimmter Dokumentseiten.

Mehr erfahren:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | `ViewOptions` | Die Ansichtoptionen. |
| cancellation_token | `CancellationToken` | Abbruch-Token zum Abbrechen der Verarbeitung. |
| page_numbers | `list[int]` | Die Seitenzahlen, die angezeigt werden sollen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `page_numbers` leer ist. |
| `PasswordRequiredException` | Wenn ein Passwort zum Öffnen des Dokuments erforderlich ist. |
| `IncorrectPasswordException` | Wenn das angegebene Passwort falsch ist. |
| `GroupDocsViewerException` | Wenn der Anhang nicht gefunden werden konnte. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Siehe auch
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
