---
title: "from_media_type yöntemi"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bir dosya medya tipini FileType'a eşler (ör. 'application/pdf' FileType.pdf'e eşlenir)."
type: docs
url: /tr/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Bir dosya medya türünü bir [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) öğesine eşler (ör. 'application/pdf' , [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/) ile eşlenir).

```python
def from_media_type(cls, media_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| media_type | `str` | Dosya medya tipi, ör. ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Ayrıca Bakınız
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
