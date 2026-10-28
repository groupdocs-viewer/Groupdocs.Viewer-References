---
title: "from_media_type-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Mappar en filmediatyp till en FileType (t.ex. 'application/pdf' mappar till FileType.pdf)."
type: docs
url: /sv/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Mappar en filmediatyp till en [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (t.ex. 'application/pdf' mappar till [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| media_type | `str` | Filmediatyp, t.ex. ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Se även
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
