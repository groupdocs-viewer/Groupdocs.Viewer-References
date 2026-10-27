---
title: "propriété try_repair"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Cette propriété permet à GroupDocs.Viewer de tenter de réparer la corruption structurelle des documents PDF."
type: docs
url: /fr/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

La propriété permet à GroupDocs.Viewer de tenter de réparer la corruption structurelle des documents PDF. La valeur par défaut est False.

Cette fonctionnalité résout les problèmes suivants dans un document PDF :

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

### Voir aussi
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
