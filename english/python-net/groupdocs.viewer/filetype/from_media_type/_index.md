---
title: from_media_type method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Maps a file media type to a FileType (e.g., 'application/pdf' maps to FileType.pdf)."
type: docs
url: /python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Maps a file media type to a [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (e.g., 'application/pdf' maps to [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| media_type | `str` | File media type, e.g., ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### See Also
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
