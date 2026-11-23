---
title: "metodo try_parse"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Tenta di analizzare la stringa grezza specificata come nome di uno stile di carattere."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/
is_root: false
weight: 1060
---


## try_parse {#style-parsed}

Tenta di analizzare la stringa grezza specificata come nome di uno stile di carattere.

```python
def try_parse(cls, style, parsed):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| style | `str` | Stringa che dovrebbe essere analizzata come stile di carattere. |
| parsed | `FontStyles` | Stile di carattere analizzato in caso di successo o `FontStyles.Regular` in caso di errore. |

**Returns:** bool: True if string was successfully parsed as a correct font style; False otherwise.

### Vedi anche
* class [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/)
