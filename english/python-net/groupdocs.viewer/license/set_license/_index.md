---
title: set_license method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Licenses the component."
type: docs
url: /python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_stream}

Licenses the component.

```python
def set_license(self, license_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| license_stream | `io.RawIOBase` | The license stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `license_stream` is None. |

### Example

```python
import os
from groupdocs.viewer import License

license_path = os.path.abspath("./GroupDocs.Viewer.lic")
if os.path.exists(license_path):
    # Set license using a file path
    License().set_license(license_path)

    # Set license using a stream
    with open(license_path, "rb") as stream:
        License().set_license(stream)
```

## set_license {#license_path}

Licenses the component.

```python
def set_license(self, license_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| license_path | `str` | The license file path or a readable stream containing the license. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `license_path` is None or an empty string. |

### Example

```python
import os
from groupdocs.viewer import License

def set_license_from_file():
    # Get absolute path to license file
    license_path = os.path.abspath("./GroupDocs.Viewer.lic")

    # Check if license file exists
    if not os.path.exists(license_path):
        print(f"License file not found at: {license_path}")
        return

    # Instantiate License and set the license
    license = License()
    license.set_license(license_path)
```

### Aliases

These names call `set_license` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `set_license_stream` | `set_license_stream(license_stream)` |
| `set_license_streams` | `set_license_streams(license_stream)` |
| `set_license_file` | `set_license_file(license_path)` |
| `set_license_string` | `set_license_string(license_path)` |

### See Also
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
