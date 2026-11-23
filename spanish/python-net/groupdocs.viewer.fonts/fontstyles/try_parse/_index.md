---
title: "método try_parse"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Intenta analizar la cadena cruda especificada como un nombre de estilo de fuente."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Intenta analizar la cadena cruda especificada como un nombre de estilo de fuente.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| style | `str` | Cadena que debe analizarse como un estilo de fuente. |
| parsed | `FontStyles` | Estilo de fuente analizado en caso de éxito o `FontStyles.Regular` en caso de falla. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Ver también
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
