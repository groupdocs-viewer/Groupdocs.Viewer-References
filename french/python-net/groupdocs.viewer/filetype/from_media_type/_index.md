---
title: "méthode from_media_type"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Mappe un type de média de fichier à un FileType (par ex., 'application/pdf' mappe à FileType.pdf)."
type: docs
url: /fr/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Mappe un type de média de fichier à un [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (par ex., 'application/pdf' est mappé à [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| media_type | `str` | Type de média de fichier, par ex., ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Voir aussi
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
