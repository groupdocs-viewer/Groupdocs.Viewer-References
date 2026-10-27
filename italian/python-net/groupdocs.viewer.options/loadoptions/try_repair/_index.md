---
title: "proprietà try_repair"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "La proprietà consente a GroupDocs.Viewer di tentare di riparare la corruzione strutturale nei documenti PDF."
type: docs
url: /it/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

La proprietà consente a GroupDocs.Viewer di tentare di riparare la corruzione strutturale nei documenti PDF. Il valore predefinito è False.

Questa funzionalità affronta i seguenti problemi in un documento PDF:

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

### Vedi anche
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
