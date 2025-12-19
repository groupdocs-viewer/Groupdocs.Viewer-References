---
title: Attachment constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes new instance of [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment) class.



```python
def __init__(self):
    ...
```




## __init__ {#System.String-System.String}

Initializes new instance of [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment) class.



```python
def __init__(self, file_name, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_name | System.String | Attachment file name. |
| file_path | System.String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_name` is null or empty. |
| ArgumentException | Thrown when `file_path` is null or empty. |




## __init__ {#System.String-System.String-System.String-int}

Initializes new instance of [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment) class.



```python
def __init__(self, id, file_name, file_path, size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | System.String | Unique (in context of single file) identifier of the attachment. |
| file_name | System.String | Attachment file name. |
| file_path | System.String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| size | int | Attachment file size in bytes. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `id` is null or empty. |
| ArgumentException | Thrown when `file_name` is null or empty. |
| ArgumentException | Thrown when `file_path` is null or empty. |




## __init__ {#System.String-System.String-System.String-groupdocs.viewer.FileType-int}

Initializes new instance of [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment) class.



```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| id | System.String | Unique (in context of single file) identifier of the attachment. |
| file_name | System.String | Attachment file name. |
| file_path | System.String | Attachment relative path e.g. folder/file.docx or filename when the file is located in the root of an archive, in e-mail message or data file. |
| file_type | groupdocs.viewer.FileType | Attachment file type. |
| size | int | Attachment file size in bytes. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `id` is null or empty. |
| ArgumentException | Thrown when `file_name` is null or empty. |
| ArgumentException | Thrown when `file_path` is null or empty. |
| ArgumentNullException | Thrown when `file_type` is null. |





### See Also
* module [`groupdocs.viewer.results`](../../)
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment)
