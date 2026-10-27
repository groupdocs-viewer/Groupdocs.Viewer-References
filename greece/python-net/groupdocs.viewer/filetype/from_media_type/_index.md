---
title: "from_media_type μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιστοιχίζει έναν τύπο μέσου αρχείου σε ένα FileType (π.χ., 'application/pdf' αντιστοιχεί σε FileType.pdf)."
type: docs
url: /el/python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 1110
---


## from_media_type {#media_type}

Αντιστοιχίζει έναν τύπο μέσου αρχείου σε ένα [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (π.χ., 'application/pdf' αντιστοιχεί στο [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)).

```python
def from_media_type(cls, media_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| media_type | `str` | Τύπος μέσου αρχείου, π.χ., ``application/pdf``. |

**Returns:** FileType: Corresponding file type when found; otherwise returns the default `FileType.unknown`.

### Δείτε επίσης
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
