---
title: "Classe LoadOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Le opzioni usate per aprire un file."
type: docs
url: /it/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Le opzioni usate per aprire un file.

Il tipo LoadOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Inizializza un'istanza della classe [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Inizializza una nuova istanza di LoadOptions. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | La proprietà abilita il rilevamento della codifica per i file [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/) e [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | La codifica usata durante l'apertura di file basati su testo o messaggi email come [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/) e [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Il valore predefinito è `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Il tipo del file da aprire. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | La password per aprire un file crittografato. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Il timeout per caricare risorse esterne. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | La proprietà disabilita il caricamento di tutte le risorse esterne come le immagini, eccetto quelle elencate in [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | La proprietà consente a GroupDocs.Viewer di tentare di riparare la corruzione strutturale nei documenti PDF. Il valore predefinito è False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | L'elenco di frammenti URL corrispondenti a risorse esterne che dovrebbero essere caricate quando [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) è impostato su `True`. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
