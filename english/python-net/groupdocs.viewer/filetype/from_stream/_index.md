---
title: from_stream method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 70
---

## from_stream {#io.RawIOBase}

Detects file type by reading the file signature.



```python
def from_stream(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |


## from_stream {#io.RawIOBase-System.String}

Detects file type by reading the file signature.



```python
def from_stream(self, stream, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| password | System.String | The password to open the file. |


## from_stream {#io.RawIOBase-groupdocs.viewer.logging.ILogger}

Detects file type by reading the file signature.


### Returns 


Returns file type in case it was detected successfully otherwise returns default [`FileType.Unknown`](/viewer/python-net/groupdocs.viewer/filetype) file type.


```python
def from_stream(self, stream, logger):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| logger | groupdocs.viewer.logging.ILogger | The logger. |


## from_stream {#io.RawIOBase-System.String-groupdocs.viewer.logging.ILogger}

Detects file type by reading the file signature.


### Returns 


Returns file type in case it was detected successfully otherwise returns default [`FileType.Unknown`](/viewer/python-net/groupdocs.viewer/filetype) file type.


```python
def from_stream(self, stream, password, logger):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| password | System.String | The password to open the file. |
| logger | groupdocs.viewer.logging.ILogger | The logger. |



### See Also
* module [`groupdocs.viewer`](../../)
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype)
