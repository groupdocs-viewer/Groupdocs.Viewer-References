---
title: PdfViewOptions constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---

## __init__ {#}

Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) class.



```python
def __init__(self):
    ...
```




## __init__ {#groupdocs.viewer.interfaces.IFileStreamFactory}

Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) class.



```python
def __init__(self, file_stream_factory):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_stream_factory | groupdocs.viewer.interfaces.IFileStreamFactory | The factory which implements methods for creating and releasing output file stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `file_stream_factory` is null. |




## __init__ {#System.String}

Initializes an instance of [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions) class.



```python
def __init__(self, output_file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| output_file_path | System.String | The path for output PDF file. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `output_file_path` is null or empty. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions)
