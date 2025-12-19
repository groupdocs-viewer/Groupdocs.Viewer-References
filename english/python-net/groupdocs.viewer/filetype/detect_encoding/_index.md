---
title: detect_encoding method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/filetype/detect_encoding/
is_root: false
weight: 20
---

## detect_encoding {#System.String}

Attempts to detect text [`FileType.TXT`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.TSV`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.CSV`](/viewer/python-net/groupdocs.viewer/filetype) files encoding by path.


### Returns 


Encoding or null when fails to detect a file encoding.


```python
def detect_encoding(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The file name or file path. |

### Example 


The example demonstrates how to detect text file encoding.


## detect_encoding {#io.RawIOBase}

Attempts to detect text [`FileType.TXT`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.TSV`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.CSV`](/viewer/python-net/groupdocs.viewer/filetype) file encoding by stream.


### Returns 


Encoding or null when fails to detect a file encoding.


```python
def detect_encoding(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |

### Example 


The example demonstrates how to detect text file encoding.



### See Also
* module [`groupdocs.viewer`](../../)
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype)
