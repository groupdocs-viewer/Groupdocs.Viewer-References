---
title: "metodo get_attachment_key"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce un identificatore univoco per la voce della cache che rappresenta il file di allegato."
type: docs
url: /it/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Restituisce un identificatore univoco per la voce della cache che rappresenta il file di allegato.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attachment_id | `str` | Identificatore unico (nel contesto di un singolo file) dell'allegato. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Generato quando `attachment_id` è nullo o vuoto. |

### Vedi anche
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
