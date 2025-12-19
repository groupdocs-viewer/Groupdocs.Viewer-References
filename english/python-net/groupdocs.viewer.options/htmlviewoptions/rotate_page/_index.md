---
title: rotate_page method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/htmlviewoptions/rotate_page/
is_root: false
weight: 40
---

## rotate_page {#int-groupdocs.viewer.options.Rotation}

Applies the clockwise rotation to a page.



```python
def rotate_page(self, page_number, rotation):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_number | int | The page number, must be strictly greater than 0 |
| rotation | groupdocs.viewer.options.Rotation | The rotation value. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentOutOfRangeException | Thrown when `page_number` is less or equal to zero. |
| ArgumentException | Thrown when rotation for the page with number `page_number` was already added. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions)
