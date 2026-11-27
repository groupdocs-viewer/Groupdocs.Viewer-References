---
title: view method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates view of all document pages."
type: docs
url: /python-net/groupdocs.viewer/viewer/view/
is_root: false
weight: 1080
---


## view {#options}

Creates view of all document pages.

Learn more: More about different viewing options following this guide: https://docs.groupdocs.com/viewer/python-net/rendering-documents/

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

## view {#options-cancellation_token}

Creates view of all document pages.

Learn more

- More about different viewing options following this guide: https://docs.groupdocs.com/viewer/python-net/rendering-documents/

```python
def view(self, options, cancellation_token):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | The view options. |
| cancellation_token | `CancellationToken` | Cancellation token to send a request to cancel current view process. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `options` is None. |
| `PasswordRequiredException` | When password is required to open the document. |
| `IncorrectPasswordException` | When password that was specified is incorrect. |
| `GroupDocsViewerException` | When attachment could not be found. |

## view {#options-page_numbers}

Creates view of specific document pages.

Learn more:

- More about different viewing options following this guide: https://docs.groupdocs.com/viewer/python-net/rendering-documents/

```python
def view(self, options, page_numbers):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options | `ViewOptions` | The view options (`ViewOptions` or derived type). |
| page_numbers | `list[int]` | The page numbers to view (list of int). |

| Raises | Description |
| :- | :- |
| `ValueError` | When `page_numbers` is empty. |
| `PasswordRequiredException` | When a password is required to open the document. |
| `IncorrectPasswordException` | When the specified password is incorrect. |
| `GroupDocsViewerException` | When an attachment could not be found. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options, page_numbers=[1, 2, 3])
```

## view {#options-cancellation_token-page_numbers}

Creates view of specific document pages.

Learn more: More about different viewing options following this guide: https://docs.groupdocs.com/viewer/python-net/rendering-documents/

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
| `IncorrectPasswordException` | When password that was specified is incorrect. |
| `GroupDocsViewerException` | When attachment could not be found. |

### Aliases

These names call `view` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `view_view_options` | `view_view_options(options)`<br>`view_view_options(options, cancellation_token)`<br>`view_view_options(options, cancellation_token, page_numbers)`<br>`view_view_options(options, page_numbers)` |

### See Also
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
