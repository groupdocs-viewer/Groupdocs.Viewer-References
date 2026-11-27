---
title: Metered class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Provides methods for applying Metered license."
type: docs
url: /python-net/groupdocs.viewer/metered/
is_root: false
weight: 50
---


## Metered class

Provides methods for applying Metered license.

- More about Metered licensing: https://purchase.groupdocs.com/faqs/licensing/metered
- More about GroupDocs.Viewer licensing: https://docs.groupdocs.com/viewer/python-net/getting-started/licensing-and-subscription/

The Metered type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/metered/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | Retrieves count of credits consumed. |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | Retrieves amount of MBs processed. |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | Activates the product with Metered keys. |

### Example

```python
from groupdocs.viewer import Metered

def set_metered_license():
    public_key = "******"
    private_key = "******"

    if not public_key or public_key == "******" or not private_key or private_key == "******":
        print("Please set your public and private keys")
        return

    metered = Metered()
    metered.set_metered_key(public_key, private_key)

    mb_processed = metered.get_consumption_quantity()
    print("MB processed:", mb_processed)

    credits_used = metered.get_consumption_credit()
    print("Credits used:", credits_used)

if __name__ == "__main__":
    set_metered_license()
```

### See Also
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
