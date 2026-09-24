---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new Attachment instance."
type: docs
url: /python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) instance.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

Initializes a new Attachment instance.

```python
def __init__(self, file_name, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_name | `str` | Attachment file name. |
| file_path | `str` | Attachment relative path e.g. "folder/file.docx" or filename when the file is located in the root of an archive, in e‑mail message or data file. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `file_path` is None or empty. |

## __init__ {#id-file_name-file_path-size}

Initializes a new instance of the Attachment class.

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| id | `str` | Unique (in context of single file) identifier of the attachment. |
| file_name | `str` | Attachment file name. |
| file_path | `str` | Attachment relative path e.g. `folder/file.docx` or filename when the file is located in the root of an archive, in e‑mail message or data file. |
| size | `int` | Attachment file size in bytes. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `file_path` is null or empty. |

## __init__ {#id-file_name-file_path-file_type-size}

Initializes a new instance of the Attachment class.

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| id | `str` | Unique (in context of single file) identifier of the attachment. |
| file_name | `str` | Attachment file name. |
| file_path | `str` | Attachment relative path e.g. `folder/file.docx` or filename when the file is located in the root of an archive, in e‑mail message or data file. |
| file_type | `FileType` | Attachment file type. |
| size | `int` | Attachment file size in bytes. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `file_type` is null. |

### See Also
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
