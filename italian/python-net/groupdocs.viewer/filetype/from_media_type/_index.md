---
title: "from_media_type metodo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Mappa un tipo di media di file a un FileType (ad esempio, 'application/pdf' mappa a FileType.pdf)."
type: docs
url: /it/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Mappa un tipo di media del file a un [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (ad esempio, 'application/pdf' viene mappato a [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| media_type | `str` | Tipo di media del file, ad esempio, ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Vedi anche
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
