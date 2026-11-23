---
title: "from_media_type methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Mapt een bestandsmediatype naar een FileType (bijv., 'application/pdf' wordt gemapt naar FileType.pdf)."
type: docs
url: /nl/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Koppelt een bestandsmediatype aan een [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (bijv. 'application/pdf' koppelt aan [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| media_type | `str` | Bestandsmediatype, bijv., ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Zie ook
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
