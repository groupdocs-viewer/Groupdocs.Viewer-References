---
title: "try_repair özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik, GroupDocs.Viewer'ın PDF belgelerindeki yapısal bozulmaları onarmaya çalışmasını sağlar."
type: docs
url: /tr/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

Bu özellik, GroupDocs.Viewer'ın PDF belgelerindeki yapısal bozulmaları onarmaya çalışmasını etkinleştirir. Varsayılan değer False'tur.

Bu özellik, bir PDF belgesindeki aşağıdaki sorunları giderir:

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

### Ayrıca Bakınız
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
