---
title: set_license method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Apply a license to the current process.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| license_source |  | Either a string path to a ``.lic`` file or a readable file-like object that yields the license bytes. File-like inputs are written to a temporary file before being passed to the bridge. |

| Raises | Description |
| :- | :- |
| `TypeError` | If ``license_source`` is neither a string path nor a readable file-like object. |

### See Also
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
