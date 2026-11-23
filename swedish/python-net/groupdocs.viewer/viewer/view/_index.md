---
title: "view metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Skapar vy av alla dokumentsidor."
type: docs
url: /sv/python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Skapar vy av alla dokumentsidor.

Läs mer

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `ViewOptions` | Visningsalternativen. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `options` är None. |
| `PasswordRequiredException` | När ett lösenord krävs för att öppna dokumentet. |
| `IncorrectPasswordException` | När det angivna lösenordet är felaktigt. |
| `GroupDocsViewerException` | När en bilaga inte kunde hittas. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Skapar vy av specifika dokumentsidor.

Läs mer

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `ViewOptions` | Visningsalternativen. |
| page_numbers | `list[int]` | Sidnumren att visa. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | när `page_numbers` är tom. |
| `PasswordRequiredException` | när lösenord krävs för att öppna dokumentet. |
| `IncorrectPasswordException` | när det angivna lösenordet är felaktigt. |
| `GroupDocsViewerException` | när bilaga inte kunde hittas. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Skapar vy av specifika dokumentsidor.

Läs mer:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | `ViewOptions` | Visningsalternativen. |
| cancellation_token | `CancellationToken` | Avbrytningstoken för att avbryta bearbetning. |
| page_numbers | `list[int]` | Sidnumren att visa. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `page_numbers` är tom. |
| `PasswordRequiredException` | När lösenord krävs för att öppna dokumentet. |
| `IncorrectPasswordException` | När det angivna lösenordet är felaktigt. |
| `GroupDocsViewerException` | När bilaga inte kunde hittas. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Se även
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
