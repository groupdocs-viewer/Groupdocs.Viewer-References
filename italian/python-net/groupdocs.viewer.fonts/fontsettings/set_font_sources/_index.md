---
title: "metodo set_font_sources"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Imposta le sorgenti da cui cercare i caratteri TrueType durante il rendering dei documenti."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Imposta le sorgenti da cui cercare i caratteri TrueType durante il rendering dei documenti.

Il metodo accetta qualsiasi combinazione di oggetti [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) individuali, elenchi di essi o una miscela di entrambi; tutti gli input vengono appiattiti in un unico elenco prima di essere applicati. I percorsi delle stringhe vengono passati così‑come e non vengono suddivisi in caratteri.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Le font sources. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `font_sources` è None. |

### Esempio

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# lista singola
FontSettings.set_font_sources([src1, src2])
# liste multiple (appiattite)
FontSettings.set_font_sources([src1], [src2])
# misto — anche appiattito
FontSettings.set_font_sources([src1, src2], src2)
```

### Vedi anche
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
