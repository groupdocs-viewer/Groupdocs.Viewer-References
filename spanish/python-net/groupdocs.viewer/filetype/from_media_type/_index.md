---
title: "método from_media_type"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Mapea un tipo de medio de archivo a un FileType (p.ej., 'application/pdf' se asigna a FileType.pdf)."
type: docs
url: /es/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Mapea un tipo de medio de archivo a un [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (p.ej., 'application/pdf' se asigna a [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| media_type | `str` | Tipo de medio de archivo, p.ej., ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Ver también
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
