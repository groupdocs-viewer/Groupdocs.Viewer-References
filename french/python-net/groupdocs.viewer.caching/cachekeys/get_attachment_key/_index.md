---
title: "méthode get_attachment_key"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Renvoie un identifiant unique pour l'entrée du cache qui représente le fichier de pièce jointe."
type: docs
url: /fr/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Renvoie un identifiant unique pour l'entrée du cache qui représente le fichier de pièce jointe.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| attachment_id | `str` | Identifiant unique (dans le contexte d'un seul fichier) de la pièce jointe. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lancée lorsque `attachment_id` est nul ou vide. |

### Voir aussi
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
