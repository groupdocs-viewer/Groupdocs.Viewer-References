---
title: set_metered_key method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Activates the product with Metered keys."
type: docs
url: /python-net/groupdocs.viewer/metered/set_metered_key/
is_root: false
weight: 1030
---


## set_metered_key {#public_key-private_key}

Activates the product with Metered keys.

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| public_key | `str` | The public key. |
| private_key | `str` | The private key. |

### Example

```python
from groupdocs.viewer import Metered

def set_metered_license():
    # Set your public and private keys
    public_key = "******"
    private_key = "******"

    # Check if keys are set
    if not public_key or public_key == "******" or not private_key or private_key == "******":
        print("Please set your public and private keys")
        return

    # Instantiate Metered and set keys
    metered = Metered()
    metered.set_metered_key(public_key, private_key)

    # Get a number of MBs processed
    mb_processed = metered.get_consumption_quantity()
    print("MB processed:", mb_processed)

    # Get a number of credits used
    credits_used = metered.get_consumption_credit()
    print("Credits used:", credits_used)

if __name__ == "__main__":
    set_metered_license()
```

### Aliases

These names call `set_metered_key` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `set_metered_key_file` | `set_metered_key_file(public_key, private_key)` |
| `set_metered_key_string` | `set_metered_key_string(public_key, private_key)` |

### See Also
* class [`Metered`](/viewer/python-net/groupdocs.viewer/metered/)
