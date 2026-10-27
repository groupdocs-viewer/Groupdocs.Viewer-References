---
title: "properti try_repair"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Properti ini memungkinkan GroupDocs.Viewer untuk mencoba memperbaiki kerusakan struktural pada dokumen PDF."
type: docs
url: /id/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

Properti ini memungkinkan GroupDocs.Viewer untuk mencoba memperbaiki kerusakan struktural pada dokumen PDF. Nilai default adalah False.

Fitur ini menangani masalah berikut dalam dokumen PDF:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### Lihat Juga
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
