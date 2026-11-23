---
title: "propiedad try_repair"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La propiedad permite que GroupDocs.Viewer intente reparar la corrupción estructural en documentos PDF."
type: docs
url: /es/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

La propiedad permite que GroupDocs.Viewer intente reparar la corrupción estructural en documentos PDF. El valor predeterminado es False.

Esta característica aborda los siguientes problemas en un documento PDF:

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

### Ver también
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
