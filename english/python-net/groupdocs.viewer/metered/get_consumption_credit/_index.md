---
title: get_consumption_credit method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Retrieves count of credits consumed."
type: docs
url: /python-net/groupdocs.viewer/metered/get_consumption_credit/
is_root: false
weight: 1010
---


## get_consumption_credit

Retrieves count of credits consumed.

Following example demonstrates how to retrieve count of credits consumed.

```python
def get_consumption_credit(cls):
    ...
```

### Example

```python
from groupdocs.viewer import Metered

def get_credits():
    # Set your public and private keys
    public_key = "******"
    private_key = "******"

    # Instantiate Metered and set keys
    metered = Metered()
    metered.set_metered_key(public_key, private_key)

    # Retrieve credits consumed
    credits_used = metered.get_consumption_credit()
    print("Credits used:", credits_used)

if __name__ == "__main__":
    get_credits()
```

### See Also
* class [`Metered`](/viewer/python-net/groupdocs.viewer/metered/)
