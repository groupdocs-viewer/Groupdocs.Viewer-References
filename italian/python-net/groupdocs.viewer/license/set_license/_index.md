---
title: "metodo set_license"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Applica una licenza al processo corrente."
type: docs
url: /it/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Applica una licenza al processo corrente.

```python
def set_license(self, license_source):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| license_source |  | Una stringa percorso a un file ``.lic`` o un oggetto simile a un file leggibile che fornisce i byte della licenza. Gli input simili a file vengono scritti in un file temporaneo prima di essere passati al bridge. |

| Eccezioni | Descrizione |
| :- | :- |
| `TypeError` | Se ``license_source`` non è né un percorso stringa né un oggetto simile a un file leggibile. |

### Vedi anche
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
