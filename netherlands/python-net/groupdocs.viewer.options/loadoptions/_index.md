---
title: "LoadOptions-klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "De opties die worden gebruikt om een bestand te openen."
type: docs
url: /nl/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

De opties die worden gebruikt om een bestand te openen.

Het LoadOptions-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Initialiseert een instantie van de [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Initialiseert een nieuwe LoadOptions‑instantie. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | De eigenschap maakt coderingdetectie mogelijk voor [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), en [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) bestanden. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | De codering die wordt gebruikt bij het openen van tekstgebaseerde bestanden of e‑mailberichten, zoals [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), en [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Standaardwaarde is `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Het type van het te openen bestand. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Het wachtwoord om een versleuteld bestand te openen. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | De time‑out voor het laden van externe bronnen. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | De eigenschap schakelt het laden van alle externe bronnen uit, zoals afbeeldingen, behalve diegene die zijn vermeld in [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | De eigenschap maakt het mogelijk voor GroupDocs.Viewer om te proberen structurele corruptie in PDF‑documenten te repareren. Standaard is False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | De lijst met URL‑fragmenten die overeenkomen met externe bronnen die moeten worden geladen wanneer [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) is ingesteld op `True`. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
