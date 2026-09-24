---
title: view method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates view of all document pages."
type: docs
url: /python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1130
---


## view {#options}

Creates view of all document pages.

Learn more

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | The view options. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `options` is None. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |
| `GroupDocsViewerException` | When an attachment could not be found. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-page_numbers}

Creates view of specific document pages.

Learn more

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, page_numbers):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | The view options. |
| page_numbers | `list[int]` | The page numbers to view. |

| Raises | Description |
| :- | :- |
| `ValueError` | when `page_numbers` is empty. |
| `PasswordRequiredException` | when password is required to open the document. |
| `IncorrectPasswordException` | when the specified password is incorrect. |
| `GroupDocsViewerException` | when attachment could not be found. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## view {#options-cancellation_token-page_numbers}

Creates view of specific document pages.

Learn more:

- More about different viewing options following this guide: https://docs.groupdocs.com/display/viewernet/Viewing

```python
def view(self, options, cancellation_token, page_numbers):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | The view options. |
| cancellation_token | `CancellationToken` | Cancellation token to cancel processing. |
| page_numbers | `list[int]` | The page numbers to view. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `page_numbers` is empty. |
| `PasswordRequiredException` | When password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |
| `GroupDocsViewerException` | When attachment could not be found. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("./sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
