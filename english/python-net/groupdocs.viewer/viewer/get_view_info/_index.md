---
title: get_view_info method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Returns information about view and document-specific details."
type: docs
url: /python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Returns information about view and document-specific details.

Learn more

- Learn more about document - file type, pages count and other format specific properties: https://docs.groupdocs.com/viewer/python-net/developer-guide/get-document-info/

```python
def get_view_info(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewInfoOptions` | The view info options. |

**Returns:** ViewInfoResult: Information about view and document-specific details.

| Raises | Description |
| :- | :- |
| `ValueError` | When `options` is None. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

## get_view_info {#options-cancellation_token}

Returns information about the view and document-specific details.

Learn more about document file type, pages count and other format‑specific properties.

- Learn more about document - file type, pages count and other format specific properties: https://docs.groupdocs.com/viewer/python-net/developer-guide/get-document-info/

```python
def get_view_info(self, options, cancellation_token):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewInfoOptions` | The view info options. |
| cancellation_token | `CancellationToken` | Cancellation token. |

**Returns:** Information about view and document specific information.

| Raises | Description |
| :- | :- |
| `ValueError` | When `options` is None. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |

### Aliases

These names call `get_view_info` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `get_view_info_view_info_options` | `get_view_info_view_info_options(options)`<br>`get_view_info_view_info_options(options, cancellation_token)` |

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
