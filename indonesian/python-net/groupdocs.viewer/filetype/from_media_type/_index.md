---
title: "metode from_media_type"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Memetakan tipe media file ke FileType (mis., 'application/pdf' dipetakan ke FileType.pdf)."
type: docs
url: /id/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Memetakan tipe media file ke [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (misalnya, 'application/pdf' dipetakan ke [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| media_type | `str` | Tipe media file, mis., ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Lihat Juga
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
