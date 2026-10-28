---
title: "Klassen LoadOptions"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Alternativen som används för att öppna en fil."
type: docs
url: /sv/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Alternativen som används för att öppna en fil.

Typen LoadOptions exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Initierar en instans av klassen [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Initierar en ny LoadOptions-instans. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | Egenskapen möjliggör kodningsdetektering för [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), och [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) filer. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | Kodningen som används när textbaserade filer eller e‑postmeddelanden öppnas, såsom [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), och [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Standardvärdet är `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Typen av filen som ska öppnas. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Lösenordet för att öppna en krypterad fil. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Timeouten för att ladda externa resurser. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | Egenskapen inaktiverar laddning av alla externa resurser såsom bilder, förutom de som listas i [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | Egenskapen möjliggör för GroupDocs.Viewer att försöka reparera strukturell korruption i PDF-dokument. Standard är False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | Listan med URL-fragment som motsvarar externa resurser som ska laddas när [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) är satt till `True`. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
