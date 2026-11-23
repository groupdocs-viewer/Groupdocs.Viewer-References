---
title: "Methode from_media_type"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Ordnet einen Dateimediatyp einem FileType zu (z. B. 'application/pdf' wird FileType.pdf zugeordnet)."
type: docs
url: /de/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Ordnet einen Dateimedientyp einem [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) zu (z. B. wird 'application/pdf' dem [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) zugeordnet).

```python
def from_media_type(cls, media_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| media_type | `str` | Dateimediatyp, z. B. ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Siehe auch
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
