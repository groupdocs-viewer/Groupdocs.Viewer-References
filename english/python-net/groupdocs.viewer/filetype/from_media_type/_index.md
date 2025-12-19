---
title: from_media_type method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/filetype/from_media_type/
is_root: false
weight: 60
---

## from_media_type {#System.String}

Maps file media type to file type e.g. 'application/pdf' will be mapped to [`FileType.PDF`](/viewer/python-net/groupdocs.viewer/filetype).


### Returns 


Returns corresponding media type when found, otherwise returns default [`FileType.Unknown`](/viewer/python-net/groupdocs.viewer/filetype) file type.


```python
def from_media_type(self, media_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| media_type | System.String | File media type e.g. application/pdf. |



### See Also
* module [`groupdocs.viewer`](../../)
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype)
