---
title: get_consumption_quantity method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Retrieves amount of MBs processed."
type: docs
url: /python-net/groupdocs.viewer/metered/get_consumption_quantity/
is_root: false
weight: 1020
---


## get_consumption_quantity

Retrieves amount of MBs processed.

```python
def get_consumption_quantity(cls):
    ...
```

### Example

```python
from groupdocs.viewer import Metered

def get_mb_processed():
    public_key = "your_public_key"
    private_key = "your_private_key"

    metered = Metered()
    metered.set_metered_key(public_key, private_key)

    mb_processed = metered.get_consumption_quantity()
    print("MB processed:", mb_processed)

if __name__ == "__main__":
    get_mb_processed()
```

### See Also
* class [`Metered`](/viewer/python-net/groupdocs.viewer/metered/)
