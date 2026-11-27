---
title: License class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Provides methods to license the component."
type: docs
url: /python-net/groupdocs.viewer/license/
is_root: false
weight: 40
---


## License class

Provides methods to license the component.

- More about licensing: https://purchase.groupdocs.com/faqs/licensing
- More about GroupDocs.Viewer licensing: https://docs.groupdocs.com/viewer/python-net/getting-started/licensing-and-subscription/

The License type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/license/__init__/) |  |

### Methods
| Method | Description |
| :- | :- |
| [set_license](/viewer/python-net/groupdocs.viewer/license/set_license/#license_stream) | Licenses the component. |
| [set_license](/viewer/python-net/groupdocs.viewer/license/set_license/#license_path) | Licenses the component. |

### Example

```python
import os
from groupdocs.viewer import License

def set_license_from_file():
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")
    if not os.path.exists(license_path):
        print(f"License file not found at: {license_path}")
        return
    license = License()
    license.set_license(license_path)

def set_license_from_stream():
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")
    if not os.path.exists(license_path):
        print(f"License file not found at: {license_path}")
        return
    with open(license_path, "rb") as license_stream:
        license = License()
        license.set_license(license_stream)
```

### Guides
Task guides that use `License`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)

### See Also
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
